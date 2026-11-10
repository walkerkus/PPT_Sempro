---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 9 — ANIMATED MEASUREMENT FRAMEWORK -->
<!-- Canvas: 980 x 552 | Background: /13.jpg -->
<!-- HTML kontigu untuk kompatibilitas Slidev Markdown -->

<div class="ums-s9">
  <header class="ums-s9__header">
    <div class="ums-s9__section">
      <span>08 / INDIKATOR PENELITIAN</span>
    </div>
    <h1 class="ums-s9__title">Bagaimana Kinerja <em>LLM</em> dan Perilaku Pengguna Diukur?</h1>
    <p class="ums-s9__intro">Pengukuran kinerja teknis agen dan tindakan pengguna dilakukan melalui dua eksperimen yang saling melengkapi.</p>
  </header>
  <main class="ums-s9__main">
    <!-- EXPERIMENT I: TECHNICAL METRICS -->
    <section v-click="1" class="ums-s9__technical">
      <div class="ums-s9__column-head">
        <div class="ums-s9__column-number">01</div>
        <div class="ums-s9__column-heading">
          <span>EKSPERIMEN I</span>
          <h2>Kinerja Teknis Agen</h2>
        </div>
        <div class="ums-s9__column-icon">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Evaluasi kinerja teknis">
            <rect x="5" y="6" width="30" height="27" rx="4" fill="#E6EAF7" stroke="#8797C2" stroke-width="1.5"/>
            <path d="M11 26V17M17 26V12M23 26V20M29 26V14" stroke="#303485" stroke-width="3" stroke-linecap="round"/>
            <path d="M12 36H28" stroke="#8797C2" stroke-width="1.5" stroke-linecap="round"/>
          </svg>
        </div>
      </div>
      <div class="ums-s9__metric-list">
        <div class="ums-s9__metric">
          <span class="ums-s9__metric-code">TSR</span>
          <span class="ums-s9__metric-name">Keberhasilan tugas</span>
          <span class="ums-s9__metric-mark">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <circle cx="12" cy="12" r="8" fill="none" stroke="#A4B0CF" stroke-width="1.5"/>
              <path d="M8 12L11 15L16 9" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </span>
        </div>
        <div class="ums-s9__metric">
          <span class="ums-s9__metric-code">HCS</span>
          <span class="ums-s9__metric-name">Pemenuhan syarat wajib</span>
          <span class="ums-s9__metric-mark">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <rect x="5" y="4" width="14" height="16" rx="2" fill="none" stroke="#A4B0CF" stroke-width="1.5"/>
              <path d="M8 10L10 12L13 8M8 16H16" fill="none" stroke="#303485" stroke-width="1.6" stroke-linecap="round"/>
            </svg>
          </span>
        </div>
        <div class="ums-s9__metric">
          <span class="ums-s9__metric-code">PS</span>
          <span class="ums-s9__metric-name">Pemenuhan preferensi</span>
          <span class="ums-s9__metric-mark">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <path d="M12 3L14.8 8.5L21 9.5L16.5 14L17.5 20L12 17L6.5 20L7.5 14L3 9.5L9.2 8.5Z" fill="#E5EAF7" stroke="#8494BF" stroke-width="1.3" stroke-linejoin="round"/>
            </svg>
          </span>
        </div>
        <div class="ums-s9__metric">
          <span class="ums-s9__metric-code">HR</span>
          <span class="ums-s9__metric-name">Tingkat halusinasi</span>
          <span class="ums-s9__metric-mark">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <path d="M12 3L22 20H2Z" fill="#F3F0E5" stroke="#BBA765" stroke-width="1.3" stroke-linejoin="round"/>
              <path d="M12 9V14" stroke="#8D7335" stroke-width="2" stroke-linecap="round"/>
              <circle cx="12" cy="17" r="1" fill="#8D7335"/>
            </svg>
          </span>
        </div>
        <div class="ums-s9__metric">
          <span class="ums-s9__metric-code">TCSR</span>
          <span class="ums-s9__metric-name">Keberhasilan <em>tool call</em></span>
          <span class="ums-s9__metric-mark">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <path d="M9 7L4 12L9 17M15 7L20 12L15 17M14 5L10 19" fill="none" stroke="#7587BA" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </span>
        </div>
        <div class="ums-s9__metric">
          <span class="ums-s9__metric-code">CE</span>
          <span class="ums-s9__metric-name">Efisiensi percakapan</span>
          <span class="ums-s9__metric-mark">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <circle cx="12" cy="12" r="9" fill="none" stroke="#A4B0CF" stroke-width="1.4"/>
              <path d="M12 7V12L16 14" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round"/>
            </svg>
          </span>
        </div>
        <div class="ums-s9__metric">
          <span class="ums-s9__metric-code">Reliability</span>
          <span class="ums-s9__metric-name">Konsistensi hasil</span>
          <span class="ums-s9__metric-mark">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <path d="M3 12H6L9 7L13 17L16 11H21" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M3 19H21" stroke="#D5DBEA" stroke-width="1.2" stroke-linecap="round"/>
            </svg>
          </span>
        </div>
      </div>
      <div class="ums-s9__technical-note">
        <span class="ums-s9__note-dot"></span>
        <span>Penilaian menggunakan acuan dan pengujian berulang.</span>
      </div>
    </section>
    <!-- EXPERIMENT II: PURCHASE FUNNEL -->
    <section v-click="2" class="ums-s9__funnel">
      <div class="ums-s9__column-head">
        <div class="ums-s9__column-number">02</div>
        <div class="ums-s9__column-heading">
          <span>EKSPERIMEN II</span>
          <h2><em>Purchase Funnel</em></h2>
        </div>
        <div class="ums-s9__column-icon">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Tahapan purchase funnel">
            <path d="M5 7H35L27 17H13Z" fill="#DCE3F4" stroke="#8191C0" stroke-width="1.2"/>
            <path d="M13 20H27L24 27H16Z" fill="#9EADD3"/>
            <path d="M16 30H24L22 36H18Z" fill="#303485"/>
          </svg>
        </div>
      </div>
      <div class="ums-s9__funnel-visual">
        <div class="ums-s9__funnel-axis">
          <span>TAHAP PERILAKU BELANJA</span>
          <span>ALUR KONSEPTUAL</span>
        </div>
        <div class="ums-s9__funnel-steps">
          <div class="ums-s9__funnel-step">
            <span class="ums-s9__step-index">01</span>
            <div class="ums-s9__step-bar">
              <span>Recommendation Click</span>
              <svg viewBox="0 0 20 20" aria-hidden="true">
                <path d="M5 3L15 10L10 11L8 16Z" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
          <div class="ums-s9__funnel-step">
            <span class="ums-s9__step-index">02</span>
            <div class="ums-s9__step-bar">
              <span>Product Selection</span>
              <svg viewBox="0 0 20 20" aria-hidden="true">
                <rect x="4" y="3" width="12" height="14" rx="2" fill="none" stroke="currentColor" stroke-width="1.4"/>
                <path d="M7 8H13M7 12H11" stroke="currentColor" stroke-width="1.4" stroke-linecap="round"/>
              </svg>
            </div>
          </div>
          <div class="ums-s9__funnel-step ums-s9__funnel-step--key">
            <span class="ums-s9__step-index">03</span>
            <div class="ums-s9__step-bar">
              <span>Add-to-Cart</span>
              <svg viewBox="0 0 20 20" aria-hidden="true">
                <path d="M2 4H5L8 13H16L18 7H6M9 16H10M15 16H16" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
            <span class="ums-s9__key-marker">ATCR</span>
          </div>
          <div class="ums-s9__funnel-step">
            <span class="ums-s9__step-index">04</span>
            <div class="ums-s9__step-bar">
              <span>Checkout Initiation</span>
              <svg viewBox="0 0 20 20" aria-hidden="true">
                <rect x="3" y="5" width="14" height="11" rx="2" fill="none" stroke="currentColor" stroke-width="1.4"/>
                <path d="M3 9H17" stroke="currentColor" stroke-width="1.4"/>
              </svg>
            </div>
          </div>
          <div class="ums-s9__funnel-step">
            <span class="ums-s9__step-index">05</span>
            <div class="ums-s9__step-bar">
              <span>Simulated Order</span>
              <svg viewBox="0 0 20 20" aria-hidden="true">
                <circle cx="10" cy="10" r="7" fill="none" stroke="currentColor" stroke-width="1.4"/>
                <path d="M6 10L9 13L14 7" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
        </div>
        <div class="ums-s9__funnel-explanation">
          <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <circle cx="12" cy="12" r="9" fill="none" stroke="#8998BE" stroke-width="1.5"/>
            <path d="M12 11V16M12 7V8" stroke="#303485" stroke-width="2" stroke-linecap="round"/>
          </svg>
          <p>Menunjukkan jenis tindakan yang diamati, bukan jumlah atau persentase peserta.</p>
        </div>
      </div>
    </section>
  </main>
  <!-- PRIMARY METRIC FORMULA -->
  <section v-click="3" class="ums-s9__formula">
    <div class="ums-s9__formula-info">
      <span>INDIKATOR UTAMA EKSPERIMEN II</span>
      <h2><em>Add-to-Cart Rate</em> <strong>(ATCR)</strong></h2>
      <p>Proporsi peserta yang menambahkan produk ke keranjang.</p>
    </div>
    <div class="ums-s9__equation">
      <span class="ums-s9__equation-name">ATCR =</span>
      <div class="ums-s9__fraction">
        <span>Jumlah peserta yang <em>Add-to-Cart</em></span>
        <span>Total peserta yang dianalisis</span>
      </div>
      <span class="ums-s9__equation-times">× 100%</span>
    </div>
  </section>
</div>

<style scoped>
/* ============================================
   SLIDE 9 — ANIMATED MEASUREMENT FRAMEWORK
   Canvas: 980 × 552
   Background: Official UMS /13.jpg
   ============================================ */

/* 01 — CANVAS */
.ums-s9 {
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
.ums-s9,
.ums-s9 * {
  box-sizing: border-box;
}

/* 02 — HEADER */
.ums-s9__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 55px;
}
.ums-s9__section {
  display: flex;
  align-items: center;
  margin-bottom: 8px;
  color: #303485;
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .11em;
}
.ums-s9__title {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 27px;
  font-weight: 720;
  line-height: 1.18;
  letter-spacing: -.032em;
}
.ums-s9__title em {
  font-style: italic;
  font-weight: 500;
}
.ums-s9__intro {
  margin: 7px 0 0;
  color: #68728C;
  font-size: 11.5px;
  line-height: 1.45;
}

/* 03 — MAIN GRID */
.ums-s9__main {
  position: absolute;
  top: 168px;
  left: 70px;
  right: 70px;
  height: 236px;
  display: grid;
  grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
  column-gap: 28px;
  align-items: start;
}
.ums-s9__technical,
.ums-s9__funnel {
  min-width: 0;
  height: 236px;
  display: flex;
  flex-direction: column;
  padding: 8px 14px 10px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}

/* 04 — COLUMN HEADINGS */
.ums-s9__column-head {
  display: flex;
  align-items: center;
  gap: 12px;
  height: 36px;
  padding: 0 0 5px;
  border-bottom: 2px solid #303485;
}
.ums-s9__column-number {
  flex: 0 0 auto;
  font-size: 24px;
  font-weight: 400;
  line-height: 1;
  letter-spacing: -.05em;
  color: #929DC0;
}
.ums-s9__column-heading {
  min-width: 0;
  flex: 1 1 auto;
}
.ums-s9__column-heading > span {
  display: block;
  margin-bottom: 3px;
  color: #8390AD;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .09em;
}
.ums-s9__column-heading h2 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 15px;
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: -.015em;
}
.ums-s9__column-heading h2 em {
  font-style: italic;
  font-weight: 550;
}
.ums-s9__column-icon {
  width: 34px;
  height: 34px;
  flex: 0 0 34px;
}
.ums-s9__column-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}

/* 05 — TECHNICAL METRICS */
.ums-s9__metric-list {
  margin-top: 4px;
}
.ums-s9__metric {
  display: grid;
  grid-template-columns: 78px minmax(0,1fr) 23px;
  align-items: center;
  gap: 10px;
  height: 22px;
  border-bottom: 1px solid #E4E8F0;
}
.ums-s9__metric-code {
  color: #303485;
  font-size: 10px;
  font-weight: 750;
  letter-spacing: -.01em;
}
.ums-s9__metric-name {
  min-width: 0;
  color: #535F7A;
  font-size: 9.5px;
  font-weight: 500;
  line-height: 1.25;
}
.ums-s9__metric-name em {
  font-style: italic;
}
.ums-s9__metric-mark {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 19px;
  height: 19px;
}
.ums-s9__metric-mark svg {
  display: block;
  width: 19px;
  height: 19px;
}

/* Staggered metric reveal */
.ums-s9__technical:not(.slidev-vclick-hidden)
.ums-s9__metric {
  animation: ums-s9-metric-in .45s ease both;
}
.ums-s9__metric:nth-child(1) { animation-delay: .10s; }
.ums-s9__metric:nth-child(2) { animation-delay: .20s; }
.ums-s9__metric:nth-child(3) { animation-delay: .30s; }
.ums-s9__metric:nth-child(4) { animation-delay: .40s; }
.ums-s9__metric:nth-child(5) { animation-delay: .50s; }
.ums-s9__metric:nth-child(6) { animation-delay: .60s; }
.ums-s9__metric:nth-child(7) { animation-delay: .70s; }
@keyframes ums-s9-metric-in {
  from {
    opacity: 0;
    transform: translateX(-10px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}
.ums-s9__technical-note {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-top: auto;
  padding-top: 4px;
  color: #7E89A2;
  font-size: 8px;
  line-height: 1.3;
}
.ums-s9__note-dot {
  width: 5px;
  height: 5px;
  flex: 0 0 5px;
  border-radius: 50%;
  background: #8796BD;
}

/* 06 — FUNNEL AXIS */
.ums-s9__funnel-visual {
  margin-top: 7px;
}
.ums-s9__funnel-axis {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 10px;
  margin-bottom: 6px;
  color: #8995AD;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .07em;
}

/* 07 — FUNNEL STAGES */
.ums-s9__funnel-steps {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: stretch;
  gap: 3px;
}
.ums-s9__funnel-steps::before {
  content: "";
  position: absolute;
  top: 11px;
  bottom: 11px;
  left: 12px;
  width: 1px;
  background: #CBD4E7;
}
.ums-s9__funnel-step {
  position: relative;
  display: grid;
  grid-template-columns: 25px minmax(0,1fr);
  align-items: center;
  gap: 7px;
  height: 25px;
}
.ums-s9__step-index {
  position: relative;
  z-index: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 22px;
  height: 22px;
  border: 1px solid #C8D1E7;
  border-radius: 50%;
  background: #F7F8FC;
  color: #6576AA;
  font-size: 8px;
  font-weight: 700;
}
.ums-s9__step-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 10px;
  height: 25px;
  min-width: 0;
  padding: 0 9px;
  background: #EDF0F8;
  border: 1px solid #DDE3F0;
  color: #46557D;
  font-size: 9.5px;
  font-weight: 600;
}
.ums-s9__step-bar svg {
  display: block;
  width: 16px;
  height: 16px;
  flex: 0 0 16px;
  color: #7585B6;
}
.ums-s9__funnel-step:nth-child(2) .ums-s9__step-bar {
  background: #E6EBF6;
}
.ums-s9__funnel-step:nth-child(4) .ums-s9__step-bar {
  background: #E1E7F4;
}
.ums-s9__funnel-step:nth-child(5) .ums-s9__step-bar {
  background: #D9E1F1;
}
.ums-s9__funnel-step--key {
  grid-template-columns: 25px minmax(0,1fr) 39px;
}
.ums-s9__funnel-step--key .ums-s9__step-index {
  color: #FFFFFF;
  background: #303485;
  border-color: #303485;
}
.ums-s9__funnel-step--key .ums-s9__step-bar {
  color: #242867;
  background: #CDD7EF;
  border-color: #8B9CCB;
  font-weight: 750;
}
.ums-s9__key-marker {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 22px;
  color: #303485;
  font-size: 8px;
  font-weight: 750;
  letter-spacing: .03em;
}

/* Sequential funnel reveal */
.ums-s9__funnel:not(.slidev-vclick-hidden)
.ums-s9__funnel-step {
  animation: ums-s9-funnel-in .55s ease both;
}
.ums-s9__funnel-step:nth-child(1) { animation-delay: .12s; }
.ums-s9__funnel-step:nth-child(2) { animation-delay: .28s; }
.ums-s9__funnel-step:nth-child(3) { animation-delay: .44s; }
.ums-s9__funnel-step:nth-child(4) { animation-delay: .60s; }
.ums-s9__funnel-step:nth-child(5) { animation-delay: .76s; }
@keyframes ums-s9-funnel-in {
  from {
    opacity: 0;
    transform: translateY(-7px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
.ums-s9__funnel-explanation {
  display: flex;
  align-items: flex-start;
  gap: 6px;
  margin-top: auto;
  padding-top: 4px;
}
.ums-s9__funnel-explanation svg {
  width: 13px;
  height: 13px;
  flex: 0 0 13px;
}
.ums-s9__funnel-explanation p {
  margin: 0;
  font-size: 8px;
  line-height: 1.3;
  color: #7C88A1;
}

/* 08 — PRIMARY ATCR FORMULA */
.ums-s9__formula {
  position: absolute;
  top: 418px;
  left: 70px;
  right: 70px;
  height: 52px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  padding: 6px 16px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  border-radius: 0px;
}
.ums-s9__formula-info {
  min-width: 0;
  flex: 1 1 auto;
}
.ums-s9__formula-info > span {
  display: block;
  margin-bottom: 3px;
  color: #6475AA;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .085em;
}
.ums-s9__formula-info h2 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 13.5px;
  font-weight: 700;
  line-height: 1.2;
}
.ums-s9__formula-info h2 em {
  font-style: italic;
  font-weight: 550;
}
.ums-s9__formula-info h2 strong {
  font-weight: 750;
}
.ums-s9__formula-info p {
  margin: 2px 0 0;
  color: #6E7B95;
  font-size: 9px;
  line-height: 1.25;
}

/* 09 — EQUATION */
.ums-s9__equation {
  display: flex;
  align-items: center;
  gap: 10px;
  flex: 0 0 auto;
  color: #242867;
  white-space: nowrap;
}
.ums-s9__equation-name {
  font-size: 14px;
  font-weight: 750;
}
.ums-s9__fraction {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-width: 210px;
  font-size: 9.5px;
  line-height: 1.2;
}
.ums-s9__fraction > span:first-child {
  display: block;
  width: 100%;
  padding: 0 4px 4px;
  border-bottom: 1.5px solid #303485;
  text-align: center;
}
.ums-s9__fraction > span:last-child {
  display: block;
  padding-top: 4px;
  text-align: center;
}
.ums-s9__fraction em {
  font-style: italic;
}
.ums-s9__equation-times {
  font-size: 14px;
  font-weight: 700;
}
.ums-s9__formula:not(.slidev-vclick-hidden)
.ums-s9__fraction {
  animation: ums-s9-formula-in .65s .2s ease both;
}
@keyframes ums-s9-formula-in {
  from {
    opacity: 0;
    transform: translateY(6px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* 10 — SLIDEV CLICK REVEAL */
.ums-s9__technical,
.ums-s9__funnel,
.ums-s9__formula {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .65s cubic-bezier(.22,1,.36,1),
    transform .65s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s9 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(12px) !important;
  pointer-events: none;
}

/* 11 — REDUCED MOTION */
@media (prefers-reduced-motion: reduce) {
  .ums-s9 *,
  .ums-s9 *::before,
  .ums-s9 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s9 .slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
}
</style>
