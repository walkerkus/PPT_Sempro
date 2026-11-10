---
name: slidev-presentation
description: Panduan arsitektur dan aturan pembuatan slide Slidev modular (16:9, folder slides/, pemanggilan aset public/, animasi, dan mitigasi error parser).
---

# Slidev Presentation Engineer Skill

Skill ini memuat instruksi, aturan arsitektur, dan solusi mitigasi dari masalah-masalah teknis yang sering terjadi saat membangun slide presentasi modular di Slidev.

---

## 1. Arsitektur Infrastruktur Proyek

Sistem menggunakan arsitektur **multi-file terisolasi** agar slide mudah dikelola, tidak menumpuk di satu berkas, dan terstruktur rapi:

```text
ppt/
├── public/                 # SEMUA aset statis (gambar, background, diagram)
│   ├── ums-cover.png
│   └── bg-skripsi.svg
├── slides/                 # SEMUA file slide mandiri
│   ├── slide1.md           # Cover presentasi
│   ├── slide2.md           # Latar belakang & masalah
│   ├── slide3.md           # Metodologi (diagram)
│   ├── slide4.md           # Hasil & evaluasi (tabel)
│   └── slide5.md           # Penutup / Q&A
├── global-bottom.vue       # Komponen global (nomor slide otomatis: 2 / 5)
└── slides.md               # Orkestrator utama (konfigurasi 16:9 & daftar src)
```

---

## 2. Aturan File Orkestrator (`slides.md`)

File `slides.md` hanya boleh berisi **Headmatter (konfigurasi global)** dan **antrean impor `src`**:

### Template Wajib `slides.md`:
```markdown
---
theme: seriph
title: Presentasi Proposal Skripsi
aspectRatio: 16/9
canvasWidth: 980
transition: slide-left
drawings:
  persist: false
mdc: true
src: ./slides/slide1.md
---

---
src: ./slides/slide2.md
---

---
src: ./slides/slide3.md
---

---
src: ./slides/slide4.md
---

---
src: ./slides/slide5.md
---
```

### ⚠️ Larangan Keras pada `slides.md`:
1. **Dilarang menulis `src:` di luar `---`**: Jika ditulis tanpa pembatas slide, Slidev menganggapnya teks biasa dan mencetak tulisan *"src: ./slides/slide1.md"* di layar.
2. **Slide 1 digabung di Headmatter pertama**: `src: ./slides/slide1.md` diletakkan tepat sebelum penutup `---` pertama.

---

## 3. Resolusi Layar & Rasio 16:9 Penuh

- **Laptop & Proyektor Standar:** Menggunakan rasio **16:9** (`aspectRatio: 16/9`, `canvasWidth: 980`).
- **Garis Hitam di Kiri/Kanan (Pillarbox):** Muncul karena bilah URL, bookmark, dan taskbar browser mengurangi tinggi layar efektif.
- **Solusi Tampilan Layar Penuh:** Saat slide terbuka di browser, tekan shortcut tombol keyboard:
  - **`F`** : Mode Fullscreen Slidev (otomatis menyembunyikan panel browser).
  - **`F11`** : Mode Fullscreen bawaan browser.

---

## 4. Aturan Pemanggilan Aset Statis (`public/`)

Folder `public/` dipetakan langsung sebagai akar web server (`/`).

### Aturan Penulisan Path:
- ❌ **SALAH:** `background: public/ums-cover.png` atau `src="public/ums-cover.png"` *(Menyebabkan 404 Not Found)*
- ✅ **BENAR:** `background: /ums-cover.png` atau `src="/ums-cover.png"`

### Cara Pasang Background Gambar:
1. **Cara 1 — Frontmatter Slide (Layout bawaan `cover`):**
   ```yaml
   ---
   layout: cover
   background: /ums-cover.png
   ---
   ```
2. **Cara 2 — Kontainer Penuh CSS (Direkomendasikan untuk kustom layout cover):**
   ```html
   <div class="custom-cover">
     <h1>Judul Slide</h1>
   </div>

   <style scoped>
   .custom-cover {
     position: absolute;
     inset: 0;
     width: 100%;
     height: 100%;
     background-image: url('/ums-cover.png');
     background-size: cover;
     background-position: center;
     background-repeat: no-repeat;
   }
   </style>
   ```

---

## 5. Mitigasi Bug Parser Markdown (PENTING!)

### Masalah 1: Baris Kosong di Atas File Slide
- **Gejala:** Slide 1 kosong atau bergeser menjadi Slide 2.
- **Penyebab:** Ada karakter spasi atau newline kosong sebelum `---` di baris pertama file slide.
- **Solusi:** Baris ke-1 file `slides/*.md` **WAJIB** dimulai tepat pada baris pertama dengan `---`.

### Masalah 2: Kode HTML Bocor / Tampil Mentah di Slide
- **Gejala:** Teks HTML seperti `<h1 class="...">` muncul sebagai blok teks abu-abu di layar.
- **Penyebab:** Menggunakan **indentasi 4 spasi atau tab** di dalam tag HTML. Parser Markdown (CommonMark) menganggap 4 spasi sebagai *Indented Code Block* (`<pre><code>`).
- **Solusi:** Jangan beri indentasi 4 spasi pada tag HTML di slide. Buat rata kiri atau maksimal 2 spasi.

---

## 6. Pengaturan Animasi & Transisi

### Transisi Antar-Slide
Atur transisi di frontmatter slide:
```yaml
---
transition: slide-left   # Pilihan: slide-left, slide-right, fade, slide-up
---
```

### Animasi Muncul Bertahap (Per Item / Per Baris)
Gunakan tag bawaan `<v-clicks>` atau direktif `v-click`:

```markdown
# Metodologi Penelitian

<v-clicks>

- Tahap 1: Pengumpulan data primer
- Tahap 2: Pra-pemrosesan teks dan normalisasi
- Tahap 3: Pelatihan model IndoBERT
- Tahap 4: Pengujian akurasi & evaluasi

</v-clicks>
```

Atau pada elemen individual:
```html
<div v-click class="p-4 bg-blue-500/10">
  Muncul pada klik pertama
</div>
<div v-click="2" class="p-4 bg-emerald-500/10">
  Muncul pada klik kedua
</div>
```

### Animasi CSS Kustom (Keyframes)
Gunakan `<style scoped>` untuk animasi halus:
```html
<style scoped>
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(12px); }
  to { opacity: 1; transform: translateY(0); }
}

.anim-title {
  animation: fadeUp 0.8s 0.2s both ease-out;
}
</style>
```

---

## 7. Diagram, Rumus, dan Kode Program

1. **Diagram Alur (Mermaid):**
   ````markdown
   ```mermaid
   flowchart LR
     A[Input] --> B[Model] --> C[Output]
   ```
   ````
2. **Rumus Matematika (KaTeX):**
   - Inline: `$E = mc^2$`
   - Blok terpusat: `$$\text{Similarity}(A, B) = \frac{A \cdot B}{\|A\| \|B\|}$$`
3. **Cuplikan Kode (Syntax Highlighting & Fokus Baris):**
   ````markdown
   ```python {all|1-2|4-6}
   import torch
   from transformers import AutoModel

   model = AutoModel.from_pretrained("indobenchmark/indobert-base-p1")
   inputs = tokenizer(text, return_tensors="pt")
   outputs = model(**inputs)
   ```
   ````

---

## 8. Checklist Verifikasi AI Sebelum Menyelesaikan Tugas

Sebelum melaporkan pekerjaan selesai, pastikan:
1. [ ] Tidak ada baris kosong sebelum `---` di baris pertama file slide.
2. [ ] Tidak ada indentasi 4 spasi pada tag HTML yang bisa memicu *indented code block*.
3. [ ] Path gambar di `public/` dipanggil dengan `/gambar.png` (tanpa kata `public`).
4. [ ] File slide baru sudah didaftarkan di `slides.md` dengan format `--- \n src: ./slides/slideX.md \n ---`.
5. [ ] Perintah `npm run build` sukses dieksekusi dengan kode keluar 0.

