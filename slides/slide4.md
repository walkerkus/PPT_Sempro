---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 4 — LITERATURE MAPPING & RESEARCH GAP -->
<!-- Canvas: 980 x 552 | Background: /6.jpg -->
<!-- Safe area: left 55px, right 195px -->
<!-- HTML kontigu untuk kompatibilitas Slidev Markdown -->

<div class="ums-s4">
  <header class="ums-s4__header">
    <div class="ums-s4__section">
      <span>03 / TINJAUAN PUSTAKA</span>
    </div>
    <h1 class="ums-s4__title">Posisi Penelitian dan <em>Research Gap</em></h1>
    <p class="ums-s4__intro">Pemetaan fokus penelitian terdahulu untuk menunjukkan posisi dan arah kontribusi penelitian ini.</p>
  </header>
  <main class="ums-s4__main">
    <div class="ums-s4__table-head">
      <span>PENELITIAN TERDAHULU</span>
      <span>FOKUS KAJIAN</span>
    </div>
    <div class="ums-s4__literature">
      <!-- REFERENCE 01 -->
      <section v-click="1" class="ums-s4__row">
        <div class="ums-s4__reference">
          <span class="ums-s4__index">01</span>
          <div class="ums-s4__reference-text">
            <strong>Jannach</strong>
            <span>2023</span>
          </div>
        </div>
        <div class="ums-s4__topic">
          <div class="ums-s4__topic-icon">
            <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Evaluasi sistem rekomendasi percakapan">
              <rect x="4" y="7" width="25" height="18" rx="4" fill="#E5EAF7" stroke="#8999C5" stroke-width="1.4"/>
              <path d="M11 25L8 30V25" fill="#E5EAF7" stroke="#8999C5" stroke-width="1.4" stroke-linejoin="round"/>
              <path d="M10 13H23M10 18H19" stroke="#303485" stroke-width="1.8" stroke-linecap="round"/>
              <path d="M23 29H29L34 34V29H36V17H31" fill="none" stroke="#8596C2" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </div>
          <div class="ums-s4__topic-text">
            <span class="ums-s4__topic-label">SISTEM REKOMENDASI</span>
            <p>Bagaimana sistem rekomendasi berbasis percakapan dievaluasi.</p>
          </div>
        </div>
      </section>
      <!-- REFERENCE 02 -->
      <section v-click="2" class="ums-s4__row">
        <div class="ums-s4__reference">
          <span class="ums-s4__index">02</span>
          <div class="ums-s4__reference-text">
            <strong>Yao et al.</strong>
            <span>2023, 2025</span>
          </div>
        </div>
        <div class="ums-s4__topic">
          <div class="ums-s4__topic-icon">
            <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Reasoning dan penggunaan tools">
              <rect x="3" y="14" width="11" height="12" rx="2" fill="#DCE4F5" stroke="#8495C2" stroke-width="1.3"/>
              <rect x="26" y="5" width="11" height="12" rx="2" fill="#DCE4F5" stroke="#8495C2" stroke-width="1.3"/>
              <rect x="26" y="24" width="11" height="12" rx="2" fill="#DCE4F5" stroke="#8495C2" stroke-width="1.3"/>
              <path class="ums-s4__network-flow" d="M14 20H20V11H26M20 20V30H26" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
              <circle cx="20" cy="20" r="2.5" fill="#D4A32B"/>
            </svg>
          </div>
          <div class="ums-s4__topic-text">
            <span class="ums-s4__topic-label">AGEN DAN TOOLS</span>
            <p>Kemampuan penalaran, penggunaan tools, serta evaluasi agen AI.</p>
          </div>
        </div>
      </section>
      <!-- REFERENCE 03 -->
      <section v-click="3" class="ums-s4__row">
        <div class="ums-s4__reference">
          <span class="ums-s4__index">03</span>
          <div class="ums-s4__reference-text">
            <strong>Fan et al.</strong>
            <span>2026</span>
          </div>
        </div>
        <div class="ums-s4__topic">
          <div class="ums-s4__topic-icon">
            <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Benchmark kemampuan model">
              <path d="M5 6V34H36" fill="none" stroke="#A0ACCA" stroke-width="1.5" stroke-linecap="round"/>
              <rect class="ums-s4__chart-bar" x="10" y="20" width="6" height="14" rx="1" fill="#A8B6D9"/>
              <rect class="ums-s4__chart-bar" x="20" y="12" width="6" height="22" rx="1" fill="#303485"/>
              <rect class="ums-s4__chart-bar" x="30" y="17" width="6" height="17" rx="1" fill="#8496C7"/>
              <path d="M10 9H30" stroke="#CBA338" stroke-width="1.5" stroke-dasharray="3 3"/>
            </svg>
          </div>
          <div class="ums-s4__topic-text">
            <span class="ums-s4__topic-label">BENCHMARK BELANJA</span>
            <p>Berfokus pada penalaran dalam aktivitas belanja.</p>
          </div>
        </div>
      </section>
      <!-- REFERENCE 04 -->
      <section v-click="4" class="ums-s4__row">
        <div class="ums-s4__reference">
          <span class="ums-s4__index">04</span>
          <div class="ums-s4__reference-text">
            <strong>Tafesse &amp; Sandhu</strong>
            <span>2026</span>
          </div>
        </div>
        <div class="ums-s4__topic">
          <div class="ums-s4__topic-icon">
            <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Pengalaman konsumen">
              <circle cx="14" cy="12" r="5" fill="#A8B6D9"/>
              <path d="M5 27C5 20 8 19 14 19C20 19 23 20 23 27" fill="#DCE4F5" stroke="#8B9BC5" stroke-width="1.2"/>
              <rect x="23" y="10" width="14" height="17" rx="3" fill="#E9EDF8" stroke="#8797C3" stroke-width="1.3"/>
              <path d="M27 16H33M27 21H31" stroke="#303485" stroke-width="1.6" stroke-linecap="round"/>
              <path class="ums-s4__user-check" d="M25 32L29 36L36 28" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </div>
          <div class="ums-s4__topic-text">
            <span class="ums-s4__topic-label">PENGALAMAN KONSUMEN</span>
            <p>Pengalaman pengguna dalam mengambil keputusan dengan bantuan AI.</p>
          </div>
        </div>
      </section>
    </div>
    <!-- RESEARCH GAP -->
    <section v-click="5" class="ums-s4__gap">
      <div class="ums-s4__gap-heading">
        <span>POSISI DAN FOKUS PENELITIAN INI</span>
        <h2>Mengintegrasikan evaluasi agen dan respons pengguna</h2>
      </div>
      <div class="ums-s4__integration">
        <div class="ums-s4__integration-node">
          <span>01</span>
          <strong>Kinerja teknis</strong>
        </div>
        <div class="ums-s4__integration-plus">+</div>
        <div class="ums-s4__integration-node">
          <span>02</span>
          <strong>Perilaku belanja</strong>
        </div>
        <div class="ums-s4__integration-plus">+</div>
        <div class="ums-s4__integration-node">
          <span>03</span>
          <strong>Pengalaman pengguna</strong>
        </div>
      </div>
      <p>Ketiganya dikaji melalui perbandingan beberapa <em>LLM</em> dalam satu lingkungan <em>e-commerce</em> simulasi yang terkontrol.</p>
    </section>
  </main>
</div>

<style scoped>
/* ============================================
   SLIDE 4 — LITERATURE MAPPING & RESEARCH GAP
   Canvas: 980 × 552
   Background: Official UMS /6.jpg
   Safe Area: left 55px, right 195px
   ============================================ */

/* 01 — CANVAS */
.ums-s4 {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  overflow: hidden;
  isolation: isolate;
  background: #ffffff url('/6.jpg') center / cover no-repeat;
  color: #242867;
  font-family: 'Inter', 'Aptos', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
}
.ums-s4,
.ums-s4 * {
  box-sizing: border-box;
}

/* 02 — HEADER */
.ums-s4__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 195px;
}
.ums-s4__section {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
  color: #303485;
  font-size: 9px;
  font-weight: 700;
  letter-spacing: .11em;
}
.ums-s4__title {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 27px;
  font-weight: 720;
  line-height: 1.16;
  letter-spacing: -.03em;
}
.ums-s4__title em {
  font-weight: 500;
  font-style: italic;
}
.ums-s4__intro {
  margin: 7px 0 0;
  font-size: 11px;
  line-height: 1.45;
  color: #68728C;
}

/* 03 — MAIN CONTENT */
.ums-s4__main {
  position: absolute;
  top: 184px;
  left: 55px;
  right: 195px;
  bottom: 82px;
}

/* 04 — LITERATURE HEADINGS */
.ums-s4__table-head {
  display: grid;
  grid-template-columns: 37% 63%;
  align-items: center;
  height: 28px;
  border-bottom: 2px solid #303485;
}
.ums-s4__table-head span {
  color: #303485;
  font-size: 9px;
  font-weight: 700;
  letter-spacing: .085em;
}
.ums-s4__table-head span:first-child {
  padding-left: 27px;
}
.ums-s4__table-head span:last-child {
  padding-left: 8px;
}

/* 05 — LITERATURE ROWS */
.ums-s4__literature {
  display: flex;
  flex-direction: column;
}
.ums-s4__row {
  display: grid;
  grid-template-columns: 37% 63%;
  align-items: center;
  height: 44px;
  min-height: 44px;
  border-bottom: 1px solid #DFE4ED;
}
.ums-s4__row:nth-child(even) {
  background: rgba(240,243,250,.34);
}

/* 06 — AUTHOR COLUMN */
.ums-s4__reference {
  display: flex;
  align-items: center;
  gap: 12px;
  min-width: 0;
  padding: 5px 7px 5px 2px;
}
.ums-s4__index {
  flex: 0 0 14px;
  color: #A0AAC0;
  font-size: 10px;
  font-weight: 600;
}
.ums-s4__reference-text {
  display: flex;
  flex-direction: column;
  min-width: 0;
  gap: 3px;
}
.ums-s4__reference-text strong {
  color: #293363;
  font-size: 11.5px;
  font-weight: 700;
  line-height: 1.15;
}
.ums-s4__reference-text > span {
  color: #8490A9;
  font-size: 9px;
  line-height: 1.1;
}

/* 07 — RESEARCH FOCUS COLUMN */
.ums-s4__topic {
  display: flex;
  align-items: center;
  gap: 10px;
  min-width: 0;
  padding: 3px 0 3px 8px;
}
.ums-s4__topic-icon {
  width: 32px;
  height: 32px;
  flex: 0 0 32px;
}
.ums-s4__topic-icon svg {
  display: block;
  width: 100%;
  height: 100%;
  overflow: visible;
}
.ums-s4__topic-text {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s4__topic-label {
  display: block;
  margin-bottom: 2px;
  color: #8491AE;
  font-size: 7px;
  font-weight: 700;
  letter-spacing: .07em;
}
.ums-s4__topic-text p {
  margin: 0;
  color: #485571;
  font-size: 10px;
  line-height: 1.25;
  font-weight: 500;
}
.ums-s4__topic-text em {
  font-style: italic;
}

/* 08 — RESEARCH GAP PANEL */
.ums-s4__gap {
  position: relative;
  width: 100%;
  min-height: 82px;
  margin-top: 8px;
  padding: 8px 14px;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  background: #FFFFFF;
}
.ums-s4__gap-heading > span {
  display: block;
  margin-bottom: 3px;
  color: #303485;
  font-size: 7.5px;
  font-weight: 800;
  letter-spacing: .085em;
}
.ums-s4__gap-heading h2 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 13px;
  font-weight: 750;
  line-height: 1.2;
  letter-spacing: -.015em;
}

/* 09 — INTEGRATION DIAGRAM */
.ums-s4__integration {
  display: grid;
  grid-template-columns:
    minmax(0,1fr)
    15px
    minmax(0,1fr)
    15px
    minmax(0,1fr);
  align-items: center;
  gap: 5px;
  margin-top: 6px;
}
.ums-s4__integration-node {
  display: flex;
  align-items: center;
  gap: 6px;
  min-width: 0;
  height: 25px;
  padding: 4px 8px;
  border: 1.5px solid #303485;
  background: #F4F7FC;
  box-shadow: 2px 2px 0px #303485;
}
.ums-s4__integration-node > span {
  flex: 0 0 auto;
  color: #8796B7;
  font-size: 7.5px;
  font-weight: 700;
}
.ums-s4__integration-node strong {
  color: #303485;
  font-size: 8.5px;
  font-weight: 650;
  line-height: 1.2;
  white-space: nowrap;
}
.ums-s4__integration-plus {
  color: #A3AEC7;
  font-size: 14px;
  font-weight: 400;
  text-align: center;
}
.ums-s4__gap > p {
  margin: 6px 0 0;
  color: #61708A;
  font-size: 9px;
  line-height: 1.3;
}
.ums-s4__gap > p em {
  font-style: italic;
}

/* ============================================
   SVG MICRO ANIMATIONS
   ============================================ */

/* 10 — TOOL FLOW */
.ums-s4__network-flow {
  stroke-dasharray: 65;
  stroke-dashoffset: 65;
}
.ums-s4__row:not(.slidev-vclick-hidden)
.ums-s4__network-flow {
  animation: ums-s4-draw .8s .2s ease forwards;
}
@keyframes ums-s4-draw {
  to { stroke-dashoffset: 0; }
}

/* 11 — BENCHMARK BARS */
.ums-s4__chart-bar {
  transform-box: fill-box;
  transform-origin: bottom center;
}
.ums-s4__row:not(.slidev-vclick-hidden)
.ums-s4__chart-bar {
  animation: ums-s4-bar-in .6s ease-out both;
}
.ums-s4__chart-bar:nth-of-type(1) {
  animation-delay: .15s;
}
.ums-s4__chart-bar:nth-of-type(2) {
  animation-delay: .3s;
}
.ums-s4__chart-bar:nth-of-type(3) {
  animation-delay: .45s;
}
@keyframes ums-s4-bar-in {
  from { opacity: .3; transform: scaleY(.08); }
  to { opacity: 1; transform: scaleY(1); }
}

/* 12 — USER EXPERIENCE CHECK */
.ums-s4__user-check {
  stroke-dasharray: 25;
  stroke-dashoffset: 25;
}
.ums-s4__row:not(.slidev-vclick-hidden)
.ums-s4__user-check {
  animation: ums-s4-draw .75s .3s ease forwards;
}

/* 13 — INTEGRATION ANIMATION */
.ums-s4__gap:not(.slidev-vclick-hidden)
.ums-s4__integration-node {
  animation: ums-s4-node-in .5s ease both;
}
.ums-s4__integration-node:nth-child(1) {
  animation-delay: .2s;
}
.ums-s4__integration-node:nth-child(3) {
  animation-delay: .4s;
}
.ums-s4__integration-node:nth-child(5) {
  animation-delay: .6s;
}
@keyframes ums-s4-node-in {
  from {
    opacity: 0;
    transform: translateY(7px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* 14 — SLIDEV CLICK REVEAL */
.ums-s4__row,
.ums-s4__gap {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .65s cubic-bezier(.22,1,.36,1),
    transform .65s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s4 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(10px) !important;
  pointer-events: none;
}

/* 15 — ACCESSIBILITY */
@media (prefers-reduced-motion: reduce) {
  .ums-s4 *,
  .ums-s4 *::before,
  .ums-s4 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s4 .slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
  .ums-s4__network-flow,
  .ums-s4__user-check {
    stroke-dashoffset: 0;
  }
}
</style>
