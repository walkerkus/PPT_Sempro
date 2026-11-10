---
layout: default
transition: fade
class: ums-background-slide
---

<!--
SLIDE 5 — DESAIN PENELITIAN
Canvas: 980 x 552
Background: /13.jpg
HTML kontigu untuk kompatibilitas Slidev Markdown
-->

<div class="ums-s5">
  <header class="ums-s5__header">
    <div class="ums-s5__section">
      <span>04 / METODOLOGI PENELITIAN</span>
    </div>
    <h1 class="ums-s5__title">Desain Penelitian Kuantitatif Komparatif</h1>
    <p class="ums-s5__intro">Dua eksperimen untuk membandingkan kinerja teknis agen serta perilaku dan pengalaman pengguna.</p>
  </header>
  <main class="ums-s5__diagram">
    <!-- STEP 01: COMMON LLM ENVIRONMENT -->
    <section v-click class="ums-s5__source">
      <div class="ums-s5__source-icon">
        <svg viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Tiga model bahasa dalam lingkungan yang sama">
          <rect x="4" y="11" width="12" height="24" rx="3" fill="#DCE3F5" stroke="#7B8BBB" stroke-width="1.3"/>
          <rect x="18" y="6" width="12" height="29" rx="3" fill="#303485"/>
          <rect x="32" y="11" width="12" height="24" rx="3" fill="#DCE3F5" stroke="#7B8BBB" stroke-width="1.3"/>
          <path d="M10 17V25M24 12V25M38 17V25" stroke="#FFFFFF" stroke-width="1.8" stroke-linecap="round" opacity=".8"/>
          <path d="M10 35V41H38V35M24 35V41" fill="none" stroke="#7B8BBB" stroke-width="1.5"/>
          <circle cx="24" cy="41" r="2.5" fill="#D5A126"/>
        </svg>
      </div>
      <div class="ums-s5__source-copy">
        <span class="ums-s5__eyebrow">LINGKUNGAN PENGUJIAN</span>
        <h2>Perbandingan beberapa <em>LLM</em></h2>
        <p>Komponen sistem dan kondisi pengujian dibuat setara.</p>
      </div>
      <div class="ums-s5__model-group">
        <span>MODEL A</span>
        <span>MODEL B</span>
        <span>MODEL C</span>
      </div>
    </section>
    <!-- STEP 02: ANIMATED SPLIT CONNECTION -->
    <div v-click class="ums-s5__split">
      <svg viewBox="0 0 820 30" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path class="ums-s5__split-base" d="M410 0V11H205V29M410 11H615V29"/>
        <path class="ums-s5__split-active" d="M410 0V11H205V29M410 11H615V29"/>
        <circle cx="410" cy="11" r="3.5" fill="#303485"/>
        <circle cx="205" cy="28" r="3" fill="#D5A126"/>
        <circle cx="615" cy="28" r="3" fill="#D5A126"/>
      </svg>
    </div>
    <!-- STEP 03: TWO EXPERIMENTS -->
    <div class="ums-s5__experiments">
      <!-- EXPERIMENT I -->
      <section v-click class="ums-s5__experiment ums-s5__experiment--technical">
        <div class="ums-s5__experiment-top">
          <span class="ums-s5__experiment-id">EKSPERIMEN 01</span>
          <span class="ums-s5__experiment-category">EVALUASI SISTEM</span>
        </div>
        <div class="ums-s5__experiment-body">
          <div class="ums-s5__experiment-icon">
            <svg viewBox="0 0 82 76" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ilustrasi pengukuran kinerja teknis agen">
              <rect x="8" y="9" width="66" height="48" rx="5" fill="#F1F3FA" stroke="#9DAAD1" stroke-width="1.5"/>
              <path d="M8 19H74" stroke="#C5CDE2" stroke-width="1.5"/>
              <circle cx="15" cy="14" r="2" fill="#A0ACCC"/>
              <circle cx="22" cy="14" r="2" fill="#A0ACCC"/>
              <circle cx="29" cy="14" r="2" fill="#A0ACCC"/>
              <path d="M17 48V30M17 48H64" fill="none" stroke="#AAB5D4" stroke-width="1.5" stroke-linecap="round"/>
              <path class="ums-s5__chart-line" d="M21 43L32 35L41 39L52 25L62 29" fill="none" stroke="#303485" stroke-width="2.7" stroke-linejoin="round" stroke-linecap="round"/>
              <circle cx="52" cy="25" r="3" fill="#D5A126"/>
              <path d="M32 57V64M50 57V64M24 64H58" stroke="#8998BF" stroke-width="1.5" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="ums-s5__experiment-copy">
            <h3><em>Controlled Agent Benchmark</em></h3>
            <p>Pengujian agen menggunakan skenario terkontrol.</p>
            <div class="ums-s5__metric">
              <span>FOKUS</span>
              <strong>Kinerja teknis agen</strong>
            </div>
          </div>
        </div>
      </section>
      <!-- EXPERIMENT II -->
      <section v-click class="ums-s5__experiment ums-s5__experiment--user">
        <div class="ums-s5__experiment-top">
          <span class="ums-s5__experiment-id">EKSPERIMEN 02</span>
          <span class="ums-s5__experiment-category">EVALUASI PENGGUNA</span>
        </div>
        <div class="ums-s5__experiment-body">
          <div class="ums-s5__experiment-icon">
            <svg viewBox="0 0 82 76" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ilustrasi peserta dan tahapan purchase funnel">
              <circle cx="24" cy="19" r="7" fill="#A8B5DB"/>
              <path d="M12 39C12 29 17 28 24 28C31 28 36 29 36 39" fill="#DCE3F5" stroke="#8D9DC8" stroke-width="1.5"/>
              <circle cx="55" cy="19" r="7" fill="#303485"/>
              <path d="M43 39C43 29 48 28 55 28C62 28 67 29 67 39" fill="#DCE3F5" stroke="#8D9DC8" stroke-width="1.5"/>
              <path d="M16 46H66L55 55H27Z" fill="#CED7EF" stroke="#9AA9D0" stroke-width="1"/>
              <path d="M27 57H55L49 64H33Z" fill="#8394C8"/>
              <path d="M33 66H49L44 72H38Z" fill="#303485"/>
              <path class="ums-s5__funnel-flow" d="M41 47V69" stroke="#D5A126" stroke-width="2.5" stroke-dasharray="4 3"/>
            </svg>
          </div>
          <div class="ums-s5__experiment-copy">
            <h3><em>Randomized User Experiment</em></h3>
            <p>Peserta dialokasikan secara acak ke kondisi LLM.</p>
            <div class="ums-s5__metric">
              <span>FOKUS</span>
              <strong>Perilaku &amp; pengalaman pengguna</strong>
            </div>
          </div>
        </div>
      </section>
    </div>
    <!-- STEP 04: CONVERGENCE -->
    <div v-click class="ums-s5__merge">
      <svg viewBox="0 0 820 26" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path class="ums-s5__merge-base" d="M205 0V10H410M615 0V10H410V24"/>
        <path class="ums-s5__merge-active" d="M205 0V10H410M615 0V10H410V24"/>
        <circle cx="410" cy="10" r="3.5" fill="#303485"/>
        <path d="M405 19L410 24L415 19" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </div>
    <!-- STEP 05: RESULT SYNTHESIS -->
    <section v-click class="ums-s5__analysis">
      <div class="ums-s5__analysis-icon">
        <svg viewBox="0 0 46 46" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ilustrasi sintesis dua hasil eksperimen">
          <path d="M9 10H17L23 22M37 10H29L23 22M23 22V33" fill="none" stroke="#8594C3" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
          <circle cx="9" cy="10" r="5" fill="#A0AEDA"/>
          <circle cx="37" cy="10" r="5" fill="#303485"/>
          <circle class="ums-s5__analysis-node" cx="23" cy="35" r="7" fill="#303485"/>
          <path d="M20 35L22 37L26 33" fill="none" stroke="#FFFFFF" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <div class="ums-s5__analysis-copy">
        <span class="ums-s5__analysis-label">SINTESIS HASIL</span>
        <h3>Analisis Hasil Kedua Eksperimen</h3>
        <p>Menggunakan sistem yang sama, dengan prompt, katalog, harga, dan tools. supaya hasil perbandingannya lebih adil.</p>
      </div>
    </section>
  </main>
</div>

<style scoped>
/* ==========================================
   SLIDE 5 — ANIMATED RESEARCH DESIGN
   Canvas: 980 x 552
   Background: Official UMS /13.jpg
   ========================================== */

/* 01 — CANVAS */
.ums-s5 {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  overflow: hidden;
  isolation: isolate;
  background: #ffffff url('/13.jpg') center / cover no-repeat;
  font-family: 'Inter', 'Aptos', Arial, sans-serif;
  color: #242867;
  -webkit-font-smoothing: antialiased;
}
.ums-s5,
.ums-s5 * {
  box-sizing: border-box;
}

/* 02 — HEADER */
.ums-s5__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 55px;
}
.ums-s5__section {
  display: flex;
  align-items: center;
  margin-bottom: 8px;
  color: #303485;
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .11em;
}
.ums-s5__title {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 27px;
  font-weight: 720;
  line-height: 1.18;
  letter-spacing: -.03em;
}
.ums-s5__intro {
  margin: 7px 0 0;
  color: #68728c;
  font-size: 11.5px;
  line-height: 1.45;
}

/* 03 — DIAGRAM CONTAINER */
.ums-s5__diagram {
  position: absolute;
  top: 178px;
  left: 80px;
  right: 80px;
  bottom: 84px;
  display: flex;
  flex-direction: column;
  align-items: stretch;
  justify-content: space-between;
}

/* 04 — COMMON ENVIRONMENT */
.ums-s5__source {
  width: 660px;
  max-width: 100%;
  height: 64px;
  flex: 0 0 64px;
  align-self: center;
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 8px 16px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  border-radius: 0px;
}
.ums-s5__source-icon {
  width: 38px;
  height: 38px;
  flex: 0 0 38px;
}
.ums-s5__source-icon svg {
  width: 100%;
  height: 100%;
}
.ums-s5__source-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s5__eyebrow {
  display: block;
  margin-bottom: 4px;
  color: #7782A2;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .09em;
}
.ums-s5__source h2 {
  margin: 0;
  padding: 0;
  font-size: 16px;
  font-weight: 700;
  line-height: 1.2;
  color: #242867;
}
.ums-s5__source h2 em {
  font-style: italic;
  font-weight: 600;
}
.ums-s5__source p {
  margin: 4px 0 0;
  font-size: 10px;
  line-height: 1.3;
  color: #68728c;
}
.ums-s5__model-group {
  flex: 0 0 auto;
  display: flex;
  flex-direction: column;
  gap: 3px;
  padding-left: 15px;
  border-left: 1px solid #D7DDED;
}
.ums-s5__model-group span {
  display: block;
  color: #59699E;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .06em;
}

/* 05 — SPLIT CONNECTION */
.ums-s5__split {
  width: 100%;
  height: 20px;
  flex: 0 0 20px;
}
.ums-s5__split svg,
.ums-s5__merge svg {
  display: block;
  width: 100%;
  height: 100%;
  overflow: visible;
}
.ums-s5__split-base,
.ums-s5__merge-base {
  fill: none;
  stroke: #D8DFED;
  stroke-width: 1.5;
}
.ums-s5__split-active {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 500;
  stroke-dashoffset: 500;
}
.ums-s5__split:not(.slidev-vclick-hidden)
.ums-s5__split-active {
  animation: ums-s5-draw 1.15s ease forwards;
}

/* 06 — EXPERIMENTS */
.ums-s5__experiments {
  width: 100%;
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
  height: 108px;
  flex: 0 0 108px;
}
.ums-s5__experiment {
  min-width: 0;
  height: 108px;
  padding: 9px 14px;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  background: #FFFFFF;
  border-radius: 0px;
}
.ums-s5__experiment--technical {
  border-top: 2px solid #303485;
}
.ums-s5__experiment--user {
  border-top: 2px solid #303485;
}
.ums-s5__experiment-top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 8px;
  padding-bottom: 5px;
  border-bottom: 1.5px solid #303485;
}
.ums-s5__experiment-id {
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .09em;
  color: #303485;
}
.ums-s5__experiment-category {
  font-size: 7.5px;
  font-weight: 600;
  letter-spacing: .035em;
  color: #8A94AF;
}
.ums-s5__experiment-body {
  display: flex;
  align-items: center;
  gap: 12px;
  padding-top: 6px;
}
.ums-s5__experiment-icon {
  flex: 0 0 58px;
  width: 58px;
  height: 55px;
}
.ums-s5__experiment-icon svg {
  display: block;
  width: 100%;
  height: 100%;
  overflow: visible;
}
.ums-s5__experiment-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s5__experiment h3 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 13.5px;
  font-weight: 650;
  line-height: 1.25;
  letter-spacing: -.015em;
}
.ums-s5__experiment h3 em {
  font-style: italic;
  font-weight: 600;
}
.ums-s5__experiment-copy > p {
  margin: 3px 0 0;
  color: #64708A;
  font-size: 9.5px;
  line-height: 1.35;
}
.ums-s5__metric {
  display: flex;
  align-items: baseline;
  gap: 8px;
  margin-top: 5px;
}
.ums-s5__metric span {
  flex: 0 0 auto;
  color: #8E99B1;
  font-size: 7px;
  font-weight: 700;
  letter-spacing: .07em;
}
.ums-s5__metric strong {
  color: #303485;
  font-size: 9.5px;
  font-weight: 650;
  line-height: 1.25;
}

/* 07 — MERGE CONNECTION */
.ums-s5__merge {
  width: 100%;
  height: 20px;
  flex: 0 0 20px;
}
.ums-s5__merge-active {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 500;
  stroke-dashoffset: 500;
}
.ums-s5__merge:not(.slidev-vclick-hidden)
.ums-s5__merge-active {
  animation: ums-s5-draw 1.15s ease forwards;
}
@keyframes ums-s5-draw {
  to {
    stroke-dashoffset: 0;
  }
}

/* 08 — SYNTHESIS */
.ums-s5__analysis {
  width: 660px;
  max-width: 100%;
  height: 56px;
  flex: 0 0 56px;
  align-self: center;
  display: flex;
  align-items: center;
  gap: 13px;
  padding: 6px 16px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  border-radius: 0px;
}
.ums-s5__analysis-icon {
  width: 36px;
  height: 36px;
  flex: 0 0 36px;
}
.ums-s5__analysis-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s5__analysis-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s5__analysis-label {
  display: block;
  margin-bottom: 3px;
  color: #5E6DA7;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .09em;
}
.ums-s5__analysis h3 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.2;
}
.ums-s5__analysis p {
  margin: 4px 0 0;
  color: #5F6B87;
  font-size: 10px;
  line-height: 1.3;
}

/* 09 — CLICK REVEAL */
.ums-s5__source,
.ums-s5__split,
.ums-s5__experiment,
.ums-s5__merge,
.ums-s5__analysis {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .65s cubic-bezier(.22,1,.36,1),
    transform .65s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s5 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(10px) !important;
  pointer-events: none;
}

/* 10 — SVG ANIMATIONS */
.ums-s5__chart-line {
  stroke-dasharray: 75;
  stroke-dashoffset: 75;
}
.ums-s5__experiment--technical:not(.slidev-vclick-hidden)
.ums-s5__chart-line {
  animation: ums-s5-chart 1.2s .35s ease forwards;
}
@keyframes ums-s5-chart {
  to {
    stroke-dashoffset: 0;
  }
}
.ums-s5__funnel-flow {
  stroke-dashoffset: 0;
}
.ums-s5__experiment--user:not(.slidev-vclick-hidden)
.ums-s5__funnel-flow {
  animation: ums-s5-flow 1.2s linear infinite;
}
@keyframes ums-s5-flow {
  to {
    stroke-dashoffset: -14;
  }
}
.ums-s5__analysis-node {
  transform-box: fill-box;
  transform-origin: center;
}
.ums-s5__analysis:not(.slidev-vclick-hidden)
.ums-s5__analysis-node {
  animation: ums-s5-node 2.5s ease-in-out infinite;
}
@keyframes ums-s5-node {
  0%, 100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.09);
  }
}

/* 11 — ACCESSIBILITY */
@media (prefers-reduced-motion: reduce) {
  .ums-s5 *,
  .ums-s5 *::before,
  .ums-s5 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s5 .slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
  .ums-s5__split-active,
  .ums-s5__merge-active,
  .ums-s5__chart-line {
    stroke-dashoffset: 0;
  }
}
</style>
