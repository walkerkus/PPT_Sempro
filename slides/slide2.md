---
layout: default
transition: fade
class: ums-background-slide
---

<!--
SLIDE 2 — LATAR BELAKANG
UMS Academic Visual Storytelling

Canvas: 980 × 552
Background: ppt/public/13.jpg

CLICK SEQUENCE
1. Masalah: product overload
2. Solusi: agentic assistant
3. Kebutuhan: evaluasi LLM
4. Kesimpulan penelitian

SVG dibuat langsung di dalam Slidev.
Tidak memerlukan library tambahan.
-->

<div class="ums-s2">
  <!-- ================= HEADER ================= -->
  <header class="ums-s2__header">
    <div class="ums-s2__section">
      <span>01 / PENDAHULUAN</span>
      <span class="ums-s2__section-divider">/</span>
      <span>LATAR BELAKANG</span>
    </div>
    <h1 class="ums-s2__title">
      Mengapa Pemilihan LLM Penting
      <br />
      dalam Asisten Belanja AI?
    </h1>
    <p class="ums-s2__intro">
      Model bahasa yang berbeda dapat menghasilkan kualitas
      bantuan dan keputusan belanja yang berbeda.
    </p>
  </header>
  <!-- ================= MAIN ================= -->
  <main class="ums-s2__main">
    <div class="ums-s2__flow">
      <!-- STAGE 01: PRODUCT OVERLOAD -->
      <section v-click class="ums-s2__stage">
        <div class="ums-s2__visual">
          <svg
            viewBox="0 0 250 105"
            class="ums-s2__svg"
            role="img"
            aria-label="Beragam produk menyebabkan kebingungan memilih"
          >
            <!-- Product cards -->
            <g class="ums-s2__product p1">
              <rect
                x="25" y="13"
                width="54" height="66"
                rx="6"
                fill="#FFFFFF"
                stroke="#D5DBEA"
              />
              <rect
                x="32" y="20"
                width="40" height="30"
                rx="4"
                fill="#DCE3F6"
              />
              <path
                d="M45 31h14v10H45z"
                fill="#7A8BC4"
              />
              <path
                d="M34 58h32M34 64h22"
                stroke="#A7B0CA"
                stroke-width="3"
                stroke-linecap="round"
              />
            </g>
            <g class="ums-s2__product p2">
              <rect
                x="98" y="7"
                width="54" height="72"
                rx="6"
                fill="#FFFFFF"
                stroke="#D5DBEA"
              />
              <rect
                x="105" y="14"
                width="40" height="36"
                rx="4"
                fill="#E9E1CD"
              />
              <path
                d="M116 27h18v12h-18z"
                fill="#B59A69"
              />
              <path
                d="M107 58h32M107 64h24"
                stroke="#A7B0CA"
                stroke-width="3"
                stroke-linecap="round"
              />
            </g>
            <g class="ums-s2__product p3">
              <rect
                x="171" y="13"
                width="54" height="66"
                rx="6"
                fill="#FFFFFF"
                stroke="#D5DBEA"
              />
              <rect
                x="178" y="20"
                width="40" height="30"
                rx="4"
                fill="#DDEBE8"
              />
              <circle
                cx="198" cy="35" r="11"
                fill="#77A9A2"
              />
              <path
                d="M180 58h32M180 64h22"
                stroke="#A7B0CA"
                stroke-width="3"
                stroke-linecap="round"
              />
            </g>
            <!-- Scanning motion -->
            <rect
              class="ums-s2__scanner"
              x="20" y="10"
              width="2" height="69"
              rx="1"
              fill="#E3AE20"
            />
            <!-- User confusion -->
            <g class="ums-s2__question">
              <circle
                cx="125" cy="89" r="13"
                fill="#303485"
              />
              <text
                x="125" y="95"
                text-anchor="middle"
                font-size="18"
                font-weight="700"
                fill="#FFFFFF"
              >?</text>
            </g>
          </svg>
        </div>
        <div class="ums-s2__stage-heading">
          <span class="ums-s2__number">01</span>
          <span class="ums-s2__tag">MASALAH</span>
        </div>
        <h2 class="ums-s2__stage-title">
          Terlalu Banyak Pilihan
        </h2>
        <p class="ums-s2__stage-text">
          pengguna belum tentu mudah menemukan produk yang benar-benar sesuai kebutuhan dan anggaran mereka.
        </p>
      </section>
      <!-- CONNECTOR 1 -->
      <div v-click="2" class="ums-s2__connector" aria-hidden="true">
        <svg viewBox="0 0 40 24">
          <path
            d="M2 12H34"
            class="ums-s2__connector-path"
          />
          <path
            d="M28 6L35 12L28 18"
            class="ums-s2__connector-path"
          />
        </svg>
      </div>
      <!-- STAGE 02: AGENTIC ASSISTANT Ai-->
      <section v-click="2" class="ums-s2__stage">
        <div class="ums-s2__visual">
          <svg
            viewBox="0 0 250 105"
            class="ums-s2__svg"
            role="img"
            aria-label="Asisten AI memahami pertanyaan dan menggunakan katalog produk"
          >
            <!-- User message -->
            <g class="ums-s2__message-user">
              <rect
                x="18" y="12"
                width="105" height="31"
                rx="9"
                fill="#E6EAF7"
              />
              <path
                d="M34 43L27 49V43"
                fill="#E6EAF7"
              />
              <path
                d="M31 23H108M31 31H85"
                stroke="#8997C0"
                stroke-width="3"
                stroke-linecap="round"
              />
            </g>
            <!-- AI assistant node -->
            <g class="ums-s2__agent">
              <circle
                class="ums-s2__agent-halo"
                cx="127" cy="57" r="30"
                fill="none"
                stroke="#B6C1E8"
                stroke-width="1.5"
              />
              <circle
                cx="127" cy="57" r="21"
                fill="#303485"
              />
              <path
                d="M119 52L113 57L119 62
                   M135 52L141 57L135 62"
                fill="none"
                stroke="#FFFFFF"
                stroke-width="2.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M130 48L124 66"
                stroke="#FFCA42"
                stroke-width="2"
                stroke-linecap="round"
              />
            </g>
            <!-- Catalog / tool node -->
            <g class="ums-s2__catalog">
              <rect
                x="175" y="46"
                width="52" height="43"
                rx="7"
                fill="#FFFFFF"
                stroke="#A7B3D6"
              />
              <rect
                x="183" y="54"
                width="15" height="13"
                rx="2"
                fill="#CED8F1"
              />
              <path
                d="M203 56H218M203 62H214
                   M183 74H218M183 80H207"
                fill="none"
                stroke="#8D9ABC"
                stroke-width="2.5"
                stroke-linecap="round"
              />
            </g>
            <!-- Tool connection -->
            <path
              class="ums-s2__tool-line"
              d="M149 57H172"
              stroke="#D6A326"
              stroke-width="2.5"
              stroke-dasharray="4 4"
              stroke-linecap="round"
            />
            <!-- Recommendation success -->
            <g class="ums-s2__success">
              <circle
                cx="213" cy="33" r="11"
                fill="#2E947D"
              />
              <path
                d="M208 33L212 37L219 29"
                fill="none"
                stroke="#FFFFFF"
                stroke-width="2.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </g>
          </svg>
        </div>
        <div class="ums-s2__stage-heading">
          <span class="ums-s2__number">02</span>
          <span class="ums-s2__tag">PENDEKATAN</span>
        </div>
        <h2 class="ums-s2__stage-title">
          Asisten Belanja Agentic
        </h2>
        <p class="ums-s2__stage-text">
          juga bisa menggunakan fungsi aplikasi, seperti mencari produk dari katalog dan memberikan rekomendasi.
        </p>
      </section>
      <!-- CONNECTOR 2 -->
      <div v-click="3" class="ums-s2__connector" aria-hidden="true">
        <svg viewBox="0 0 40 24">
          <path
            d="M2 12H34"
            class="ums-s2__connector-path"
          />
          <path
            d="M28 6L35 12L28 18"
            class="ums-s2__connector-path"
          />
        </svg>
      </div>
      <!-- STAGE 03: LLM EVALUATION -->
      <section v-click="3" class="ums-s2__stage">
        <div class="ums-s2__visual">
          <svg
            viewBox="0 0 250 105"
            class="ums-s2__svg"
            role="img"
            aria-label="Perbandingan kinerja beberapa model bahasa"
          >
            <!-- Comparison baseline -->
            <path
              d="M24 85H225"
              stroke="#B9C2D9"
              stroke-width="1.5"
            />
            <!-- Model A -->
            <g>
              <rect
                class="ums-s2__bar bar-a"
                x="46" y="32"
                width="35" height="53"
                rx="4"
                fill="#8997C9"
              />
              <text
                x="63" y="98"
                text-anchor="middle"
                font-size="10"
                font-weight="600"
                fill="#606C8D"
              >A</text>
            </g>
            <!-- Model B -->
            <g>
              <rect
                class="ums-s2__bar bar-b"
                x="107" y="16"
                width="35" height="69"
                rx="4"
                fill="#303485"
              />
              <text
                x="124" y="98"
                text-anchor="middle"
                font-size="10"
                font-weight="600"
                fill="#606C8D"
              >B</text>
            </g>
            <!-- Model C -->
            <g>
              <rect
                class="ums-s2__bar bar-c"
                x="168" y="39"
                width="35" height="46"
                rx="4"
                fill="#6577B5"
              />
              <text
                x="185" y="98"
                text-anchor="middle"
                font-size="10"
                font-weight="600"
                fill="#606C8D"
              >C</text>
            </g>
            <!-- Comparison indicator -->
            <g class="ums-s2__chart-indicator">
              <path
                d="M39 25L65 15L126 9L188 28"
                fill="none"
                stroke="#DBA523"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-dasharray="5 4"
              />
              <circle
                cx="126" cy="9" r="4"
                fill="#DBA523"
              />
            </g>
          </svg>
        </div>
        <div class="ums-s2__stage-heading">
          <span class="ums-s2__number">03</span>
          <span class="ums-s2__tag">PENELITIAN</span>
        </div>
        <h2 class="ums-s2__stage-title">
          Kinerja LLM Berbeda-beda
        </h2>
        <p class="ums-s2__stage-text">
          Saya ingin melihat bagaimana perbedaan kinerja LLM tersebut, sekaligus bagaimana pengguna merespons bantuan yang diberikan.
        </p>
      </section>
    </div>
  </main>
  
</div>

<style scoped>
/* ============================================
   SLIDE 2 — ANIMATED EDITORIAL STORY
   Canvas 980 × 552
   ============================================ */

/* 01 — CANVAS */

.ums-s2 {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  overflow: hidden;
  isolation: isolate;

  background: #ffffff url('/13.jpg')
    center / cover no-repeat;

  color: #242867;
  font-family: 'Inter', 'Aptos', Arial, sans-serif;
}

/* 02 — HEADER */

.ums-s2__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 55px;
}

.ums-s2__section {
  display: flex;
  align-items: center;
  gap: 10px;

  margin-bottom: 8px;

  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .1em;
  color: #303485;
}

.ums-s2__section-divider {
  color: #ABB3CC;
  font-weight: 400;
}

.ums-s2__title {
  max-width: 760px;
  margin: 0;
  padding: 0;

  font-size: 26px;
  font-weight: 720;
  line-height: 1.18;
  letter-spacing: -.03em;
  color: #242867;
  text-wrap: balance;
}

.ums-s2__intro {
  max-width: 700px;
  margin: 6px 0 0;

  font-size: 11.5px;
  line-height: 1.45;
  color: #68728C;
}

/* 03 — MAIN LAYOUT */

.ums-s2__main {
  position: absolute;
  top: 204px;
  left: 55px;
  right: 55px;
  bottom: 84px;
}

.ums-s2__flow {
  display: grid;

  grid-template-columns:
    minmax(0, 1fr)
    27px
    minmax(0, 1fr)
    27px
    minmax(0, 1fr);

  column-gap: 12px;
  align-items: stretch;
}

.ums-s2__stage {
  min-width: 0;
  display: flex;
  flex-direction: column;
  padding: 14px 14px 14px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 4px 4px 0px #303485;
  border-radius: 0px;
  opacity: 1;
  transform: translateY(0);

  transition:
    opacity .65s ease,
    transform .65s cubic-bezier(.22,1,.36,1)
    !important;
}

/* Slidev sequential reveal */
.ums-s2__stage.slidev-vclick-hidden,
.ums-s2__connector.slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(18px) !important;
  pointer-events: none;
}

/* 04 — SVG VISUAL AREA */

.ums-s2__visual {
  width: 100%;
  height: 84px;
  margin-bottom: 8px;

  display: flex;
  align-items: center;
  justify-content: center;
}

.ums-s2__svg {
  display: block;
  width: 100%;
  height: 100%;
  overflow: visible;
}

/* 05 — STAGE HEADING */

.ums-s2__stage-heading {
  display: flex;
  align-items: center;
  gap: 8px;

  margin-bottom: 6px;
  padding-bottom: 6px;

  border-bottom: 2px solid #303485;
}

.ums-s2__number {
  font-size: 20px;
  font-weight: 800;
  line-height: 1;
  letter-spacing: -.03em;
  color: #303485;
}

.ums-s2__tag {
  font-size: 8px;
  font-weight: 800;
  letter-spacing: .12em;
  color: #303485;
  background: #E8EDF8;
  padding: 2px 5px;
  border: 1px solid #303485;
}

.ums-s2__stage-title {
  margin: 0;
  padding: 0;

  font-size: 15px;
  font-weight: 750;
  line-height: 1.25;
  letter-spacing: -.015em;
  color: #242867;
}

.ums-s2__stage-text {
  margin: 6px 0 0;
  flex: 1 1 auto;

  font-size: 10.5px;
  line-height: 1.45;
  color: #55627D;
  max-width: 100%;
}

.ums-s2__stage-text em {
  font-style: italic;
  font-weight: 600;
}

/* 06 — FLOW CONNECTORS */

.ums-s2__connector {
  width: 27px;
  height: 84px;

  display: flex;
  align-items: center;
  justify-content: center;
}

.ums-s2__connector svg {
  width: 100%;
  height: 24px;
}

.ums-s2__connector-path {
  fill: none;
  stroke: #B3BDD8;
  stroke-width: 2;
  stroke-linecap: round;
  stroke-linejoin: round;
}

/* 07 — TAKEAWAY */

.ums-s2__footer {
  position: absolute;
  left: 55px;
  right: 55px;
  bottom: 71px;

  display: grid;
  grid-template-columns: 135px 1fr;
  column-gap: 22px;
  align-items: start;

  padding-top: 13px;
  border-top: 1px solid #CFD4E2;

  opacity: 1;
  transform: translateY(0);

  transition:
    opacity .65s ease,
    transform .65s ease
    !important;
}

.ums-s2__footer.slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(12px) !important;
}

.ums-s2__footer-label {
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .1em;
  color: #303485;
}

.ums-s2__footer p {
  margin: 0;

  font-size: clamp(12px, 1.2vw, 14px);
  line-height: 1.5;
  color: #535D78;
}

.ums-s2__footer strong {
  font-weight: 700;
  color: #303485;
}

/* ============================================
   SVG MOTION SYSTEM
   ============================================ */

/* 08 — PRODUCT CARDS
   Gentle staggered entrance and movement */

.ums-s2__product {
  transform-box: fill-box;
  transform-origin: center;
  animation: product-float 3.6s ease-in-out infinite;
}

.ums-s2__product.p2 {
  animation-delay: -.9s;
}

.ums-s2__product.p3 {
  animation-delay: -1.8s;
}

@keyframes product-float {
  0%, 100% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-4px);
  }
}

/* Scanning available products */

.ums-s2__scanner {
  animation: scan-products 4s ease-in-out infinite;
  opacity: .65;
}

@keyframes scan-products {
  0% {
    transform: translateX(0);
    opacity: 0;
  }

  15% {
    opacity: .7;
  }

  80% {
    opacity: .7;
  }

  100% {
    transform: translateX(207px);
    opacity: 0;
  }
}

/* Question icon pulse */

.ums-s2__question {
  transform-box: fill-box;
  transform-origin: center;
  animation: question-pulse 3s ease-in-out infinite;
}

@keyframes question-pulse {
  0%, 100% {
    transform: scale(1);
  }

  50% {
    transform: scale(1.09);
  }
}

/* 09 — AI COMMUNICATION */

.ums-s2__message-user {
  animation: message-appear 3.5s ease-in-out infinite;
}

@keyframes message-appear {
  0%, 10% {
    opacity: .35;
    transform: translateY(5px);
  }

  30%, 90% {
    opacity: 1;
    transform: translateY(0);
  }

  100% {
    opacity: .35;
    transform: translateY(5px);
  }
}

.ums-s2__agent-halo {
  transform-box: fill-box;
  transform-origin: center;

  animation: agent-pulse 2.8s ease-in-out infinite;
}

@keyframes agent-pulse {
  0%, 100% {
    transform: scale(1);
    opacity: .45;
  }

  50% {
    transform: scale(1.17);
    opacity: 1;
  }
}

/* Data flow to catalog */

.ums-s2__tool-line {
  animation: tool-data-flow 1s linear infinite;
}

@keyframes tool-data-flow {
  to {
    stroke-dashoffset: -16;
  }
}

.ums-s2__success {
  transform-box: fill-box;
  transform-origin: center;

  animation: success-pop 3.5s ease-in-out infinite;
}

@keyframes success-pop {
  0%, 40% {
    opacity: 0;
    transform: scale(.5);
  }

  55%, 90% {
    opacity: 1;
    transform: scale(1);
  }

  100% {
    opacity: 0;
    transform: scale(.5);
  }
}

/* 10 — CHART ANIMATION */

.ums-s2__bar {
  transform-box: fill-box;
  transform-origin: bottom center;

  animation: chart-grow 3.8s ease-in-out infinite;
}

.ums-s2__bar.bar-a {
  animation-delay: 0s;
}

.ums-s2__bar.bar-b {
  animation-delay: .18s;
}

.ums-s2__bar.bar-c {
  animation-delay: .36s;
}

@keyframes chart-grow {
  0% {
    transform: scaleY(.08);
    opacity: .45;
  }

  30%, 80% {
    transform: scaleY(1);
    opacity: 1;
  }

  100% {
    transform: scaleY(.08);
    opacity: .45;
  }
}

.ums-s2__chart-indicator {
  animation: chart-indicator-in 3.8s ease-in-out infinite;
}

@keyframes chart-indicator-in {
  0%, 25% {
    opacity: 0;
  }

  45%, 80% {
    opacity: 1;
  }

  100% {
    opacity: 0;
  }
}

/* 11 — ACCESSIBILITY */

@media (prefers-reduced-motion: reduce) {
  .ums-s2 *,
  .ums-s2 *::before,
  .ums-s2 *::after {
    animation: none !important;
    transition: none !important;
  }

  .ums-s2__stage.slidev-vclick-hidden,
  .ums-s2__footer.slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
}
</style>
