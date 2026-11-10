---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 3 — RUMUSAN MASALAH DAN TUJUAN PENELITIAN -->
<!-- Canvas: 980 x 552 | Background: /13.jpg -->
<!-- HTML dibuat kontigu agar kompatibel dengan Slidev Markdown -->

<div class="ums-s3">
  <header class="ums-s3__header">
    <div class="ums-s3__section">
      <span>02 / ARAH PENELITIAN</span>
    </div>
    <h1 class="ums-s3__title">Rumusan Masalah &amp; Tujuan Penelitian</h1>
    <p class="ums-s3__intro">Tiga pertanyaan utama yang menjadi dasar evaluasi kinerja asisten belanja berbasis LLM.</p>
  </header>
  <main class="ums-s3__main">
    <div class="ums-s3__column-head">
      <div class="ums-s3__column-left">RUMUSAN MASALAH</div>
      <div class="ums-s3__column-center">HUBUNGAN</div>
      <div class="ums-s3__column-right">TUJUAN PENELITIAN</div>
    </div>
    <div class="ums-s3__rows">
      <!-- PAIR 01 — TECHNICAL PERFORMANCE -->
      <section v-click class="ums-s3__pair">
        <div class="ums-s3__question">
          <span class="ums-s3__index">01</span>
          <div class="ums-s3__icon">
            <svg viewBox="0 0 48 48" aria-label="Ilustrasi evaluasi teknis" role="img">
              <rect x="6" y="9" width="36" height="28" rx="4" fill="#E7EBF8" stroke="#5869AB" stroke-width="1.5"/>
              <path d="M12 30L19 23L25 27L35 16" fill="none" stroke="#303485" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" class="ums-s3__graph-line"/>
              <circle cx="19" cy="23" r="2.4" fill="#303485"/>
              <circle cx="25" cy="27" r="2.4" fill="#303485"/>
              <circle cx="35" cy="16" r="2.4" fill="#D5A126"/>
              <path d="M18 42H30M24 37V42" stroke="#5869AB" stroke-width="1.5" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="ums-s3__text">
            <span class="ums-s3__eyebrow">KINERJA TEKNIS</span>
            <p>Apakah terdapat perbedaan kemampuan teknis antar-LLM ketika digunakan dalam sistem yang sama?</p>
          </div>
        </div>
        <div class="ums-s3__connection" aria-hidden="true">
          <svg viewBox="0 0 90 44">
            <path class="ums-s3__connection-base" d="M5 22H83"/>
            <path class="ums-s3__connection-progress" d="M5 22H83"/>
            <path class="ums-s3__connection-arrow" d="M76 15L83 22L76 29"/>
            <circle class="ums-s3__connection-dot" cx="5" cy="22" r="3.5"/>
          </svg>
        </div>
        <div class="ums-s3__objective">
          <div class="ums-s3__objective-icon">
            <svg viewBox="0 0 48 48" aria-label="Target evaluasi teknis" role="img">
              <circle cx="24" cy="24" r="17" fill="#EEF1FA" stroke="#7988BD" stroke-width="1.5"/>
              <circle cx="24" cy="24" r="10" fill="none" stroke="#7988BD" stroke-width="1.5"/>
              <circle cx="24" cy="24" r="4" fill="#303485"/>
              <path class="ums-s3__target-arrow" d="M36 12L24 24" stroke="#D2A126" stroke-width="2" stroke-linecap="round"/>
              <path d="M31 12H36V17" fill="none" stroke="#D2A126" stroke-width="2" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="ums-s3__text">
            <span class="ums-s3__eyebrow">TUJUAN 01</span>
            <p>Membandingkan kinerja teknis <em>LLM</em> dalam sistem yang sama.</p>
          </div>
        </div>
      </section>
      <!-- PAIR 02 — USER BEHAVIOR -->
      <section v-click class="ums-s3__pair">
        <div class="ums-s3__question">
          <span class="ums-s3__index">02</span>
          <div class="ums-s3__icon">
            <svg viewBox="0 0 48 48" aria-label="Ilustrasi perilaku belanja" role="img">
              <path d="M9 13H14L18 32H37L41 19H16" fill="#E7EBF8" stroke="#5869AB" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
              <circle cx="21" cy="38" r="3" fill="#303485"/>
              <circle cx="35" cy="38" r="3" fill="#303485"/>
              <path class="ums-s3__cart-path" d="M21 25H35" stroke="#D5A126" stroke-width="2.5" stroke-linecap="round"/>
              <path class="ums-s3__cart-path" d="M31 21L35 25L31 29" fill="none" stroke="#D5A126" stroke-width="2" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="ums-s3__text">
            <span class="ums-s3__eyebrow">PERILAKU &amp; PENGALAMAN</span>
            <p>Apakah perilaku belanja dan pengalaman pengguna juga berbeda tergantung LLM yang digunakan?</p>
          </div>
        </div>
        <div class="ums-s3__connection" aria-hidden="true">
          <svg viewBox="0 0 90 44">
            <path class="ums-s3__connection-base" d="M5 22H83"/>
            <path class="ums-s3__connection-progress" d="M5 22H83"/>
            <path class="ums-s3__connection-arrow" d="M76 15L83 22L76 29"/>
            <circle class="ums-s3__connection-dot" cx="5" cy="22" r="3.5"/>
          </svg>
        </div>
        <div class="ums-s3__objective">
          <div class="ums-s3__objective-icon">
            <svg viewBox="0 0 48 48" aria-label="Ilustrasi purchase funnel" role="img">
              <path d="M5 9H43L33 21H15Z" fill="#DCE3F6" stroke="#7180B4" stroke-width="1.2"/>
              <path d="M15 24H33L29 32H19Z" fill="#9EACD3" stroke="#7180B4" stroke-width="1.2"/>
              <path d="M19 35H29L26 42H22Z" fill="#303485"/>
              <path class="ums-s3__funnel-flow" d="M24 11V40" stroke="#D5A126" stroke-width="2" stroke-dasharray="3 4" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="ums-s3__text">
            <span class="ums-s3__eyebrow">TUJUAN 02</span>
            <p>Membandingkan tindakan <em>purchase funnel</em> dan pengalaman pengguna.</p>
          </div>
        </div>
      </section>
      <!-- PAIR 03 — RELATIONSHIP ANALYSIS -->
      <section v-click class="ums-s3__pair">
        <div class="ums-s3__question">
          <span class="ums-s3__index">03</span>
          <div class="ums-s3__icon">
            <svg viewBox="0 0 48 48" aria-label="Ilustrasi hubungan antarvariabel" role="img">
              <path d="M14 14L34 15L24 35L14 14" fill="none" stroke="#A3AFD0" stroke-width="2" class="ums-s3__network-line"/>
              <circle class="ums-s3__network-node" cx="14" cy="14" r="6" fill="#303485"/>
              <circle class="ums-s3__network-node" cx="34" cy="15" r="6" fill="#7889C2"/>
              <circle class="ums-s3__network-node" cx="24" cy="35" r="6" fill="#D5A126"/>
              <circle cx="14" cy="14" r="2" fill="#FFFFFF"/>
              <circle cx="34" cy="15" r="2" fill="#FFFFFF"/>
              <circle cx="24" cy="35" r="2" fill="#FFFFFF"/>
            </svg>
          </div>
          <div class="ums-s3__text">
            <span class="ums-s3__eyebrow">HUBUNGAN ANTARVARIABEL</span>
            <p>Apakah kualitas bantuan AI memiliki hubungan dengan tindakan dan penilaian pengguna?</p>
          </div>
        </div>
        <div class="ums-s3__connection" aria-hidden="true">
          <svg viewBox="0 0 90 44">
            <path class="ums-s3__connection-base" d="M5 22H83"/>
            <path class="ums-s3__connection-progress" d="M5 22H83"/>
            <path class="ums-s3__connection-arrow" d="M76 15L83 22L76 29"/>
            <circle class="ums-s3__connection-dot" cx="5" cy="22" r="3.5"/>
          </svg>
        </div>
        <div class="ums-s3__objective">
          <div class="ums-s3__objective-icon">
            <svg viewBox="0 0 48 48" aria-label="Ilustrasi analisis hubungan" role="img">
              <path d="M8 8V40H42" fill="none" stroke="#9DA8C8" stroke-width="1.5" stroke-linecap="round"/>
              <path class="ums-s3__trend-line" d="M12 34L20 28L27 30L37 14" fill="none" stroke="#303485" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
              <circle cx="12" cy="34" r="3" fill="#7C8CBC"/>
              <circle cx="20" cy="28" r="3" fill="#7C8CBC"/>
              <circle cx="27" cy="30" r="3" fill="#7C8CBC"/>
              <circle cx="37" cy="14" r="3.5" fill="#D5A126"/>
            </svg>
          </div>
          <div class="ums-s3__text">
            <span class="ums-s3__eyebrow">TUJUAN 03</span>
            <p>Menganalisis hubungan kualitas bantuan, tindakan, dan penilaian pengguna.</p>
          </div>
        </div>
      </section>
    </div>
  </main>
</div>

<style scoped>
/* ===========================================
   SLIDE 3 — RESEARCH QUESTION MAPPING
   Canvas: 980 × 552
   Theme: UMS Academic Editorial
   =========================================== */

/* 01 — CANVAS */
.ums-s3 {
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

/* 02 — HEADER */
.ums-s3__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 55px;
}

.ums-s3__section {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
  font-size: 9px;
  font-weight: 700;
  letter-spacing: 0.11em;
  color: #303485;
}

.ums-s3__title {
  margin: 0;
  padding: 0;
  font-size: 28px;
  font-weight: 720;
  line-height: 1.16;
  letter-spacing: -0.035em;
  color: #242867;
}

.ums-s3__intro {
  margin: 7px 0 0;
  font-size: 11.5px;
  line-height: 1.45;
  color: #68728c;
}

/* 03 — CONTENT AREA */
.ums-s3__main {
  position: absolute;
  top: 184px;
  left: 55px;
  right: 55px;
  bottom: 84px;
}

.ums-s3__column-head {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 80px minmax(0, 1fr);
  column-gap: 8px;
  align-items: end;
  padding: 0 4px 8px;
  border-bottom: 2px solid #303485;
}

.ums-s3__column-left,
.ums-s3__column-right {
  font-size: 9px;
  font-weight: 700;
  letter-spacing: 0.09em;
  color: #303485;
}

.ums-s3__column-center {
  font-size: 7.5px;
  font-weight: 600;
  letter-spacing: 0.045em;
  text-align: center;
  color: #98A2BA;
}

/* 04 — RESEARCH PAIRS */
.ums-s3__rows {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.ums-s3__pair {
  position: relative;
  display: grid;
  grid-template-columns: minmax(0, 1fr) 80px minmax(0, 1fr);
  column-gap: 8px;
  align-items: center;
  box-sizing: border-box;
  height: 74px;
  min-height: 74px;
  padding: 4px 12px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  border-radius: 0px;
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity 0.7s ease,
    transform 0.7s cubic-bezier(.22,1,.36,1)
    !important;
}

.ums-s3__pair.slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(16px) !important;
  pointer-events: none;
}

.ums-s3__pair:nth-child(even) {
  background: #FFFFFF;
}

/* 05 — QUESTION COLUMN */
.ums-s3__question {
  display: flex;
  align-items: center;
  gap: 11px;
  min-width: 0;
  padding: 9px 0 9px 4px;
}

.ums-s3__index {
  flex: 0 0 20px;
  font-size: 12px;
  font-weight: 650;
  letter-spacing: -0.02em;
  color: #9AA4BE;
}

.ums-s3__icon {
  flex: 0 0 44px;
  width: 44px;
  height: 44px;
}

.ums-s3__icon svg {
  display: block;
  width: 100%;
  height: 100%;
  overflow: visible;
}

.ums-s3__text {
  flex: 1 1 auto;
  min-width: 0;
}

.ums-s3__eyebrow {
  display: block;
  margin-bottom: 5px;
  font-size: 8px;
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: 0.07em;
  color: #8792AD;
}

.ums-s3__text p {
  margin: 0;
  font-size: 11.8px;
  font-weight: 500;
  line-height: 1.42;
  color: #35405E;
}

.ums-s3__text em {
  font-style: italic;
}

/* 06 — RELATIONSHIP CONNECTOR */
.ums-s3__connection {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 80px;
  height: 44px;
}

.ums-s3__connection svg {
  display: block;
  width: 80px;
  height: 40px;
  overflow: visible;
}

.ums-s3__connection-base {
  fill: none;
  stroke: #D5DBE9;
  stroke-width: 1.5;
}

.ums-s3__connection-progress {
  fill: none;
  stroke: #303485;
  stroke-width: 2.4;
  stroke-linecap: round;
  stroke-dasharray: 78;
  stroke-dashoffset: 78;
  animation: ums-s3-draw 1.15s 0.35s ease forwards;
}

.ums-s3__connection-arrow {
  fill: none;
  stroke: #303485;
  stroke-width: 2.4;
  stroke-linecap: round;
  stroke-linejoin: round;
  opacity: 0;
  animation: ums-s3-arrow-in .4s 1.25s ease forwards;
}

.ums-s3__connection-dot {
  fill: #D5A126;
  animation: ums-s3-dot-pulse 2.8s 1.5s ease-in-out infinite;
}

@keyframes ums-s3-draw {
  from {
    stroke-dashoffset: 78;
  }
  to {
    stroke-dashoffset: 0;
  }
}

@keyframes ums-s3-arrow-in {
  to {
    opacity: 1;
  }
}

@keyframes ums-s3-dot-pulse {
  0%, 100% {
    opacity: 0.65;
    transform: scale(1);
  }
  50% {
    opacity: 1;
    transform: scale(1.12);
  }
}

/* 07 — OBJECTIVE COLUMN */
.ums-s3__objective {
  display: flex;
  align-items: center;
  gap: 13px;
  min-width: 0;
  padding: 9px 6px 9px 0;
}

.ums-s3__objective-icon {
  flex: 0 0 44px;
  width: 44px;
  height: 44px;
}

.ums-s3__objective-icon svg {
  display: block;
  width: 100%;
  height: 100%;
  overflow: visible;
}

.ums-s3__objective .ums-s3__text p {
  color: #242867;
  font-weight: 600;
}

.ums-s3__objective .ums-s3__eyebrow {
  color: #5869A7;
}

/* ===========================================
   SVG MICRO-ANIMATIONS
   =========================================== */

/* 08 — TECHNICAL GRAPH */
.ums-s3__graph-line {
  stroke-dasharray: 40;
  stroke-dashoffset: 40;
  animation: ums-s3-graph-draw 1.6s 0.4s ease forwards;
}

@keyframes ums-s3-graph-draw {
  to {
    stroke-dashoffset: 0;
  }
}

/* 09 — TARGET ARROW */
.ums-s3__target-arrow {
  stroke-dasharray: 20;
  stroke-dashoffset: 20;
  animation: ums-s3-target-in 1s 0.8s ease forwards;
}

@keyframes ums-s3-target-in {
  to {
    stroke-dashoffset: 0;
  }
}

/* 10 — SHOPPING CART FLOW */
.ums-s3__cart-path {
  animation: ums-s3-cart-highlight 2.5s ease-in-out infinite;
}

@keyframes ums-s3-cart-highlight {
  0%, 100% {
    opacity: 0.45;
  }
  50% {
    opacity: 1;
  }
}

/* 11 — PURCHASE FUNNEL */
.ums-s3__funnel-flow {
  animation: ums-s3-funnel-data 1.5s linear infinite;
}

@keyframes ums-s3-funnel-data {
  to {
    stroke-dashoffset: -14;
  }
}

/* 12 — VARIABLE NETWORK */
.ums-s3__network-line {
  stroke-dasharray: 70;
  stroke-dashoffset: 70;
  animation: ums-s3-network-draw 1.5s .4s ease forwards;
}

@keyframes ums-s3-network-draw {
  to {
    stroke-dashoffset: 0;
  }
}

.ums-s3__network-node {
  transform-box: fill-box;
  transform-origin: center;
  animation: ums-s3-node-pulse 3s ease-in-out infinite;
}

@keyframes ums-s3-node-pulse {
  0%, 100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.12);
  }
}

/* 13 — RELATIONSHIP TREND */
.ums-s3__trend-line {
  stroke-dasharray: 65;
  stroke-dashoffset: 65;
  animation: ums-s3-trend-draw 1.6s .5s ease forwards;
}

@keyframes ums-s3-trend-draw {
  to {
    stroke-dashoffset: 0;
  }
}

/* 14 — ACCESSIBILITY */
@media (prefers-reduced-motion: reduce) {
  .ums-s3 *,
  .ums-s3 *::before,
  .ums-s3 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s3__pair.slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
  .ums-s3__connection-progress,
  .ums-s3__graph-line,
  .ums-s3__target-arrow,
  .ums-s3__network-line,
  .ums-s3__trend-line {
    stroke-dashoffset: 0;
  }
  .ums-s3__connection-arrow {
    opacity: 1;
  }
}
</style>
