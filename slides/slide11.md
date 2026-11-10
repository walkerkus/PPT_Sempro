---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 11 — PROGRES PENELITIAN -->
<!-- Canvas: 980 x 552 | Background: /13.jpg -->

<div class="ums-s11">
  <header class="ums-s11__header">
    <div class="ums-s11__section">
      <span>10 / PROGRES PENELITIAN</span>
    </div>
    <h1 class="ums-s11__title">Progres Pengembangan Sementara</h1>
    <p class="ums-s11__intro">Implementasi antarmuka pengguna telah selesai dibangun menggunakan data simulasi <em>dummy</em> sebelum integrasi backend.</p>
  </header>
  <main class="ums-s11__main">
    <div class="ums-s11__grid">
      <!-- CARD 1: FRONTEND SISTEM MANAJEMEN AI -->
      <section v-click="1" class="ums-s11__card">
        <div class="ums-s11__card-head">
          <span class="ums-s11__badge">KOMPONEN 01</span>
          <div class="ums-s11__status-tag">
            <span class="ums-s11__status-dot"></span>
            <span>SELESAI (FRONTEND)</span>
          </div>
        </div>
        <div class="ums-s11__card-body">
          <div class="ums-s11__card-icon">
            <svg viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Sistem Manajemen Agen AI">
              <rect x="5" y="6" width="34" height="30" rx="3" fill="#EEF2FA" stroke="#303485" stroke-width="2"/>
              <path d="M5 14H39" stroke="#303485" stroke-width="1.8"/>
              <circle cx="10" cy="10" r="1.5" fill="#303485"/>
              <circle cx="15" cy="10" r="1.5" fill="#303485"/>
              <circle cx="20" cy="10" r="1.5" fill="#303485"/>
              <rect x="9" y="19" width="12" height="12" fill="#FFFFFF" stroke="#303485" stroke-width="1.4"/>
              <path d="M25 20H34M25 25H34M25 30H31" stroke="#303485" stroke-width="1.8" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="ums-s11__card-copy">
            <h2>Frontend Sistem Manajemen Agen AI</h2>
            <p>Antarmuka orkestrasi model, pemantauan status agen, serta konfigurasi instruksi dan <em>prompt template</em>.</p>
          </div>
        </div>
        <div class="ums-s11__features">
          <span>Konfigurasi Prompt</span>
          <span>Panel Pemilihan LLM</span>
          <span>Log Percakapan Dummy</span>
        </div>
      </section>
      <!-- CARD 2: FRONTEND TOKO E-COMMERCE SIMULASI -->
      <section v-click="2" class="ums-s11__card">
        <div class="ums-s11__card-head">
          <span class="ums-s11__badge">KOMPONEN 02</span>
          <div class="ums-s11__status-tag">
            <span class="ums-s11__status-dot"></span>
            <span>SELESAI (FRONTEND)</span>
          </div>
        </div>
        <div class="ums-s11__card-body">
          <div class="ums-s11__card-icon">
            <svg viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Toko E-Commerce Simulasi">
              <rect x="5" y="8" width="34" height="28" rx="3" fill="#EEF2FA" stroke="#303485" stroke-width="2"/>
              <path d="M12 8V6C12 4.9 12.9 4 14 4H30C31.1 4 32 4.9 32 6V8" fill="none" stroke="#303485" stroke-width="1.8"/>
              <path d="M11 18H33M11 25H27" stroke="#303485" stroke-width="1.8" stroke-linecap="round"/>
              <circle cx="22" cy="27" r="8" fill="#FFFFFF" stroke="#303485" stroke-width="1.8"/>
              <path d="M19 27L21 29L25 25" fill="none" stroke="#D5A126" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </div>
          <div class="ums-s11__card-copy">
            <h2>Frontend Toko <em>E-Commerce</em> Simulasi</h2>
            <p>Antarmuka interaksi belanja peserta mencakup penelusuran katalog produk, widget Chat AI, keranjang, dan checkout.</p>
          </div>
        </div>
        <div class="ums-s11__features">
          <span>Katalog Produk Dummy</span>
          <span>Widget Chat Asisten</span>
          <span>Simulasi Keranjang Belanja</span>
        </div>
      </section>
    </div>
    <!-- REASON & NEXT STEPS PANEL -->
    <section v-click="3" class="ums-s11__rationale">
      <div class="ums-s11__rationale-icon">
        <svg viewBox="0 0 36 36" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Catatan Metodologi">
          <circle cx="18" cy="18" r="14" fill="#FFFFFF" stroke="#303485" stroke-width="2"/>
          <path d="M18 11V19M18 23V25" stroke="#303485" stroke-width="2.4" stroke-linecap="round"/>
        </svg>
      </div>
      <div class="ums-s11__rationale-copy">
        <strong>Fokus Tahap Saat Ini &amp; Rencana Selanjutnya:</strong>
        <p>Implementasi masih menggunakan data simulasi (<em>dummy</em>) untuk memastikan tata letak dan alur antarmuka telah matang serta bebas dari kendala interaksi pengguna, sebelum integrasi <em>backend</em>, pemanggilan <em>LLM API</em>, dan pencatatan metrik dihubungkan.</p>
      </div>
      <div class="ums-s11__rationale-badge">
        <span>TAHAP SELANJUTNYA</span>
        <strong>Integrasi Backend &amp; API</strong>
      </div>
    </section>
  </main>
</div>

<style scoped>
/* ===========================================
   SLIDE 11 — PROGRESS PRESENTATION (NEO-BRUTALISM)
   Canvas: 980 × 552
   Background: Official UMS /13.jpg
   =========================================== */

.ums-s11 {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  overflow: hidden;
  isolation: isolate;
  background: #ffffff url('/13.jpg') center / cover no-repeat;
  color: #242867;
  font-family: 'Inter', 'Aptos', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
}
.ums-s11, .ums-s11 * {
  box-sizing: border-box;
}

/* HEADER */
.ums-s11__header {
  position: absolute;
  top: 84px;
  left: 55px;
  right: 55px;
}
.ums-s11__section {
  display: flex;
  align-items: center;
  margin-bottom: 6px;
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .11em;
  color: #303485;
}
.ums-s11__title {
  margin: 0;
  padding: 0;
  font-size: 26px;
  font-weight: 720;
  line-height: 1.18;
  letter-spacing: -.032em;
  color: #242867;
}
.ums-s11__title em {
  font-weight: 500;
  font-style: italic;
}
.ums-s11__intro {
  margin: 5px 0 0;
  font-size: 11px;
  line-height: 1.4;
  color: #68728C;
}

/* MAIN CONTENT */
.ums-s11__main {
  position: absolute;
  top: 170px;
  left: 55px;
  right: 55px;
  bottom: 84px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

/* TWO CARDS GRID */
.ums-s11__grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
}
.ums-s11__card {
  height: 154px;
  display: flex;
  flex-direction: column;
  padding: 10px 14px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s11__card-head {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-bottom: 5px;
  border-bottom: 1.5px solid #303485;
}
.ums-s11__badge {
  font-size: 8px;
  font-weight: 800;
  letter-spacing: .1em;
  color: #303485;
  background: #E8EDF8;
  padding: 2px 6px;
  border: 1px solid #303485;
}
.ums-s11__status-tag {
  display: flex;
  align-items: center;
  gap: 5px;
  font-size: 8px;
  font-weight: 750;
  letter-spacing: .05em;
  color: #303485;
}
.ums-s11__status-dot {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #2E947D;
}
.ums-s11__card-body {
  display: flex;
  align-items: flex-start;
  gap: 12px;
  margin-top: 8px;
}
.ums-s11__card-icon {
  width: 40px;
  height: 40px;
  flex: 0 0 40px;
}
.ums-s11__card-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s11__card-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s11__card-copy h2 {
  margin: 0;
  padding: 0;
  font-size: 13.5px;
  font-weight: 750;
  line-height: 1.25;
  color: #242867;
}
.ums-s11__card-copy h2 em {
  font-style: italic;
  font-weight: 600;
}
.ums-s11__card-copy p {
  margin: 3px 0 0;
  font-size: 9.5px;
  line-height: 1.35;
  color: #606C88;
}
.ums-s11__card-copy p em {
  font-style: italic;
}
.ums-s11__features {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 5px;
  margin-top: auto;
  padding-top: 6px;
}
.ums-s11__features span {
  padding: 2px 6px;
  border: 1px solid #303485;
  background: #F0F3FA;
  color: #303485;
  font-size: 8px;
  font-weight: 700;
  line-height: 1.1;
}

/* RATIONALE PANEL */
.ums-s11__rationale {
  display: flex;
  align-items: center;
  gap: 14px;
  height: 60px;
  padding: 8px 16px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s11__rationale-icon {
  width: 32px;
  height: 32px;
  flex: 0 0 32px;
}
.ums-s11__rationale-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s11__rationale-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s11__rationale-copy strong {
  display: block;
  color: #303485;
  font-size: 10px;
  font-weight: 750;
}
.ums-s11__rationale-copy p {
  margin: 2px 0 0;
  color: #55627D;
  font-size: 9px;
  line-height: 1.35;
}
.ums-s11__rationale-copy p em {
  font-style: italic;
}
.ums-s11__rationale-badge {
  flex: 0 0 auto;
  text-align: right;
  padding-left: 14px;
  border-left: 1.5px solid #CBD5E8;
}
.ums-s11__rationale-badge span {
  display: block;
  color: #7E8AA6;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .06em;
}
.ums-s11__rationale-badge strong {
  display: block;
  color: #303485;
  font-size: 10px;
  font-weight: 750;
  margin-top: 1px;
}

/* CLICK REVEAL */
.ums-s11__card,
.ums-s11__rationale {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .6s ease,
    transform .6s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s11 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(10px) !important;
  pointer-events: none;
}
</style>
