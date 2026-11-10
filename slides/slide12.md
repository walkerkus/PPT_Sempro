---
layout: default
transition: fade
class: ums-closing-slide
---

<!-- SLIDE 12 — PENUTUP / TERIMA KASIH -->
<!-- Canvas: 980 x 552 | Background: /16.jpg -->

<div class="ums-s12">
  <main class="ums-s12__main">
    <div class="ums-s12__box">
      <!-- HEADER CATEGORY -->
      <div class="ums-s12__category">
        <span>SEMINAR PROPOSAL SKRIPSI</span>
        <span class="ums-s12__divider">/</span>
        <span>TEKNIK INFORMATIKA</span>
      </div>
      <!-- MAIN THANKS TITLE -->
      <h1 class="ums-s12__title">Terima Kasih</h1>
      <p class="ums-s12__subtitle">
        Secara keseluruhan, penelitian ini diharapkan dapat memberikan evaluasi yang lebih menyeluruh terhadap penggunaan LLM dalam asisten belanja berbasis AI.
      </p>
      <div class="ums-s12__line" aria-hidden="true"></div>
      <!-- Q&A BADGE -->
      <div class="ums-s12__qa">
        <span class="ums-s12__qa-badge">SESI TANYA JAWAB</span>
        <p class="ums-s12__qa-text">Mohon masukan, saran, dan arahan dari Bapak/Ibu Dosen Penguji &amp; Pembimbing.</p>
      </div>
      <!-- FOOTER IDENTITY -->
      <div class="ums-s12__identity">
        <div class="ums-s12__person">
          <span class="ums-s12__label">PENYUSUN</span>
          <strong>Muhammad Syahid Kusasih</strong>
          <span>NIM: L200230272</span>
        </div>
        <div class="ums-s12__separator"></div>
        <div class="ums-s12__person">
          <span class="ums-s12__label">DOSEN PEMBIMBING</span>
          <strong>Helmi Imaduddin, S.Kom., M.Eng.</strong>
          <span>Universitas Muhammadiyah Surakarta</span>
        </div>
      </div>
    </div>
  </main>
</div>

<style scoped>
/* ===========================================
   SLIDE 12 — CLOSING & THANK YOU SLIDE
   Canvas: 980 × 552
   Background: Official UMS /16.jpg
   =========================================== */

.ums-s12 {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  overflow: hidden;
  isolation: isolate;
  background-color: #303485;
  background-image: url('/16.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color: #FFFFFF;
  font-family: 'Inter', 'Aptos', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
}
.ums-s12, .ums-s12 * {
  box-sizing: border-box;
}

.ums-s12__main {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 40px;
}

.ums-s12__box {
  width: 680px;
  max-width: 100%;
  padding: 24px 30px;
  background: rgba(255, 255, 255, 0.98);
  border: 3px solid #303485;
  box-shadow: 6px 6px 0px #D5A126;
  color: #242867;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.ums-s12__category {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  color: #303485;
  font-size: 8.5px;
  font-weight: 800;
  letter-spacing: .12em;
  padding: 3px 8px;
  background: #E8EDF8;
  border: 1.5px solid #303485;
  margin-bottom: 10px;
}
.ums-s12__divider {
  color: #929EB9;
}

.ums-s12__title {
  margin: 0;
  padding: 0;
  font-size: 38px;
  font-weight: 850;
  line-height: 1.1;
  letter-spacing: -.03em;
  color: #242867;
}

.ums-s12__subtitle {
  max-width: 540px;
  margin: 8px 0 0;
  font-size: 11px;
  line-height: 1.45;
  color: #55627D;
}
.ums-s12__subtitle em {
  font-style: italic;
  font-weight: 600;
}

.ums-s12__line {
  width: 100px;
  height: 3px;
  background: #303485;
  margin: 14px 0 12px;
}

.ums-s12__qa {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 6px 14px;
  background: #F4F7FC;
  border: 1.5px solid #303485;
  margin-bottom: 14px;
}
.ums-s12__qa-badge {
  font-size: 8px;
  font-weight: 800;
  letter-spacing: .08em;
  color: #FFFFFF;
  background: #303485;
  padding: 2px 6px;
}
.ums-s12__qa-text {
  margin: 0;
  font-size: 10px;
  font-weight: 600;
  color: #303485;
}

.ums-s12__identity {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 24px;
  width: 100%;
  padding-top: 10px;
  border-top: 1.5px solid #D8DEEB;
}
.ums-s12__person {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.ums-s12__label {
  font-size: 7.5px;
  font-weight: 800;
  letter-spacing: .09em;
  color: #7D88A3;
  margin-bottom: 2px;
}
.ums-s12__person strong {
  font-size: 11px;
  font-weight: 750;
  color: #242867;
}
.ums-s12__person span {
  font-size: 9px;
  color: #64708A;
  margin-top: 1px;
}
.ums-s12__separator {
  width: 1px;
  height: 30px;
  background: #D8DEEB;
}
</style>
