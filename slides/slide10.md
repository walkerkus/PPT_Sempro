---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 10 — ANALISIS DATA DAN KONTRIBUSI -->
<!-- Canvas: 980 x 552 | Background: /13.jpg -->
<!-- HTML kontigu agar kompatibel dengan Slidev Markdown -->

<div class="ums-s10">
  <header class="ums-s10__header">
    <div class="ums-s10__section">
      <span>09 / ANALISIS DAN KONTRIBUSI</span>
    </div>
    <h1 class="ums-s10__title">Analisis Data dan Kontribusi yang Diharapkan</h1>
    <p class="ums-s10__intro">Mengintegrasikan hasil benchmark, perilaku belanja, dan pengalaman pengguna untuk mengevaluasi pemilihan LLM.</p>
  </header>
  <main class="ums-s10__main">
    <div class="ums-s10__headings">
      <span>PENDEKATAN ANALISIS</span>
      <span>FOKUS PENGUKURAN</span>
    </div>
    <div class="ums-s10__analysis-list">
      <!-- ANALYSIS 01 -->
      <section v-click="1" class="ums-s10__analysis-row">
        <div class="ums-s10__analysis-name">
          <span class="ums-s10__index">01</span>
          <div class="ums-s10__illustration">
            <svg viewBox="0 0 52 52" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Grafik analisis kinerja LLM">
              <rect x="5" y="6" width="42" height="40" rx="5" fill="#EEF1F9" stroke="#BAC5DF"/>
              <path d="M12 37H41M12 37V13" fill="none" stroke="#A7B4D0" stroke-width="1.4"/>
              <rect class="ums-s10__bar ums-s10__bar--a" x="17" y="24" width="5" height="13" rx="1" fill="#8797C8"/>
              <rect class="ums-s10__bar ums-s10__bar--b" x="26" y="17" width="5" height="20" rx="1" fill="#303485"/>
              <rect class="ums-s10__bar ums-s10__bar--c" x="35" y="21" width="5" height="16" rx="1" fill="#A8B5D9"/>
              <path class="ums-s10__graph-trend" d="M19 20L28 12L37 16" fill="none" stroke="#C79A2D" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </div>
          <div class="ums-s10__analysis-copy">
            <span>EKSPERIMEN I</span>
            <h2>Analisis Kinerja Agen</h2>
          </div>
        </div>
        <div class="ums-s10__analysis-detail">
          <span class="ums-s10__analysis-connector"></span>
          <p>Perbandingan <strong>keberhasilan, ketepatan, efisiensi, dan konsistensi</strong> antar-LLM berdasarkan hasil benchmark.</p>
        </div>
      </section>
      <!-- ANALYSIS 02 -->
      <section v-click="2" class="ums-s10__analysis-row">
        <div class="ums-s10__analysis-name">
          <span class="ums-s10__index">02</span>
          <div class="ums-s10__illustration">
            <svg viewBox="0 0 52 52" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ilustrasi pengukuran purchase funnel">
              <path d="M5 8H47L37 19H15Z" fill="#DFE5F4" stroke="#92A2CC" stroke-width="1.3"/>
              <path d="M15 22H37L32 32H20Z" fill="#B6C3E2" stroke="#92A2CC" stroke-width="1.2"/>
              <path d="M20 35H32L28 44H24Z" fill="#303485"/>
              <path class="ums-s10__funnel-trace" d="M26 10V42" fill="none" stroke="#C89B2A" stroke-width="2.3" stroke-dasharray="4 4"/>
              <circle cx="26" cy="27" r="3" fill="#FFFFFF" stroke="#303485" stroke-width="1.4"/>
            </svg>
          </div>
          <div class="ums-s10__analysis-copy">
            <span>EKSPERIMEN II</span>
            <h2>Analisis <em>Purchase Funnel</em></h2>
          </div>
        </div>
        <div class="ums-s10__analysis-detail">
          <span class="ums-s10__analysis-connector"></span>
          <p>Perbandingan <strong>ATCR dan tahapan perilaku belanja</strong> antar-LLM dengan mempertimbangkan kategori produk.</p>
        </div>
      </section>
      <!-- ANALYSIS 03 -->
      <section v-click="3" class="ums-s10__analysis-row">
        <div class="ums-s10__analysis-name">
          <span class="ums-s10__index">03</span>
          <div class="ums-s10__illustration">
            <svg viewBox="0 0 52 52" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ilustrasi analisis hubungan antarvariabel">
              <path class="ums-s10__network-lines" d="M15 14L38 17L26 39L15 14" fill="none" stroke="#8B9BC6" stroke-width="1.8"/>
              <circle class="ums-s10__network-node" cx="15" cy="14" r="6" fill="#303485"/>
              <circle class="ums-s10__network-node" cx="38" cy="17" r="6" fill="#8193C4"/>
              <circle class="ums-s10__network-node" cx="26" cy="39" r="6" fill="#BE972E"/>
              <circle cx="15" cy="14" r="2" fill="#FFFFFF"/>
              <circle cx="38" cy="17" r="2" fill="#FFFFFF"/>
              <circle cx="26" cy="39" r="2" fill="#FFFFFF"/>
            </svg>
          </div>
          <div class="ums-s10__analysis-copy">
            <span>EKSPERIMEN II &amp; INTEGRASI</span>
            <h2>Pengalaman &amp; Hubungan</h2>
          </div>
        </div>
        <div class="ums-s10__analysis-detail">
          <span class="ums-s10__analysis-connector"></span>
          <p>Analisis <strong>penilaian pengalaman peserta</strong> serta keterkaitannya dengan kualitas bantuan AI dan tindakan belanja.</p>
        </div>
      </section>
    </div>
    <!-- THREE-TO-ONE VISUAL CONNECTION -->
    <div v-click="4" class="ums-s10__merge">
      <svg viewBox="0 0 840 28" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path class="ums-s10__merge-track" d="M140 0V10H420M700 0V10H420M420 0V27"/>
        <path class="ums-s10__merge-active" d="M140 0V10H420M700 0V10H420M420 0V27"/>
        <path class="ums-s10__merge-arrow" d="M415 22L420 27L425 22" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </div>
    <!-- RESEARCH CONTRIBUTION -->
    <section v-click="4" class="ums-s10__contribution">
      <div class="ums-s10__contribution-icon">
        <svg viewBox="0 0 58 58" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Integrasi hasil penelitian">
          <path d="M11 12L29 21L47 12L29 3Z" fill="#DCE4F5" stroke="#8596C2" stroke-width="1.4" stroke-linejoin="round"/>
          <path d="M11 24L29 33L47 24" fill="none" stroke="#8495C1" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M11 36L29 45L47 36" fill="none" stroke="#8495C1" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <circle class="ums-s10__synthesis-node" cx="29" cy="21" r="6" fill="#303485"/>
          <path d="M26 21L28 23L32 19" fill="none" stroke="#FFFFFF" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <div class="ums-s10__contribution-copy">
        <span>HASIL YANG DIHARAPKAN</span>
        <h2>Gambaran Yang Lebih Lengkap Dalam Memilih LLM</h2>
        <p>Untuk asisten penjualan, bukan hanya berdasarkan kemampuan teknisnya, tetapi juga respons penggunanya.</p>
      </div>
    </section>
  </main>
</div>

<style scoped>
/* =============================================
   SLIDE 10 — ANALYSIS & RESEARCH CONTRIBUTION
   Canvas: 980 × 552
   Background: Official UMS /13.jpg
   ============================================= */

/* 01 — CANVAS */
.ums-s10 {
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
.ums-s10,
.ums-s10 * {
  box-sizing: border-box;
}

/* 02 — HEADER */
.ums-s10__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 55px;
}
.ums-s10__section {
  display: flex;
  align-items: center;
  margin-bottom: 8px;
  color: #303485;
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .11em;
}
.ums-s10__title {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 27px;
  font-weight: 720;
  line-height: 1.18;
  letter-spacing: -.032em;
}
.ums-s10__intro {
  margin: 7px 0 0;
  color: #68728C;
  font-size: 11.5px;
  line-height: 1.45;
}

/* 03 — MAIN LAYOUT */
.ums-s10__main {
  position: absolute;
  top: 178px;
  left: 70px;
  right: 70px;
  bottom: 84px;
}

/* 04 — COLUMN HEADINGS */
.ums-s10__headings {
  display: grid;
  grid-template-columns: 43% 57%;
  align-items: center;
  height: 24px;
  border-bottom: 2px solid #303485;
}
.ums-s10__headings span {
  color: #303485;
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .09em;
}
.ums-s10__headings span:first-child {
  padding-left: 36px;
}
.ums-s10__headings span:last-child {
  padding-left: 16px;
}

/* 05 — ANALYSIS ROWS */
.ums-s10__analysis-list {
  display: flex;
  flex-direction: column;
  gap: 6px;
}
.ums-s10__analysis-row {
  display: grid;
  grid-template-columns: 43% 57%;
  align-items: center;
  height: 48px;
  min-height: 48px;
  border: 1.5px solid #303485;
  box-shadow: 2px 2px 0px #303485;
  background: #FFFFFF;
}
.ums-s10__analysis-row:nth-child(even) {
  background: #FFFFFF;
}

/* 06 — ANALYSIS LEFT COLUMN */
.ums-s10__analysis-name {
  display: flex;
  align-items: center;
  gap: 10px;
  min-width: 0;
  padding: 4px 8px 4px 3px;
}
.ums-s10__index {
  flex: 0 0 16px;
  color: #9AA5BC;
  font-size: 10px;
  font-weight: 650;
}
.ums-s10__illustration {
  width: 38px;
  height: 38px;
  flex: 0 0 38px;
}
.ums-s10__illustration svg {
  display: block;
  width: 100%;
  height: 100%;
  overflow: visible;
}
.ums-s10__analysis-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s10__analysis-copy > span {
  display: block;
  margin-bottom: 2px;
  color: #8793AD;
  font-size: 7px;
  font-weight: 700;
  letter-spacing: .075em;
}
.ums-s10__analysis-copy h2 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 12px;
  font-weight: 700;
  line-height: 1.25;
  letter-spacing: -.012em;
}
.ums-s10__analysis-copy h2 em {
  font-style: italic;
  font-weight: 550;
}

/* 07 — ANALYSIS RIGHT COLUMN */
.ums-s10__analysis-detail {
  display: flex;
  align-items: center;
  gap: 11px;
  min-width: 0;
  padding: 4px 3px 4px 16px;
}
.ums-s10__analysis-connector {
  position: relative;
  width: 16px;
  height: 1px;
  flex: 0 0 16px;
  background: #A9B4CE;
  transform-origin: left center;
}
.ums-s10__analysis-connector::after {
  content: "";
  position: absolute;
  right: 0;
  top: -2px;
  width: 5px;
  height: 5px;
  border-top: 1px solid #8999BD;
  border-right: 1px solid #8999BD;
  transform: rotate(45deg);
}
.ums-s10__analysis-detail p {
  margin: 0;
  color: #56617B;
  font-size: 9.8px;
  line-height: 1.38;
}
.ums-s10__analysis-detail strong {
  color: #303485;
  font-weight: 650;
}

/* 08 — MERGE DIAGRAM */
.ums-s10__merge {
  width: 100%;
  height: 18px;
}
.ums-s10__merge svg {
  display: block;
  width: 100%;
  height: 18px;
  overflow: visible;
}
.ums-s10__merge-track {
  fill: none;
  stroke: #D5DCEB;
  stroke-width: 1.4;
  stroke-linejoin: round;
}
.ums-s10__merge-active {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-linejoin: round;
  stroke-linecap: round;
  stroke-dasharray: 650;
  stroke-dashoffset: 650;
}
.ums-s10__merge-arrow {
  opacity: 0;
}
.ums-s10__merge:not(.slidev-vclick-hidden)
.ums-s10__merge-active {
  animation: ums-s10-merge-draw .9s ease forwards;
}
.ums-s10__merge:not(.slidev-vclick-hidden)
.ums-s10__merge-arrow {
  animation: ums-s10-arrow-in .3s .75s ease forwards;
}
@keyframes ums-s10-merge-draw {
  to { stroke-dashoffset: 0; }
}
@keyframes ums-s10-arrow-in {
  to { opacity: 1; }
}

/* 09 — CONTRIBUTION PANEL */
.ums-s10__contribution {
  display: flex;
  align-items: center;
  gap: 15px;
  width: 100%;
  min-height: 72px;
  padding: 8px 16px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  border-radius: 0px;
}
.ums-s10__contribution-icon {
  width: 48px;
  height: 48px;
  flex: 0 0 48px;
}
.ums-s10__contribution-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s10__contribution-copy {
  min-width: 0;
  flex: 1 1 auto;
}
.ums-s10__contribution-copy > span {
  display: block;
  margin-bottom: 3px;
  color: #6979A9;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .09em;
}
.ums-s10__contribution h2 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 14.5px;
  font-weight: 700;
  line-height: 1.2;
}
.ums-s10__contribution p {
  margin: 4px 0 0;
  color: #56627C;
  font-size: 10px;
  line-height: 1.38;
}
.ums-s10__contribution p strong {
  color: #303485;
  font-weight: 700;
}

/* 10 — SVG: TECHNICAL ANALYSIS */
.ums-s10__bar {
  transform-box: fill-box;
  transform-origin: bottom center;
}
.ums-s10__analysis-row:not(.slidev-vclick-hidden)
.ums-s10__bar {
  animation: ums-s10-bar-grow .7s ease-out both;
}
.ums-s10__bar--a { animation-delay: .2s; }
.ums-s10__bar--b { animation-delay: .35s; }
.ums-s10__bar--c { animation-delay: .5s; }
@keyframes ums-s10-bar-grow {
  from { opacity: .3; transform: scaleY(.05); }
  to { opacity: 1; transform: scaleY(1); }
}
.ums-s10__graph-trend {
  stroke-dasharray: 50;
  stroke-dashoffset: 50;
}
.ums-s10__analysis-row:not(.slidev-vclick-hidden)
.ums-s10__graph-trend {
  animation: ums-s10-line-draw .8s .4s ease forwards;
}
@keyframes ums-s10-line-draw {
  to { stroke-dashoffset: 0; }
}

/* 11 — SVG: FUNNEL ANALYSIS */
.ums-s10__funnel-trace {
  stroke-dashoffset: 0;
}
.ums-s10__analysis-row:not(.slidev-vclick-hidden)
.ums-s10__funnel-trace {
  animation: ums-s10-funnel-flow 1.2s linear infinite;
}
@keyframes ums-s10-funnel-flow {
  to { stroke-dashoffset: -16; }
}

/* 12 — SVG: RELATIONSHIP ANALYSIS */
.ums-s10__network-lines {
  stroke-dasharray: 85;
  stroke-dashoffset: 85;
}
.ums-s10__analysis-row:not(.slidev-vclick-hidden)
.ums-s10__network-lines {
  animation: ums-s10-line-draw 1.1s .2s ease forwards;
}
.ums-s10__network-node {
  transform-box: fill-box;
  transform-origin: center;
}
.ums-s10__analysis-row:not(.slidev-vclick-hidden)
.ums-s10__network-node {
  animation: ums-s10-node-in .45s ease both;
}
.ums-s10__network-node:nth-of-type(1) { animation-delay: .2s; }
.ums-s10__network-node:nth-of-type(2) { animation-delay: .4s; }
.ums-s10__network-node:nth-of-type(3) { animation-delay: .6s; }
@keyframes ums-s10-node-in {
  from { opacity: .3; transform: scale(.4); }
  to { opacity: 1; transform: scale(1); }
}

/* 13 — SVG: CONTRIBUTION */
.ums-s10__synthesis-node {
  transform-box: fill-box;
  transform-origin: center;
}
.ums-s10__contribution:not(.slidev-vclick-hidden)
.ums-s10__synthesis-node {
  animation: ums-s10-synthesis-in .6s .5s ease both;
}
@keyframes ums-s10-synthesis-in {
  from { opacity: 0; transform: scale(.3); }
  to { opacity: 1; transform: scale(1); }
}

/* 14 — CLICK REVEAL */
.ums-s10__analysis-row,
.ums-s10__merge,
.ums-s10__contribution {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .65s cubic-bezier(.22,1,.36,1),
    transform .65s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s10 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(10px) !important;
  pointer-events: none;
}

/* 15 — ACCESSIBILITY */
@media (prefers-reduced-motion: reduce) {
  .ums-s10 *,
  .ums-s10 *::before,
  .ums-s10 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s10 .slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
  .ums-s10__merge-active,
  .ums-s10__graph-trend,
  .ums-s10__network-lines {
    stroke-dashoffset: 0;
  }
  .ums-s10__merge-arrow {
    opacity: 1;
  }
}
</style>
