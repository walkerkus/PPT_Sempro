---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 8 — RANDOMIZED USER EXPERIMENT -->
<!-- Canvas 980 x 552 | Background /13.jpg -->
<!-- HTML kontigu agar aman untuk parser Slidev Markdown -->

<div class="ums-s8">
  <header class="ums-s8__header">
    <div class="ums-s8__section">
      <span>07 / EKSPERIMEN II</span>
      <span class="ums-s8__section-separator">/</span>
      <span>RANDOMIZED USER EXPERIMENT</span>
    </div>
    <h1 class="ums-s8__title">Pengujian Perilaku Pengguna dalam Toko Simulasi</h1>
    <p class="ums-s8__intro">Mengamati perilaku dan pengalaman peserta saat berbelanja dengan bantuan LLM yang dialokasikan secara acak.</p>
  </header>
  <main class="ums-s8__diagram">
    <!-- STEP 01: PARTICIPANTS -->
    <section v-click="1" class="ums-s8__participants">
      <div class="ums-s8__participant-icon">
        <svg viewBox="0 0 64 48" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Sekelompok peserta penelitian">
          <circle cx="17" cy="15" r="7" fill="#AAB6D8"/>
          <path d="M5 37C5 27 10 25 17 25C24 25 29 27 29 37" fill="#DCE3F3"/>
          <circle cx="47" cy="15" r="7" fill="#AAB6D8"/>
          <path d="M35 37C35 27 40 25 47 25C54 25 59 27 59 37" fill="#DCE3F3"/>
          <circle cx="32" cy="12" r="8" fill="#303485"/>
          <path d="M18 42C18 30 23 26 32 26C41 26 46 30 46 42" fill="#303485"/>
          <path d="M25 42H39" stroke="#FFFFFF" stroke-width="1.5" stroke-linecap="round"/>
        </svg>
      </div>
      <div class="ums-s8__participant-copy">
        <span class="ums-s8__eyebrow">01 / PARTISIPASI</span>
        <h2>Peserta Penelitian</h2>
        <p>Persetujuan partisipasi dan pemilihan kategori produk sesuai minat.</p>
      </div>
      <div class="ums-s8__participant-status">
        <svg viewBox="0 0 22 22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <circle cx="11" cy="11" r="9" fill="#E4EAF7" stroke="#8E9CC3"/>
          <path d="M6 11L9.5 14.5L16 7.5" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <span>PARTISIPASI SUKARELA</span>
      </div>
    </section>
    <!-- STEP 02: RANDOM ASSIGNMENT -->
    <section v-click="2" class="ums-s8__assignment">
      <div class="ums-s8__assignment-header">
        <div class="ums-s8__assignment-title">
          <span class="ums-s8__eyebrow">02 / ALOKASI ACAK</span>
          <h2><em>Random Assignment</em> dalam Kategori</h2>
        </div>
        <p>Setiap peserta menggunakan satu LLM selama sesi utama.</p>
      </div>
      <div class="ums-s8__random-visual">
        <svg viewBox="0 0 780 30" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path class="ums-s8__branch-base" d="M390 0V10H130V29M390 10V29M390 10H650V29"/>
          <path class="ums-s8__branch-active" d="M390 0V10H130V29M390 10V29M390 10H650V29"/>
          <circle cx="390" cy="10" r="3" fill="#303485"/>
          <circle class="ums-s8__branch-end" cx="130" cy="28" r="3" fill="#D4A12A"/>
          <circle class="ums-s8__branch-end" cx="390" cy="28" r="3" fill="#D4A12A"/>
          <circle class="ums-s8__branch-end" cx="650" cy="28" r="3" fill="#D4A12A"/>
        </svg>
      </div>
      <div class="ums-s8__models">
        <div class="ums-s8__model">
          <span class="ums-s8__model-dot"></span>
          <strong>LLM A</strong>
          <span>Kelompok A</span>
        </div>
        <div class="ums-s8__model">
          <span class="ums-s8__model-dot"></span>
          <strong>LLM B</strong>
          <span>Kelompok B</span>
        </div>
        <div class="ums-s8__model">
          <span class="ums-s8__model-dot"></span>
          <strong>LLM C</strong>
          <span>Kelompok C</span>
        </div>
      </div>
    </section>
    <!-- STEP 03: SHOPPING SESSION -->
    <section v-click="3" class="ums-s8__shopping">
      <div class="ums-s8__stage-heading">
        <span class="ums-s8__eyebrow">03 / AKTIVITAS</span>
        <h2>Sesi Belanja dalam Toko Simulasi</h2>
      </div>
      <div class="ums-s8__journey">
        <div class="ums-s8__journey-item">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Percakapan dengan asisten AI">
            <path d="M7 8H33V28H17L10 34V28H7Z" fill="#E5EAF7" stroke="#7B8BBB" stroke-width="1.5" stroke-linejoin="round"/>
            <path d="M13 16H27M13 22H23" stroke="#303485" stroke-width="2" stroke-linecap="round"/>
          </svg>
          <span>Chat AI</span>
        </div>
        <span class="ums-s8__journey-arrow">→</span>
        <div class="ums-s8__journey-item">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Mencari produk">
            <circle cx="17" cy="17" r="10" fill="#E5EAF7" stroke="#7B8BBB" stroke-width="1.5"/>
            <path d="M24 24L34 34" stroke="#303485" stroke-width="2.5" stroke-linecap="round"/>
            <path d="M12 17H22M17 12V22" stroke="#8A99C2" stroke-width="1.4"/>
          </svg>
          <span>Cari Produk</span>
        </div>
        <span class="ums-s8__journey-arrow">→</span>
        <div class="ums-s8__journey-item">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Membandingkan produk">
            <rect x="5" y="8" width="13" height="23" rx="2" fill="#DCE3F3" stroke="#7B8BBB" stroke-width="1.3"/>
            <rect x="22" y="8" width="13" height="23" rx="2" fill="#E5EAF7" stroke="#7B8BBB" stroke-width="1.3"/>
            <path d="M9 15H14M9 20H14M26 15H31M26 20H31" stroke="#303485" stroke-width="1.5" stroke-linecap="round"/>
          </svg>
          <span>Bandingkan</span>
        </div>
        <span class="ums-s8__journey-arrow">→</span>
        <div class="ums-s8__journey-item">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Menambahkan barang ke keranjang">
            <path d="M5 9H10L15 28H32L36 15H12" fill="#E5EAF7" stroke="#7B8BBB" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"/>
            <circle cx="18" cy="33" r="2.5" fill="#303485"/>
            <circle cx="30" cy="33" r="2.5" fill="#303485"/>
            <path d="M24 15V24M20 20H28" stroke="#303485" stroke-width="1.8" stroke-linecap="round"/>
          </svg>
          <span>Add-to-Cart</span>
        </div>
        <span class="ums-s8__journey-arrow">→</span>
        <div class="ums-s8__journey-item">
          <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Checkout simulasi">
            <rect x="6" y="7" width="28" height="27" rx="4" fill="#E5EAF7" stroke="#7B8BBB" stroke-width="1.5"/>
            <path d="M6 14H34" stroke="#7B8BBB" stroke-width="1.5"/>
            <path d="M13 24L18 29L28 19" fill="none" stroke="#303485" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span>Checkout</span>
        </div>
      </div>
      <p class="ums-s8__shopping-note">Tahapan belanja dapat dilewati; peserta tidak diwajibkan melakukan checkout.</p>
    </section>
    <!-- STEP 04: END-OF-SESSION SURVEY -->
    <section v-click="4" class="ums-s8__survey">
      <div class="ums-s8__survey-copy">
        <span class="ums-s8__eyebrow">04 / PENILAIAN</span>
        <h2>Kuesioner Akhir</h2>
        <p>Kualitas jawaban · Kepuasan · Kepercayaan · Keyakinan keputusan · Niat membeli</p>
      </div>
      <div class="ums-s8__rating">
        <span>SKALA 1–5</span>
        <div class="ums-s8__rating-scale">
          <div>1</div>
          <div>2</div>
          <div>3</div>
          <div>4</div>
          <div>5</div>
        </div>
      </div>
    </section>
    <!-- STEP 05: CONTINUOUS OBSERVATION -->
    <section v-click="5" class="ums-s8__observation">
      <div class="ums-s8__observation-icon">
        <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Pencatatan aktivitas pengguna">
          <rect x="8" y="5" width="25" height="31" rx="4" fill="#E4EAF7" stroke="#7B8BBB" stroke-width="1.5"/>
          <path d="M14 14H27M14 20H25M14 26H22" stroke="#303485" stroke-width="2" stroke-linecap="round"/>
          <circle class="ums-s8__record-dot" cx="30" cy="9" r="4" fill="#D4A12A"/>
        </svg>
      </div>
      <div class="ums-s8__observation-copy">
        <strong>Pencatatan Aktivitas</strong>
        <p>Sistem merekam interaksi dan tindakan peserta sepanjang sesi, termasuk ketika tidak terjadi add-to-cart atau checkout.</p>
      </div>
    </section>
  </main>
</div>

<style scoped>
/* ==============================================
   SLIDE 8 — ANIMATED RANDOMIZED USER JOURNEY
   Canvas: 980 × 552
   Background: Official UMS /13.jpg
   ============================================== */

/* 01 — CANVAS */
.ums-s8 {
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
.ums-s8,
.ums-s8 * {
  box-sizing: border-box;
}

/* 02 — HEADER */
.ums-s8__header {
  position: absolute;
  top: 86px;
  left: 55px;
  right: 55px;
}
.ums-s8__section {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 8px;
  color: #303485;
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .1em;
}
.ums-s8__section-separator {
  color: #ADB5CA;
  font-weight: 400;
}
.ums-s8__title {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 27px;
  font-weight: 720;
  line-height: 1.18;
  letter-spacing: -.032em;
}
.ums-s8__intro {
  margin: 7px 0 0;
  color: #68728C;
  font-size: 11.5px;
  line-height: 1.45;
}

/* 03 — DIAGRAM CANVAS */
.ums-s8__diagram {
  position: absolute;
  top: 184px;
  left: 70px;
  width: 1135px;
  transform: scale(.71);
  transform-origin: top left;
}
.ums-s8__eyebrow {
  display: block;
  margin-bottom: 3px;
  color: #303485;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .085em;
  line-height: 1.2;
}

/* 04 — PARTICIPANTS */
.ums-s8__participants {
  width: 100%;
  min-height: 64px;
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 10px 18px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s8__participant-icon {
  width: 52px;
  height: 40px;
  flex: 0 0 52px;
}
.ums-s8__participant-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s8__participant-copy {
  flex: 1 1 auto;
  min-width: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.ums-s8__participant-copy h2 {
  margin: 0;
  padding: 0;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.25;
  color: #242867;
}
.ums-s8__participant-copy p {
  margin: 3px 0 0;
  font-size: 10px;
  line-height: 1.35;
  color: #68748D;
}
.ums-s8__participant-status {
  display: flex;
  align-items: center;
  gap: 5px;
  color: #7785A4;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .045em;
  white-space: nowrap;
}
.ums-s8__participant-status svg {
  width: 19px;
  height: 19px;
}

/* 05 — RANDOM ASSIGNMENT */
.ums-s8__assignment {
  margin-top: 9px;
}
.ums-s8__assignment-header {
  display: flex;
  justify-content: space-between;
  align-items: end;
  gap: 12px;
}
.ums-s8__assignment h2 {
  margin: 0;
  padding: 0;
  color: #242867;
  font-size: 13px;
  font-weight: 700;
  line-height: 1.2;
}
.ums-s8__assignment h2 em {
  font-style: italic;
  font-weight: 600;
}
.ums-s8__assignment-header > p {
  margin: 0 0 1px;
  font-size: 9px;
  color: #7A859D;
}
.ums-s8__random-visual {
  height: 22px;
  width: 100%;
  margin-top: 3px;
}
.ums-s8__random-visual svg {
  display: block;
  width: 100%;
  height: 22px;
  overflow: visible;
}
.ums-s8__branch-base {
  fill: none;
  stroke: #D6DEEC;
  stroke-width: 1.4;
}
.ums-s8__branch-active {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 1000;
  stroke-dashoffset: 1000;
}
.ums-s8__assignment:not(.slidev-vclick-hidden)
.ums-s8__branch-active {
  animation: ums-s8-branch 1.15s ease forwards;
}
@keyframes ums-s8-branch {
  to { stroke-dashoffset: 0; }
}
.ums-s8__branch-end {
  transform-box: fill-box;
  transform-origin: center;
}
.ums-s8__assignment:not(.slidev-vclick-hidden)
.ums-s8__branch-end {
  animation: ums-s8-node .45s .7s ease both;
}
@keyframes ums-s8-node {
  from { opacity: 0; transform: scale(.3); }
  to { opacity: 1; transform: scale(1); }
}

/* 06 — LLM GROUPS */
.ums-s8__models {
  display: grid;
  grid-template-columns: repeat(3, minmax(0,1fr));
  gap: 12px;
}
.ums-s8__model {
  height: 39px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  padding: 6px 10px;
  border: 1.5px solid #303485;
  box-shadow: 2px 2px 0px #303485;
  background: #FFFFFF;
}
.ums-s8__model-dot {
  width: 8px;
  height: 8px;
  flex: 0 0 8px;
  border-radius: 50%;
  background: #303485;
}
.ums-s8__model strong {
  font-size: 12px;
  font-weight: 700;
  color: #303485;
}
.ums-s8__model > span:last-child {
  margin-left: auto;
  color: #8A95AB;
  font-size: 9px;
}
.ums-s8__assignment:not(.slidev-vclick-hidden)
.ums-s8__model {
  animation: ums-s8-group-enter .5s ease both;
}
.ums-s8__model:nth-child(1) {
  animation-delay: .2s;
}
.ums-s8__model:nth-child(2) {
  animation-delay: .35s;
}
.ums-s8__model:nth-child(3) {
  animation-delay: .5s;
}
@keyframes ums-s8-group-enter {
  from { opacity: 0; transform: translateY(6px); }
  to { opacity: 1; transform: translateY(0); }
}

/* 07 — SHOPPING ACTIVITY */
.ums-s8__shopping {
  margin-top: 12px;
  padding: 10px 14px 8px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s8__stage-heading h2 {
  margin: 0;
  padding: 0;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.2;
  color: #242867;
}
.ums-s8__journey {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 8px;
  margin-top: 7px;
}
.ums-s8__journey-item {
  flex: 1 1 0;
  min-width: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 7px;
}
.ums-s8__journey-item svg {
  width: 30px;
  height: 30px;
  flex: 0 0 30px;
}
.ums-s8__journey-item span {
  color: #4E5C80;
  font-size: 10px;
  font-weight: 600;
  white-space: nowrap;
}
.ums-s8__journey-arrow {
  color: #9DA9C5;
  font-size: 15px;
  font-weight: 400;
}
.ums-s8__shopping-note {
  margin: 7px 0 0;
  color: #8993A9;
  font-size: 8.5px;
  line-height: 1.3;
}
.ums-s8__shopping:not(.slidev-vclick-hidden)
.ums-s8__journey-item {
  animation: ums-s8-item-in .6s ease both;
}
.ums-s8__shopping:not(.slidev-vclick-hidden)
.ums-s8__journey-item:nth-of-type(1) {
  animation-delay: .15s;
}
.ums-s8__shopping:not(.slidev-vclick-hidden)
.ums-s8__journey-item:nth-of-type(2) {
  animation-delay: .30s;
}
.ums-s8__shopping:not(.slidev-vclick-hidden)
.ums-s8__journey-item:nth-of-type(3) {
  animation-delay: .45s;
}
.ums-s8__shopping:not(.slidev-vclick-hidden)
.ums-s8__journey-item:nth-of-type(4) {
  animation-delay: .60s;
}
.ums-s8__shopping:not(.slidev-vclick-hidden)
.ums-s8__journey-item:nth-of-type(5) {
  animation-delay: .75s;
}
@keyframes ums-s8-item-in {
  from { opacity: 0; transform: translateY(7px); }
  to { opacity: 1; transform: translateY(0); }
}

/* 08 — SURVEY */
.ums-s8__survey {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  margin-top: 10px;
  min-height: 55px;
  padding: 8px 14px;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  background: #FFFFFF;
}
.ums-s8__survey-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s8__survey h2 {
  margin: 0;
  padding: 0;
  font-size: 13px;
  font-weight: 700;
  color: #242867;
}
.ums-s8__survey-copy p {
  margin: 4px 0 0;
  color: #66718A;
  font-size: 9.5px;
  line-height: 1.3;
}
.ums-s8__rating {
  flex: 0 0 190px;
}
.ums-s8__rating > span {
  display: block;
  margin-bottom: 6px;
  text-align: center;
  color: #6978A6;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .08em;
}
.ums-s8__rating-scale {
  display: grid;
  grid-template-columns: repeat(5,1fr);
  gap: 4px;
}
.ums-s8__rating-scale div {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 23px;
  border: 1px solid #CFD7E9;
  background: #F2F4FB;
  color: #303485;
  font-size: 10px;
  font-weight: 700;
}
.ums-s8__survey:not(.slidev-vclick-hidden)
.ums-s8__rating-scale div {
  animation: ums-s8-rating-in .4s ease both;
}
.ums-s8__rating-scale div:nth-child(1) { animation-delay: .15s; }
.ums-s8__rating-scale div:nth-child(2) { animation-delay: .25s; }
.ums-s8__rating-scale div:nth-child(3) { animation-delay: .35s; }
.ums-s8__rating-scale div:nth-child(4) { animation-delay: .45s; }
.ums-s8__rating-scale div:nth-child(5) { animation-delay: .55s; }
@keyframes ums-s8-rating-in {
  from { opacity: 0; transform: translateY(5px); }
  to { opacity: 1; transform: translateY(0); }
}

/* 09 — OBSERVATION */
.ums-s8__observation {
  display: flex;
  align-items: center;
  gap: 11px;
  margin-top: 9px;
  padding: 6px 12px;
  min-height: 46px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s8__observation-icon {
  width: 35px;
  height: 35px;
  flex: 0 0 35px;
}
.ums-s8__observation-icon svg {
  width: 100%;
  height: 100%;
}
.ums-s8__observation-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s8__observation strong {
  display: block;
  color: #303485;
  font-size: 10.5px;
  font-weight: 700;
}
.ums-s8__observation p {
  margin: 3px 0 0;
  color: #66718A;
  font-size: 9px;
  line-height: 1.3;
}
.ums-s8__record-dot {
  transform-box: fill-box;
  transform-origin: center;
  animation: ums-s8-record 2s ease-in-out infinite;
}
@keyframes ums-s8-record {
  0%, 100% { opacity: 1; transform: scale(1); }
  50% { opacity: .4; transform: scale(.75); }
}

/* 10 — CLICK REVEAL */
.ums-s8__participants,
.ums-s8__assignment,
.ums-s8__shopping,
.ums-s8__survey,
.ums-s8__observation {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .6s ease,
    transform .6s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s8 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(10px) !important;
  pointer-events: none;
}

/* 11 — ACCESSIBILITY */
@media (prefers-reduced-motion: reduce) {
  .ums-s8 *,
  .ums-s8 *::before,
  .ums-s8 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s8 .slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
  .ums-s8__branch-active {
    stroke-dashoffset: 0;
  }
}
</style>
