---
layout: default
transition: fade
class: ums-background-slide
---

<!-- SLIDE 6 — ANIMATED SYSTEM ARCHITECTURE -->
<!-- Canvas: 980 x 552 | Background: /13.jpg -->
<!-- HTML kontigu, tanpa baris kosong di dalam markup. -->

<div class="ums-s6">
  <header class="ums-s6__header">
    <div class="ums-s6__section">
      <span>05 / ARSITEKTUR SISTEM</span>
    </div>
    <h1 class="ums-s6__title">Arsitektur <em>Agentic Conversational Sales Assistant</em></h1>
    <p class="ums-s6__intro">Alur interaksi pengguna, pemrosesan agen AI, dan integrasi layanan pendukung.</p>
  </header>
  <main class="ums-s6__diagram">
    <div class="ums-s6__flow">
      <!-- 01 — USER -->
      <section v-click class="ums-s6__actor">
        <div class="ums-s6__actor-illustration">
          <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Pengguna sistem">
            <circle cx="32" cy="32" r="29" fill="#EDF0F9"/>
            <circle cx="32" cy="24" r="9" fill="#8392C2"/>
            <path d="M15 48C15 38 22 35 32 35C42 35 49 38 49 48" fill="#303485"/>
            <path d="M20 51H44" stroke="#CBD4EE" stroke-width="2" stroke-linecap="round"/>
            <circle class="ums-s6__actor-status" cx="52" cy="13" r="5" fill="#D4A12A" stroke="#FFFFFF" stroke-width="2"/>
          </svg>
        </div>
        <span class="ums-s6__eyebrow">AKTOR</span>
        <h2>Pengguna</h2>
        <p>Berinteraksi dengan toko dan asisten AI</p>
      </section>
      <!-- 02 — USER TO FRONTEND -->
      <div v-click class="ums-s6__user-link">
        <svg viewBox="0 0 24 52" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path class="ums-s6__link-track" d="M1 20H22M22 32H1"/>
          <path class="ums-s6__link-forward" d="M1 20H22"/>
          <path d="M17 16L22 20L17 24" fill="none" stroke="#303485" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M6 28L1 32L6 36" fill="none" stroke="#8490B5" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <!-- FRONTEND -->
      <section v-click class="ums-s6__system ums-s6__frontend">
        <div class="ums-s6__system-head">
          <span>01 / FRONTEND</span>
          <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <rect x="3" y="4" width="18" height="16" rx="2" fill="none" stroke="#7584B6" stroke-width="1.6"/>
            <path d="M3 9H21M7 6.5H7.5M10 6.5H10.5" stroke="#7584B6" stroke-width="1.6" stroke-linecap="round"/>
            <path d="M7 13H17M7 16H13" stroke="#303485" stroke-width="1.5" stroke-linecap="round"/>
          </svg>
        </div>
        <h2>Toko <em>E-Commerce</em> Simulasi</h2>
        <p>Antarmuka bagi peserta untuk mencari, memilih, dan melakukan simulasi pembelian.</p>
        <div class="ums-s6__features">
          <span>Katalog</span>
          <span>Chat AI</span>
          <span>Keranjang</span>
          <span>Checkout</span>
        </div>
      </section>
      <!-- 03 — FRONTEND TO BACKEND: API REQUEST -->
      <div v-click="3" class="ums-s6__api">
        <span class="ums-s6__api-label">REST API</span>
        <div class="ums-s6__api-request">
          <span>REQUEST</span>
          <svg viewBox="0 0 72 17" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path class="ums-s6__api-track" d="M2 8H68"/>
            <path class="ums-s6__api-active" d="M2 8H68"/>
            <path d="M62 3L68 8L62 13" fill="none" stroke="#303485" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
            <circle class="ums-s6__packet-request" cx="3" cy="8" r="3" fill="#D5A126"/>
          </svg>
        </div>
        <div class="ums-s6__api-response" v-click="6">
          <svg viewBox="0 0 72 17" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path class="ums-s6__api-track" d="M68 8H2"/>
            <path class="ums-s6__api-active ums-s6__api-active--reverse" d="M68 8H2"/>
            <path d="M8 3L2 8L8 13" fill="none" stroke="#7888B8" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
            <circle class="ums-s6__packet-response" cx="68" cy="8" r="3" fill="#D5A126"/>
          </svg>
          <span>RESPONSE</span>
        </div>
      </div>
      <!-- 04 — BACKEND -->
      <section v-click="4" class="ums-s6__system ums-s6__backend">
        <div class="ums-s6__system-head">
          <span>02 / BACKEND</span>
          <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <rect x="7" y="7" width="10" height="10" rx="2" fill="#E4E9F7" stroke="#303485" stroke-width="1.5"/>
            <path d="M10 3V7M14 3V7M10 17V21M14 17V21M3 10H7M3 14H7M17 10H21M17 14H21" stroke="#7484B9" stroke-width="1.6" stroke-linecap="round"/>
            <circle cx="12" cy="12" r="2.5" fill="#303485"/>
          </svg>
        </div>
        <h2>Sistem Manajemen Agen AI</h2>
        <p>Mengelola alur pemrosesan, pemanggilan model, dan penggunaan <em>tools</em>.</p>
        <div class="ums-s6__features">
          <span>Prompt</span>
          <span>Orkestrasi</span>
          <span>LLM</span>
          <span>Tools</span>
        </div>
      </section>
    </div>
    <!-- 05 — BACKEND DEPENDENCIES -->
    <div v-click="5" class="ums-s6__services">
      <div class="ums-s6__services-heading">
        <span>LAYANAN YANG DIGUNAKAN AGEN</span>
        <span class="ums-s6__services-heading-rule"></span>
      </div>
      <div class="ums-s6__service-grid">
        <section class="ums-s6__service">
          <div class="ums-s6__service-icon">
            <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="LLM API">
              <circle cx="20" cy="20" r="16" fill="#E5EAF8"/>
              <path d="M14 14L9 20L14 26M26 14L31 20L26 26M23 11L17 29" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </div>
          <div class="ums-s6__service-copy">
            <span>LLM API</span>
            <strong><em>Reasoning Engine</em></strong>
            <p>Model yang diuji</p>
          </div>
        </section>
        <section class="ums-s6__service">
          <div class="ums-s6__service-icon">
            <svg viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Database produk">
              <ellipse cx="20" cy="10" rx="13" ry="5" fill="#CED8EF" stroke="#6376B0" stroke-width="1.4"/>
              <path d="M7 10V29C7 36 33 36 33 29V10" fill="#E7EBF8" stroke="#6376B0" stroke-width="1.4"/>
              <path d="M7 19C7 26 33 26 33 19M7 27C7 34 33 34 33 27" fill="none" stroke="#6376B0" stroke-width="1.4"/>
              <ellipse cx="20" cy="10" rx="13" ry="5" fill="#CED8EF" stroke="#6376B0" stroke-width="1.4"/>
            </svg>
          </div>
          <div class="ums-s6__service-copy">
            <span>DATA PRODUK</span>
            <strong>Katalog &amp; <em>Ground Truth</em></strong>
            <p>Referensi rekomendasi</p>
          </div>
        </section>
      </div>
    </div>
    <!-- 07 — EVALUATION LOGGING -->
    <section v-click="7" class="ums-s6__logging">
      <div class="ums-s6__logging-icon">
        <svg viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Pencatatan aktivitas dan evaluasi">
          <rect x="7" y="5" width="30" height="34" rx="4" fill="#E5EAF8" stroke="#7E8FBE" stroke-width="1.5"/>
          <path d="M14 15H30M14 21H26M14 27H21" fill="none" stroke="#303485" stroke-width="2" stroke-linecap="round"/>
          <path class="ums-s6__logging-mark" d="M24 30L28 34L35 25" fill="none" stroke="#D5A126" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <div class="ums-s6__logging-copy">
        <span>PENCATATAN &amp; EVALUASI</span>
        <h3>Interaksi, <em>Tool Calls</em>, dan Aktivitas Belanja</h3>
        <p>Data untuk analisis kinerja agen, <em>purchase funnel</em>, dan pengalaman pengguna.</p>
      </div>
      <div class="ums-s6__logging-status">
        <span class="ums-s6__status-dot"></span>
        DATA PENELITIAN
      </div>
    </section>
  </main>
</div>

<style scoped>
/* ===========================================
   SLIDE 6 — ANIMATED SYSTEM ARCHITECTURE
   Canvas: 980 × 552
   Background: Official UMS /13.jpg
   =========================================== */

/* 01 — CANVAS */
.ums-s6 {
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
.ums-s6,
.ums-s6 * {
  box-sizing: border-box;
}

/* 02 — HEADER */
.ums-s6__header {
  position: absolute;
  top: 80px;
  left: 55px;
  right: 55px;
}
.ums-s6__section {
  display: flex;
  align-items: center;
  margin-bottom: 5px;
  font-size: 8.5px;
  font-weight: 700;
  letter-spacing: .11em;
  color: #303485;
}
.ums-s6__title {
  margin: 0;
  padding: 0;
  font-size: 26px;
  font-weight: 720;
  line-height: 1.18;
  letter-spacing: -.032em;
  color: #242867;
}
.ums-s6__title em {
  font-weight: 500;
  font-style: italic;
}
.ums-s6__intro {
  margin: 4px 0 0;
  font-size: 11px;
  line-height: 1.4;
  color: #68728C;
}

/* 03 — ARCHITECTURE AREA */
.ums-s6__diagram {
  position: absolute;
  top: 164px;
  left: 55px;
  right: 55px;
  bottom: 84px;
}
.ums-s6__flow {
  display: grid;
  grid-template-columns: 112px 24px 282px 72px 330px;
  column-gap: 12px;
  align-items: center;
  height: 124px;
}

/* 04 — USER */
.ums-s6__actor {
  height: 124px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.ums-s6__actor-illustration {
  width: 50px;
  height: 50px;
  margin-bottom: 4px;
}
.ums-s6__actor-illustration svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s6__eyebrow {
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .1em;
  color: #8994AE;
}
.ums-s6__actor h2 {
  margin: 2px 0 0;
  font-size: 12.5px;
  font-weight: 700;
  color: #242867;
}
.ums-s6__actor p {
  margin: 2px 0 0;
  font-size: 8px;
  line-height: 1.3;
  color: #748099;
}
.ums-s6__actor-status {
  transform-box: fill-box;
  transform-origin: center;
  animation: ums-s6-status 2.8s ease-in-out infinite;
}
@keyframes ums-s6-status {
  0%, 100% { opacity: 1; transform: scale(1); }
  50% { opacity: .65; transform: scale(.85); }
}

/* 05 — USER CONNECTION */
.ums-s6__user-link {
  width: 24px;
  height: 52px;
}
.ums-s6__user-link svg {
  width: 100%;
  height: 100%;
}
.ums-s6__link-track {
  fill: none;
  stroke: #C9D1E3;
  stroke-width: 1.5;
}
.ums-s6__link-forward {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-dasharray: 22;
  stroke-dashoffset: 22;
}
.ums-s6__user-link:not(.slidev-vclick-hidden)
.ums-s6__link-forward {
  animation: ums-s6-draw-link .7s ease forwards;
}
@keyframes ums-s6-draw-link {
  to { stroke-dashoffset: 0; }
}

/* 06 — SYSTEM CARDS */
.ums-s6__system {
  height: 124px;
  min-width: 0;
  display: flex;
  flex-direction: column;
  padding: 8px 12px 8px;
  background: #FFFFFF;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
}
.ums-s6__backend {
  border-color: #303485;
}
.ums-s6__system-head {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-bottom: 4px;
  border-bottom: 1.5px solid #303485;
}
.ums-s6__system-head span {
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .09em;
  color: #303485;
}
.ums-s6__system-head svg {
  width: 18px;
  height: 18px;
}
.ums-s6__system h2 {
  margin: 4px 0 0;
  padding: 0;
  font-size: 13px;
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: -.015em;
  color: #242867;
}
.ums-s6__system h2 em {
  font-weight: 550;
  font-style: italic;
}
.ums-s6__system > p {
  margin: 3px 0 0;
  font-size: 8.5px;
  line-height: 1.3;
  color: #66718A;
}
.ums-s6__features {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 4px;
  margin-top: auto;
  padding-top: 4px;
}
.ums-s6__features span {
  padding: 1.5px 5px;
  border: 1px solid #303485;
  background: #F0F3FA;
  color: #303485;
  font-size: 7.5px;
  font-weight: 700;
  line-height: 1.1;
}

/* 07 — API COMMUNICATION */
.ums-s6__api {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 72px;
  height: 124px;
}
.ums-s6__api-label {
  margin-bottom: 7px;
  color: #303485;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: .05em;
  white-space: nowrap;
}
.ums-s6__api-request,
.ums-s6__api-response {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 72px;
  gap: 2px;
}
.ums-s6__api-request span,
.ums-s6__api-response span {
  font-size: 7.5px;
  font-weight: 700;
  color: #7582A5;
  letter-spacing: .05em;
}
.ums-s6__api-request svg,
.ums-s6__api-response svg {
  width: 72px;
  height: 17px;
  overflow: visible;
}
.ums-s6__api-response {
  margin-top: 12px;
}
.ums-s6__api-track {
  fill: none;
  stroke: #D6DDEB;
  stroke-width: 1.5;
  stroke-linecap: round;
}
.ums-s6__api-active {
  fill: none;
  stroke: #303485;
  stroke-width: 2;
  stroke-linecap: round;
  stroke-dasharray: 66;
  stroke-dashoffset: 66;
}
.ums-s6__api-active--reverse {
  stroke: #7888B8;
}
.ums-s6__api-request:not(.slidev-vclick-hidden)
.ums-s6__api-active,
.ums-s6__api-response:not(.slidev-vclick-hidden)
.ums-s6__api-active {
  animation: ums-s6-api-draw .8s ease forwards;
}
@keyframes ums-s6-api-draw {
  to { stroke-dashoffset: 0; }
}
.ums-s6__packet-request,
.ums-s6__packet-response {
  opacity: 0;
}
.ums-s6__api-request:not(.slidev-vclick-hidden)
.ums-s6__packet-request {
  animation: ums-s6-request-move 2.4s 1s ease-in-out infinite;
}
.ums-s6__api-response:not(.slidev-vclick-hidden)
.ums-s6__packet-response {
  animation: ums-s6-response-move 2.4s 1s ease-in-out infinite;
}
@keyframes ums-s6-request-move {
  0% { opacity: 0; transform: translateX(0); }
  15% { opacity: 1; }
  85% { opacity: 1; }
  100% { opacity: 0; transform: translateX(65px); }
}
@keyframes ums-s6-response-move {
  0% { opacity: 0; transform: translateX(0); }
  15% { opacity: 1; }
  85% { opacity: 1; }
  100% { opacity: 0; transform: translateX(-65px); }
}

/* 08 — BACKEND DEPENDENCIES */
.ums-s6__services {
  position: absolute;
  top: 136px;
  right: 0;
  width: 330px;
}
.ums-s6__services::before {
  content: "";
  position: absolute;
  top: -12px;
  left: 50%;
  width: 1px;
  height: 12px;
  background: #AAB6D1;
}
.ums-s6__services-heading {
  display: flex;
  align-items: center;
  gap: 9px;
  margin-bottom: 4px;
}
.ums-s6__services-heading > span:first-child {
  color: #7F8BA6;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .065em;
  white-space: nowrap;
}
.ums-s6__services-heading-rule {
  flex: 1;
  height: 1px;
  background: #D9DFEB;
}
.ums-s6__service-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0,1fr));
  gap: 10px;
}
.ums-s6__service {
  display: flex;
  align-items: center;
  gap: 8px;
  height: 48px;
  min-width: 0;
  padding: 5px 8px;
  background: #FFFFFF;
  border: 1.5px solid #303485;
  box-shadow: 2px 2px 0px #303485;
}
.ums-s6__service-icon {
  width: 24px;
  height: 24px;
  flex: 0 0 24px;
}
.ums-s6__service-icon svg {
  display: block;
  width: 100%;
  height: 100%;
}
.ums-s6__service-copy {
  min-width: 0;
}
.ums-s6__service-copy > span {
  display: block;
  margin-bottom: 1px;
  color: #7280A3;
  font-size: 6.5px;
  font-weight: 700;
  letter-spacing: .055em;
}
.ums-s6__service strong {
  display: block;
  color: #303485;
  font-size: 8.5px;
  font-weight: 650;
  line-height: 1.15;
}
.ums-s6__service strong em {
  font-style: italic;
}
.ums-s6__service p {
  margin: 1px 0 0;
  color: #78839A;
  font-size: 7px;
  line-height: 1.15;
}

/* 09 — EVALUATION LOGGING */
.ums-s6__logging {
  position: absolute;
  top: 220px;
  left: 0;
  right: 0;
  height: 46px;
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 6px 14px;
  border: 2px solid #303485;
  box-shadow: 3px 3px 0px #303485;
  background: #FFFFFF;
}
.ums-s6__logging-icon {
  width: 30px;
  height: 30px;
  flex: 0 0 30px;
}
.ums-s6__logging-icon svg {
  width: 100%;
  height: 100%;
}
.ums-s6__logging-copy {
  flex: 1 1 auto;
  min-width: 0;
}
.ums-s6__logging-copy > span {
  display: block;
  color: #6777AC;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .07em;
  line-height: 1.2;
}
.ums-s6__logging h3 {
  margin: 1px 0 0;
  padding: 0;
  color: #242867;
  font-size: 11px;
  font-weight: 700;
  line-height: 1.2;
}
.ums-s6__logging p {
  margin: 1px 0 0;
  color: #6E7993;
  font-size: 8.5px;
  line-height: 1.2;
}
.ums-s6__logging-status {
  display: flex;
  align-items: center;
  gap: 6px;
  color: #6978A5;
  font-size: 7.5px;
  font-weight: 700;
  letter-spacing: .04em;
  white-space: nowrap;
}
.ums-s6__status-dot {
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background: #303485;
}
.ums-s6__logging-mark {
  stroke-dasharray: 22;
  stroke-dashoffset: 22;
}
.ums-s6__logging:not(.slidev-vclick-hidden)
.ums-s6__logging-mark {
  animation: ums-s6-api-draw .8s .35s ease forwards;
}

/* 10 — SLIDEV REVEAL */
.ums-s6 .ums-s6__actor,
.ums-s6 .ums-s6__user-link,
.ums-s6 .ums-s6__system,
.ums-s6 .ums-s6__api,
.ums-s6 .ums-s6__api-request,
.ums-s6 .ums-s6__api-response,
.ums-s6 .ums-s6__services,
.ums-s6 .ums-s6__logging {
  opacity: 1;
  transform: translateY(0);
  transition:
    opacity .6s ease,
    transform .6s cubic-bezier(.22,1,.36,1)
    !important;
}
.ums-s6 .slidev-vclick-hidden {
  opacity: 0 !important;
  transform: translateY(10px) !important;
  pointer-events: none;
}

/* 11 — REDUCED MOTION */
@media (prefers-reduced-motion: reduce) {
  .ums-s6 *,
  .ums-s6 *::before,
  .ums-s6 *::after {
    animation: none !important;
    transition: none !important;
  }
  .ums-s6 .slidev-vclick-hidden {
    opacity: 0 !important;
    transform: none !important;
  }
  .ums-s6__link-forward,
  .ums-s6__api-active,
  .ums-s6__logging-mark {
    stroke-dashoffset: 0;
  }
}
</style>
