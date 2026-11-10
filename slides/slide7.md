---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 7 — CONTROLLED AGENT BENCHMARK -->
<!-- Canvas: 980 x 552 | Background: /13.jpg -->
<!-- HTML kontigu untuk kompatibilitas Slidev Markdown -->

<div class="ums-s7">
  <header class="ums-s7__header">
    <div class="ums-s7__section">
      <span>06 / EKSPERIMEN I</span>
      <span class="ums-s7__section-divider">/</span>
      <span>CONTROLLED AGENT BENCHMARK</span>
    </div>
    <h1 class="ums-s7__title">Pengujian Kinerja Teknis <em>LLM</em></h1>
    <p class="ums-s7__intro">Saya akan menguji kemampuan teknis beberapa LLM menggunakan skenario belanja yang sama.</p>
  </header>
  <main class="ums-s7__diagram">
    <!-- STEP 01 — BENCHMARK SCENARIO -->
    <section v-click="1" class="ums-s7__scenario">
      <div class="ums-s7__scenario-icon">
        <svg viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Instruksi skenario belanja">
          <rect x="7" y="5" width="34" height="38" rx="5" fill="#FFFFFF" stroke="#8493BD" stroke-width="1.5"/>
          <path d="M15 15H33M15 21H27M15 28H24" stroke="#8290B9" stroke-width="2" stroke-linecap="round"/>
          <circle cx="32" cy="31" r="8" fill="#303485"/>
          <path d="M29 31L31 33L35 29" stroke="#FFFFFF" stroke-width="1.8" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
          <path class="ums-s7__check-draw" d="M29 31L31 33L35 29" stroke="#E7BD4D" stroke-width="1.8" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <div class="ums-s7__scenario-copy">
        <div class="ums-s7__scenario-heading">
          <span>01 / SKENARIO PENGUJIAN</span>
          <span class="ums-s7__scenario-note">CONTOH ILUSTRATIF</span>
        </div>
        <p>“Carikan laptop untuk kuliah dengan harga maksimal Rp8 juta dan RAM minimal 16 GB.”</p>
        <div class="ums-s7__requirements">
          <span><b>ANGGARAN</b> ≤ Rp8 juta</span>
          <span><b>MEMORI</b> ≥ 16 GB RAM</span>
          <span><b>KEBUTUHAN</b> Kuliah</span>
        </div>
      </div>
    </section>
    <!-- STEP 02 — SCENARIO DISTRIBUTION -->
    <div v-click="2" class="ums-s7__distribution">
      <svg viewBox="0 0 840 25" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path class="ums-s7__distribution-track" d="M420 0V9H140V24M420 9V24M420 9H700V24"/>
        <path class="ums-s7__distribution-active" d="M420 0V9H140V24M420 9V24M420 9H700V24"/>
        <circle cx="140" cy="24" r="2.5" fill="#303485"/>
        <circle cx="420" cy="24" r="2.5" fill="#303485"/>
        <circle cx="700" cy="24" r="2.5" fill="#303485"/>
      </svg>
    </div>
    <!-- STEP 02 — THREE MODELS -->
    <section v-click="2" class="ums-s7__models">
      <div class="ums-s7__model">
        <div class="ums-s7__model-heading">
          <span class="ums-s7__model-name">MODEL A</span>
          <span class="ums-s7__model-index">01</span>
        </div>
        <div class="ums-s7__model-process">
          <svg viewBox="0 0 100 25" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <rect x="1" y="4" width="24" height="17" rx="3" fill="#E3E8F5" stroke="#A3B0D0"/>
            <path d="M7 10H19M7 15H16" stroke="#6274A9" stroke-width="2" stroke-linecap="round"/>
            <path class="ums-s7__process-line" d="M31 12H69" stroke="#303485" stroke-width="2" stroke-dasharray="4 4"/>
            <rect x="75" y="4" width="24" height="17" rx="3" fill="#EEF1F9" stroke="#A3B0D0"/>
            <path d="M81 12L86 16L94 8" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span class="ums-s7__process-label">PROSES TUGAS</span>
        </div>
        <p>Menjalankan skenario dengan konfigurasi yang setara.</p>
      </div>
      <div class="ums-s7__model">
        <div class="ums-s7__model-heading">
          <span class="ums-s7__model-name">MODEL B</span>
          <span class="ums-s7__model-index">02</span>
        </div>
        <div class="ums-s7__model-process">
          <svg viewBox="0 0 100 25" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <rect x="1" y="4" width="24" height="17" rx="3" fill="#E3E8F5" stroke="#A3B0D0"/>
            <path d="M7 10H19M7 15H16" stroke="#6274A9" stroke-width="2" stroke-linecap="round"/>
            <path class="ums-s7__process-line" d="M31 12H69" stroke="#303485" stroke-width="2" stroke-dasharray="4 4"/>
            <rect x="75" y="4" width="24" height="17" rx="3" fill="#EEF1F9" stroke="#A3B0D0"/>
            <path d="M81 12L86 16L94 8" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span class="ums-s7__process-label">PROSES TUGAS</span>
        </div>
        <p>Menjalankan skenario dengan konfigurasi yang setara.</p>
      </div>
      <div class="ums-s7__model">
        <div class="ums-s7__model-heading">
          <span class="ums-s7__model-name">MODEL C</span>
          <span class="ums-s7__model-index">03</span>
        </div>
        <div class="ums-s7__model-process">
          <svg viewBox="0 0 100 25" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <rect x="1" y="4" width="24" height="17" rx="3" fill="#E3E8F5" stroke="#A3B0D0"/>
            <path d="M7 10H19M7 15H16" stroke="#6274A9" stroke-width="2" stroke-linecap="round"/>
            <path class="ums-s7__process-line" d="M31 12H69" stroke="#303485" stroke-width="2" stroke-dasharray="4 4"/>
            <rect x="75" y="4" width="24" height="17" rx="3" fill="#EEF1F9" stroke="#A3B0D0"/>
            <path d="M81 12L86 16L94 8" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span class="ums-s7__process-label">PROSES TUGAS</span>
        </div>
        <p>Menjalankan skenario dengan konfigurasi yang setara.</p>
      </div>
    </section>
    <!-- STEP 03 — EVALUATION CONNECTION -->
    <div v-click="3" class="ums-s7__merge">
      <svg viewBox="0 0 840 19" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path class="ums-s7__merge-track" d="M140 0V7H420M700 0V7H420V18M420 0V7"/>
        <path class="ums-s7__merge-active" d="M140 0V7H420M700 0V7H420V18M420 0V7"/>
        <path d="M415 13L420 18L425 13" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </div>
    <!-- STEP 03 — GROUND TRUTH EVALUATION -->
    <section v-click="3" class="ums-s7__evaluation">
      <div class="ums-s7__evaluation-heading">
        <div>
          <span>02 / EVALUASI HASIL</span>
          <h2>Penilaian terhadap <em>Ground Truth</em></h2>
        </div>
        <span class="ums-s7__evaluation-note">ACUAN YANG SAMA</span>
      </div>
      <div class="ums-s7__criteria">
        <div class="ums-s7__criterion">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Kesesuaian syarat">
            <rect x="7" y="5" width="26" height="30" rx="4" fill="#E7EBF8" stroke="#8B9AC5" stroke-width="1.4"/>
            <path d="M13 14L16 17L21 11M13 26L16 29L21 23M24 15H29M24 27H29" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span>Kesesuaian syarat</span>
        </div>
        <div class="ums-s7__criterion">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Kebenaran informasi">
            <circle cx="18" cy="18" r="11" fill="#E7EBF8" stroke="#8B9AC5" stroke-width="1.4"/>
            <path d="M26 26L35 35" stroke="#303485" stroke-width="3" stroke-linecap="round"/>
            <path d="M13 18L17 22L24 14" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span>Kebenaran informasi</span>
        </div>
        <div class="ums-s7__criterion">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Penggunaan tools">
            <rect x="7" y="8" width="26" height="24" rx="4" fill="#E7EBF8" stroke="#8B9AC5" stroke-width="1.4"/>
            <path d="M15 16L11 20L15 24M25 16L29 20L25 24M23 14L17 26" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span>Penggunaan <em>tools</em></span>
        </div>
        <div class="ums-s7__criterion">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Penyelesaian tugas">
            <circle cx="20" cy="20" r="14" fill="#E7EBF8" stroke="#8B9AC5" stroke-width="1.4"/>
            <circle cx="20" cy="20" r="8" fill="none" stroke="#8B9AC5" stroke-width="1.4"/>
            <path d="M15 20L19 24L27 15" fill="none" stroke="#303485" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span>Penyelesaian tugas</span>
        </div>
      </div>
    </section>
    <!-- STEP 04 — COMPARISON OUTPUT -->
    <section v-click="4" class="ums-s7__result">
      <div class="ums-s7__result-left">
        <div class="ums-s7__result-icon">
          <svg viewBox="0 0 46 46" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Hasil perbandingan kinerja">
            <path d="M7 7V38H41" fill="none" stroke="#97A5CB" stroke-width="1.5" stroke-linecap="round"/>
            <rect class="ums-s7__result-bar bar-a" x="13" y="20" width="7" height="18" rx="1.5" fill="#8999C9"/>
            <rect class="ums-s7__result-bar bar-b" x="24" y="13" width="7" height="25" rx="1.5" fill="#303485"/>
            <rect class="ums-s7__result-bar bar-c" x="35" y="24" width="5" height="14" rx="1.5" fill="#B1BBDD"/>
          </svg>
        </div>
        <div class="ums-s7__result-copy">
          <span>03 / OUTPUT PENELITIAN</span>
          <h2>Perbandingan Kinerja Teknis LLM</h2>
        </div>
      </div>
      <div class="ums-s7__result-right">
        <strong>Pengujian berulang</strong>
        <p>Untuk menilai konsistensi hasil pada setiap model.</p>
      </div>
    </section>
    <!-- METHODOLOGICAL CONTROL NOTE -->
    <div v-click="5" class="ums-s7__control">
      <span>PRINSIP KONTROL</span>
      <p>Skenario, katalog, instruksi, dan akses <em>tools</em> disetarakan; hasil dinilai menggunakan acuan yang ditetapkan sebelum pengujian.</p>
    </div>
  </main>
</div>

<style scoped>
/* ===============================================
   SLIDE 7 — ANIMATED BENCHMARK PIPELINE
   Canvas: 980 x 552
   Background: /13.jpg
   =============================================== */

/* 01 — CANVAS */
.ums-s7 {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  overflow: hidden;
  isolation: isolate;
  background: #fff url('/13.jpg') center / cover no-repeat;
  font-family: 'Inter', 'Aptos', Arial, sans-serif;
  color: #242867;
  -webkit-font-smoothing: antialiased;
}
.ums-s7,
.ums-s7 * {
  box-sizing: border-box;
}

/* 02 — HEADER */
.ums-s7__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 55px;
}
.ums-s7__section {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 10px;
  color: #303485;
  font-size: 9px;
  font-weight: 700;
  letter-spacing: .1em;
}
.ums-s7__section-divider {
  color: #ABB4CC;
  font-weight: 400;
}
.ums-s7__title {
  margin: 0;
  padding: 0;
  font-size: 27px;
  font-weight: 720;
  line-height: 1.16;
  letter-spacing: -.032em;
  color: #242867;
}
.ums-s7__title em {
  font-style: italic;
  font-weight: 500;
}
.ums-s7__intro {
  margin: 7px 0 0;
  color: #68728C;
  font-size: 11px;
  line-height: 1.45;
}

/* 03 — DIAGRAM LAYOUT */
.ums-s7__diagram {
  position: absolute;
  top: 178px;
  left: 70px;
  right: 70px;
  bottom: 84px;
}

/* 04 — SCENARIO */
.ums-s7__scenario {
  display: flex;
  align-items: center;
  gap: 13px;
  width: 100%;
  height: 68px;
  padding: 8px 14px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s7__scenario-icon {
  width: 46px;
  height: 46px;
  flex: 0 0 46px;
}
.ums-s7__scenario-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s7__scenario-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s7__scenario-heading {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
}
.ums-s7__scenario-heading span:first-child {
  color: #303485;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .095em;
}
.ums-s7__scenario-note {
  color: #8893AC;
  font-size: 7.5px;
  font-weight: 600;
  letter-spacing: .065em;
}
.ums-s7__scenario p {
  margin: 5px 0;
  font-size: 13px;
  font-weight: 600;
  line-height: 1.3;
  color: #242867;
}
.ums-s7__requirements {
  display: flex;
  align-items: center;
  gap: 15px;
}
.ums-s7__requirements span {
  color: #596784;
  font-size: 9px;
  line-height: 1.2;
}
.ums-s7__requirements b {
  margin-right: 4px;
  color: #7D89A4;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .045em;
}

/* 05 — DISTRIBUTION SVG */
.ums-s7__distribution {
  height: 25px;
}
.ums-s7__distribution svg {
  display: block;
  width: 100%;
  height: 25px;
  overflow: visible;
}
.ums-s7__distribution-track {
  fill: none;
  stroke: #D3DAE9;
  stroke-width: 1.4;
}
.ums-s7__distribution-active {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-linejoin: round;
  stroke-linecap: round;
  stroke-dasharray: 900;
  stroke-dashoffset: 900;
}
.ums-s7__distribution:not(.slidev-vclick-hidden)
.ums-s7__distribution-active {
  animation: ums-s7-draw .95s ease forwards;
}
@keyframes ums-s7-draw {
  to { stroke-dashoffset: 0; }
}

/* 06 — MODEL PROCESSING */
.ums-s7__models {
  display: grid;
  grid-template-columns: repeat(3, minmax(0,1fr));
  gap: 12px;
  height: 83px;
}
.ums-s7__model {
  min-width: 0;
  height: 83px;
  padding: 9px 12px;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  background: #FFFFFF;
}
.ums-s7__model-heading {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.ums-s7__model-name {
  color: #303485;
  font-size: 10px;
  font-weight: 750;
  letter-spacing: .065em;
}
.ums-s7__model-index {
  color: #AFB8CB;
  font-size: 9px;
  font-weight: 600;
}
.ums-s7__model-process {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-top: 4px;
}
.ums-s7__model-process svg {
  width: 100px;
  height: 25px;
  flex: 0 0 100px;
}
.ums-s7__process-label {
  color: #7E8AA5;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .045em;
}
.ums-s7__model p {
  margin: 4px 0 0;
  color: #69758E;
  font-size: 9px;
  line-height: 1.3;
}
.ums-s7__process-line {
  animation: ums-s7-process 1.5s linear infinite;
}
.ums-s7__model:nth-child(2)
.ums-s7__process-line {
  animation-delay: -.5s;
}
.ums-s7__model:nth-child(3)
.ums-s7__process-line {
  animation-delay: -1s;
}
@keyframes ums-s7-process {
  to { stroke-dashoffset: -16; }
}

/* 07 — MERGE */
.ums-s7__merge {
  height: 19px;
}
.ums-s7__merge svg {
  display: block;
  width: 100%;
  height: 19px;
  overflow: visible;
}
.ums-s7__merge-track {
  fill: none;
  stroke: #D3DAE9;
  stroke-width: 1.4;
}
.ums-s7__merge-active {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 900;
  stroke-dashoffset: 900;
}
.ums-s7__merge:not(.slidev-vclick-hidden)
.ums-s7__merge-active {
  animation: ums-s7-draw 1s ease forwards;
}

/* 08 — EVALUATION */
.ums-s7__evaluation {
  height: 74px;
  padding: 7px 14px 8px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s7__evaluation-heading {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.ums-s7__evaluation-heading > div > span {
  display: block;
  color: #7280A3;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .085em;
}
.ums-s7__evaluation h2 {
  margin: 2px 0 0;
  padding: 0;
  color: #242867;
  font-size: 13px;
  font-weight: 700;
  line-height: 1.2;
}
.ums-s7__evaluation h2 em {
  font-style: italic;
  font-weight: 550;
}
.ums-s7__evaluation-note {
  color: #8C98B0;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .065em;
}
.ums-s7__criteria {
  display: grid;
  grid-template-columns: repeat(4,minmax(0,1fr));
  gap: 7px;
  margin-top: 7px;
}
.ums-s7__criterion {
  display: flex;
  align-items: center;
  gap: 7px;
  min-width: 0;
}
.ums-s7__criterion svg {
  width: 29px;
  height: 29px;
  flex: 0 0 29px;
}
.ums-s7__criterion span {
  color: #56617C;
  font-size: 10px;
  font-weight: 600;
  line-height: 1.25;
}
.ums-s7__criterion em {
  font-style: italic;
}

/* 09 — RESULT */
.ums-s7__result {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 44px;
  gap: 15px;
  margin-top: 7px;
  padding: 5px 12px;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  background: #FFFFFF;
}
.ums-s7__result-left {
  display: flex;
  align-items: center;
  gap: 10px;
  min-width: 0;
}
.ums-s7__result-icon {
  flex: 0 0 37px;
  width: 37px;
  height: 37px;
}
.ums-s7__result-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s7__result-copy > span {
  display: block;
  color: #6676AA;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .07em;
}
.ums-s7__result h2 {
  margin: 3px 0 0;
  padding: 0;
  font-size: 13px;
  font-weight: 700;
  line-height: 1.2;
  color: #242867;
}
.ums-s7__result-right {
  max-width: 270px;
  text-align: right;
}
.ums-s7__result-right strong {
  display: block;
  color: #303485;
  font-size: 10px;
  font-weight: 700;
}
.ums-s7__result-right p {
  margin: 2px 0 0;
  color: #65718A;
  font-size: 9px;
  line-height: 1.25;
}
.ums-s7__result-bar {
  transform-box: fill-box;
  transform-origin: bottom center;
}
.ums-s7__result:not(.slidev-vclick-hidden)
.ums-s7__result-bar {
  animation: ums-s7-bars .8s ease-out both;
}
.ums-s7__result-bar.bar-b {
  animation-delay: .15s;
}
.ums-s7__result-bar.bar-c {
  animation-delay: .3s;
}
@keyframes ums-s7-bars {
  from { transform: scaleY(.05); opacity: .3; }
  to { transform: scaleY(1); opacity: 1; }
}

/* 10 — METHODOLOGICAL PRINCIPLE */
.ums-s7__control {
  display: flex;
  align-items: flex-start;
  gap: 13px;
  margin-top: 7px;
}
.ums-s7__control > span {
  flex: 0 0 105px;
  color: #303485;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .07em;
}
.ums-s7__control p {
  margin: 0;
  color: #65718B;
  font-size: 9px;
  line-height: 1.4;
}
.ums-s7__control em {
  font-style: italic;
}

/* 11 — CHECK MARK */
.ums-s7__check-draw {
  stroke-dasharray: 15;
  stroke-dashoffset: 15;
}
.ums-s7__scenario:not(.slidev-vclick-hidden)
.ums-s7__check-draw {
  animation: ums-s7-check .65s .55s ease forwards;
}
@keyframes ums-s7-check {
  to { stroke-dashoffset: 0; }
}

/* 12 — CLICK REVEAL */
.ums-s7__scenario,
.ums-s7__distribution,
.ums-s7__models,
.ums-s7__merge,
.ums-s7__evaluation,
.ums-s7__result,
.ums-s7__control {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .6s cubic-bezier(.22,1,.36,1),
    transform .6s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s7 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(10px) !important;
  pointer-events: none;
}

/* 13 — REDUCED MOTION */
@media (prefers-reduced-motion: reduce) {
  .ums-s7 *,
  .ums-s7 *::before,
  .ums-s7 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s7 .slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
  .ums-s7__distribution-active,
  .ums-s7__merge-active,
  .ums-s7__check-draw {
    stroke-dashoffset: 0;
  }
}
</style>
