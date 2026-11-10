---
layout: default
transition: fade
class: ums-cover-slide
---

<!-- SLIDE 1 — ANIMATED ACADEMIC COVER -->
<!-- Canvas: 980 x 552 | Background: /1.1.jpg -->
<!-- HTML kontigu agar kompatibel dengan Slidev Markdown -->

<div class="ums-cover">
  <main class="ums-cover__main">
    <!-- PRESENTATION IDENTIFIER -->
    <header class="ums-cover__header">
      <div class="ums-cover__category">
        <span>PROPOSAL SKRIPSI</span>
        <span class="ums-cover__separator">/</span>
        <span>TEKNIK INFORMATIKA</span>
      </div>
    </header>
    <!-- RESEARCH TITLE -->
    <section class="ums-cover__content">
      <h1 class="ums-cover__title">
        Perbandingan Kinerja
        <em>Large Language Models</em>
        sebagai <em>Reasoning Engine</em>
        pada <em>Agentic Conversational Sales Assistant</em>
      </h1>
      <h2 class="ums-cover__subtitle">
        Analisis Kinerja Agen dan
        <em>Purchase Funnel</em>
        dalam <em>E-Commerce</em>
      </h2>
      <div class="ums-cover__accent" aria-hidden="true"></div>
    </section>
    <!-- AUTHOR AND SUPERVISOR -->
    <footer class="ums-cover__identity">
      <div class="ums-cover__person ums-cover__person--author">
        <span class="ums-cover__label">DISUSUN OLEH</span>
        <p class="ums-cover__name">Muhammad Syahid Kusasih</p>
        <p class="ums-cover__meta">L200230272 <span class="ums-cover__meta-divider">·</span> Teknik Informatika <span class="ums-cover__meta-divider">·</span> 2026</p>
      </div>
      <div class="ums-cover__person ums-cover__person--supervisor">
        <span class="ums-cover__label">DOSEN PEMBIMBING</span>
        <p class="ums-cover__name">Helmi Imaduddin, S.Kom., M.Eng.</p>
        <p class="ums-cover__meta">Universitas Muhammadiyah Surakarta</p>
      </div>
    </footer>
  </main>
</div>

<style scoped>
/* ==============================================
   SLIDE 1 — ANIMATED ACADEMIC COVER
   Canvas: 980 x 552
   Background: Official UMS /1.1.jpg

   Design principles:
   - Institutional and academic
   - Restrained typography
   - Consistent vertical rhythm
   - Subtle entrance animation
   - No decorative clutter
   ============================================== */

/* 01 — CANVAS */
.ums-cover {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  overflow: hidden;
  isolation: isolate;
  background-color: #303485;
  background-image: url('/1.1.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color: #FFFFFF;
  font-family: 'Inter', 'Aptos', Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
}

.ums-cover,
.ums-cover * {
  box-sizing: border-box;
}

/* 02 — MAIN CONTENT AREA */
.ums-cover__main {
  position: absolute;
  top: 104px;
  right: 51px;
  bottom: 132px;
  left: 51px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  min-width: 0;
}

/* 03 — PRESENTATION IDENTIFIER */
.ums-cover__header {
  width: 100%;
  flex: 0 0 auto;
}

.ums-cover__category {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 0;
  padding: 0;
  font-size: 10px;
  font-weight: 600;
  line-height: 1.5;
  letter-spacing: .09em;
  color: #DCE1F7;
}

.ums-cover__separator {
  color: #AEB6E8;
  font-weight: 400;
}

/* 04 — TITLE CONTENT AREA */
.ums-cover__content {
  width: 100%;
  max-width: 800px;
  min-width: 0;
  margin-top: 21px;
}

/* 05 — MAIN RESEARCH TITLE */
.ums-cover__title {
  width: 100%;
  max-width: 800px;
  margin: 0;
  padding: 0;
  color: #FFFFFF;
  font-size: 29px;
  font-weight: 700;
  line-height: 1.17;
  letter-spacing: -.027em;
  text-wrap: balance;
  text-shadow: none;
}

.ums-cover__title em {
  font-style: italic;
  font-weight: 600;
  color: inherit;
}

/* 06 — RESEARCH SUBTITLE */
.ums-cover__subtitle {
  max-width: 770px;
  margin: 16px 0 0;
  padding: 0;
  color: #DBE1F7;
  font-size: 14px;
  font-weight: 400;
  line-height: 1.5;
  letter-spacing: -.005em;
  text-wrap: pretty;
}

.ums-cover__subtitle em {
  font-style: italic;
  font-weight: 400;
  color: #FFFFFF;
}

/* 07 — SUBTLE ACADEMIC ACCENT */
.ums-cover__accent {
  width: 72px;
  height: 2px;
  margin-top: 13px;
  background: #F0C64D;
  border-radius: 1px;
  transform-origin: left center;
}

/* 08 — AUTHOR AND SUPERVISOR */
.ums-cover__identity {
  width: 100%;
  display: grid;
  grid-template-columns: minmax(0,1fr) minmax(0,1fr);
  column-gap: 42px;
  margin-top: auto;
  padding-top: 12px;
  border-top: 1px solid rgba(255,255,255,.24);
}

.ums-cover__person {
  min-width: 0;
}

.ums-cover__label {
  display: block;
  margin-bottom: 6px;
  color: #CBD2F2;
  font-size: 9px;
  font-weight: 600;
  line-height: 1.35;
  letter-spacing: .1em;
}

.ums-cover__name {
  margin: 0;
  padding: 0;
  color: #FFFFFF;
  font-size: 13.5px;
  font-weight: 650;
  line-height: 1.3;
  letter-spacing: -.012em;
}

.ums-cover__meta {
  margin: 5px 0 0;
  padding: 0;
  color: #DCE1F7;
  font-size: 10px;
  font-weight: 400;
  line-height: 1.4;
}

.ums-cover__meta-divider {
  display: inline-block;
  margin: 0 3px;
  color: #AEB6E8;
}

/* ==============================================
   ENTRANCE ANIMATION SYSTEM
   All animations run once.
   ============================================== */

/* 09 — HEADER ENTRANCE */
.ums-cover__header {
  animation: ums-cover-enter .65s .08s ease-out both;
}

/* 10 — TITLE ENTRANCE */
.ums-cover__title {
  animation: ums-cover-title-in .85s .22s
    cubic-bezier(.22,1,.36,1) both;
}

/* 11 — SUBTITLE ENTRANCE */
.ums-cover__subtitle {
  animation: ums-cover-enter .7s .48s ease-out both;
}

/* 12 — ACCENT LINE DRAW */
.ums-cover__accent {
  animation: ums-cover-accent-in .65s .78s
    cubic-bezier(.22,1,.36,1) both;
}

/* 13 — IDENTITY DIVIDER */
.ums-cover__identity {
  animation: ums-cover-border-in .7s .85s ease-out both;
}

/* 14 — AUTHOR ENTRANCE */
.ums-cover__person--author {
  animation: ums-cover-enter .65s .95s ease-out both;
}

/* 15 — SUPERVISOR ENTRANCE */
.ums-cover__person--supervisor {
  animation: ums-cover-enter .65s 1.08s ease-out both;
}

/* ==============================================
   KEYFRAMES
   ============================================== */

@keyframes ums-cover-enter {
  from {
    opacity: 0;
    transform: translateY(8px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes ums-cover-title-in {
  from {
    opacity: 0;
    transform: translateY(13px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes ums-cover-accent-in {
  from {
    opacity: 0;
    transform: scaleX(0);
  }
  to {
    opacity: 1;
    transform: scaleX(1);
  }
}

@keyframes ums-cover-border-in {
  from {
    border-top-color: transparent;
  }
  to {
    border-top-color: rgba(255,255,255,.24);
  }
}

/* 16 — REDUCED MOTION */
@media (prefers-reduced-motion: reduce) {
  .ums-cover *,
  .ums-cover *::before,
  .ums-cover *::after {
    animation: none !important;
    transition: none !important;
  }
}
</style>
