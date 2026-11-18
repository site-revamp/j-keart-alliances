<!DOCTYPE html>
<html lang="en-SG">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>J.Keart Alliances | Fire Protection & Safety Engineering Singapore</title>
  <meta name="description" content="J.Keart Alliances provides fire protection engineering, SCDF submissions, Fire Certificate renewals, fire equipment maintenance and fire safety services in Singapore. Established in 1988.">
  <meta name="robots" content="index,follow">
  <meta name="theme-color" content="#171A2F">
  <link rel="canonical" href="https://jkeart.com/">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <meta property="og:type" content="website">
  <meta property="og:title" content="J.Keart Alliances | Fire Protection Engineering">
  <meta property="og:description" content="Fire protection systems, maintenance and fire-safety services in Singapore. Protecting lives since 1988.">
  <meta property="og:url" content="https://jkeart.com/">

  <style>
:root {
  --indigo: #262262;
  --orange: #F05828;
  --orange-hover: #FF7952;
  --orange-ink: #AC3516;
  --navy: #171A2F;
  --ink: #14162B;
  --slate: #4B5063;
  --line: #DAD9DF;
  --mist: #F5F3F0;
  --white: #FFF;
  --display: "Manrope", Arial, sans-serif;
  --body: "DM Sans", Arial, sans-serif;
  --mono: ui-monospace, "Cascadia Mono", Consolas, monospace;
  --max: 1240px;
  --gutter: 24px;
  --nav-height: 76px;
  --mobile-bar: 70px;
}

*, *::before, *::after { box-sizing: border-box; }
html { scroll-behavior: smooth; scroll-padding-top: calc(var(--nav-height) + 16px); }
body { margin: 0; color: var(--ink); background: var(--white); font: 16px/1.65 var(--body); }
h1, h2, h3, p, figure, blockquote { margin: 0; }
h1, h2, h3 { font-family: var(--display); line-height: 1.1; letter-spacing: -.045em; }
h1 { font-size: clamp(42px, 5.75vw, 89px); font-weight: 800; }
h2 { font-size: clamp(32px, 4.6vw, 62px); font-weight: 800; }
h3 { font-size: clamp(22px, 2.15vw, 31px); font-weight: 800; }
a { color: inherit; text-decoration: none; }
img { display: block; max-width: 100%; }
button { font: inherit; }
[hidden] { display: none !important; }
:focus-visible { outline: 2px solid currentColor; outline-offset: 5px; }
section:focus { outline: none; }
.wrap { width: min(var(--max), calc(100% - 2 * var(--gutter))); margin-inline: auto; }
.section { padding-block: clamp(60px, 8vw, 118px); }
.section--mist { background: var(--mist); }
.section--warm { background: #FBF9F7; }

.eyebrow, .service-category, .diagram-key, .pathway-label {
  display: inline-block;
  font: 700 .72rem/1.4 var(--mono);
  letter-spacing: .085em;
  text-transform: uppercase;
}
.eyebrow { color: var(--orange-ink); margin-bottom: 15px; }
.eyebrow::before { content: ""; display: inline-block; width: 16px; height: 2px; background: currentColor; margin: 0 9px .22em 0; }
.lead { font-size: clamp(16px, 1.65vw, 19px); color: var(--slate); }
.section-head { max-width: 760px; margin-bottom: clamp(26px, 4.7vw, 52px); }
.section-head .lead { max-width: 58ch; margin-top: 16px; }

.btn {
  display: inline-flex; align-items: center; justify-content: center; gap: 12px;
  min-height: 52px; max-width: 100%; padding: 11px 17px;
  border: 1px solid transparent; border-radius: 4px;
  font: 800 .91rem/1.25 var(--display); text-align: center;
  transition: color .2s ease, background .2s ease, border-color .2s ease;
}
.btn--orange { background: var(--orange); color: var(--navy); }
.btn--orange:hover { background: var(--orange-hover); }
.btn--orange:focus-visible { outline-color: #A33319; }
.hero .btn--orange:focus-visible, #credentials .btn--orange:focus-visible, .contact .btn--orange:focus-visible { outline-color: #FFA185; }
.btn--light { background: var(--white); border-color: #B9B7C4; color: var(--indigo); }
.btn--light:hover { border-color: var(--indigo); background: #F1EFF8; }
.btn--outline { color: white; border-color: #A29FB7; }
.btn--outline:hover { background: #FFFFFF17; color: white; }
.arrow { flex: none; font-size: 1.2em; line-height: 1; }
.text-link { display: inline-flex; align-items: center; gap: 8px; min-height: 44px; width: fit-content; max-width: 100%; color: var(--indigo); font-weight: 800; line-height: 1.35; }
.text-link:hover { text-decoration: underline; text-underline-offset: 4px; }
.text-link span { color: var(--orange-ink); }

.header { position: sticky; top: 0; z-index: 10; background: white; border-bottom: 1px solid var(--line); }
.nav { min-height: var(--nav-height); display: flex; align-items: center; justify-content: space-between; gap: 20px; }
.brand, .footer-brand { display: inline-flex; align-items: center; gap: 9px; flex: none; color: var(--indigo); font: 800 15px/1.15 var(--display); }

.nav-links { display: flex; align-items: center; gap: clamp(12px, 2vw, 30px); }
.nav-links a { color: var(--ink); font-weight: 700; line-height: 1.3; }
.nav-links a:hover { text-decoration: underline; text-decoration-color: var(--orange); text-decoration-thickness: 2px; text-underline-offset: 6px; }
.nav-cta { flex: none; min-height: 44px; }
.menu-toggle { display: none; width: 44px; height: 44px; padding: 0; border: 1px solid var(--line); border-radius: 4px; background: var(--white); color: var(--indigo); font-size: 24px; cursor: pointer; }

.hero {
  position: relative; overflow: hidden; isolation: isolate; color: white; background: var(--navy);
  background-image: radial-gradient(ellipse at 91% 45%, #312D67 0%, #191B33 54%, #14162A 85%);
}
.hero-grid {
  display: grid; grid-template-columns: minmax(0, 1.15fr) minmax(0, .85fr); align-items: center;
  gap: clamp(26px, 4vw, 62px); min-height: clamp(570px, 56vw, 760px); padding-block: 64px;
}
.hero .eyebrow, #credentials .eyebrow, .contact .eyebrow { color: #FFA185; }
.hero h1 { max-width: 15ch; }
.hero h1 span { color: var(--orange-hover); }
.hero-copy { margin-top: 22px; max-width: 54ch; color: #E0DDEA; font-size: clamp(16px, 1.6vw, 19px); }
.hero-actions, .contact-actions { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 27px; }
.hero-proof { display: flex; flex-wrap: wrap; gap: 8px 18px; margin-top: 25px; padding-top: 15px; border-top: 1px solid #FFFFFF38; color: #D1CEE0; font-size: 13px; }
.hero-proof strong { color: #FFF; }
.hero-visual { min-width: 0; }
.proof-ribbon { background: var(--orange); color: var(--navy); }
.proof-ribbon-inner { display: flex; align-items: center; justify-content: space-between; gap: 14px 25px; min-height: 66px; padding-block: 12px; }
.proof-ribbon strong { font: 800 clamp(17px, 2vw, 23px)/1.2 var(--display); }
.proof-ribbon span { font-weight: 700; }
.intro-grid, .record-layout, .credentials, .faq-layout, .contact-layout {
  display: grid; grid-template-columns: minmax(0, .95fr) minmax(0, 1.05fr);
  gap: clamp(28px, 6.4vw, 84px); align-items: start;
}
.intro-statement { border-left: 2px solid var(--orange); padding-left: clamp(16px, 3vw, 35px); }
.intro-statement > p + p { margin-top: 17px; color: var(--slate); }
.intro-note { margin-top: 18px; font-weight: 800; color: var(--indigo); }

.services-intro { display: flex; align-items: end; justify-content: space-between; gap: 20px; margin-bottom: clamp(24px, 4.1vw, 45px); }
.services-intro .section-head { margin: 0; }
.services-intro > .btn { flex: none; }
.service-grid {
  display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 1px;
  background: #CFCED8; border: 1px solid #CFCED8; border-radius: 5px; overflow: hidden;
}
.service-item { display: flex; flex-direction: column; align-items: start; min-width: 0; padding: clamp(21px, 3vw, 35px); background: white; border-top: 3px solid transparent; }
.service-item:first-child { border-top-color: var(--orange); background: var(--indigo); color: white; }
.service-item:first-child p { color: #E8E5F5; }
.service-item:first-child .text-link, .service-item:first-child .service-category { color: #FFF; }
.service-item:first-child .text-link span { color: #FFA185; }
.service-item:focus-within { border-top-color: var(--orange); }
.service-top { display: flex; align-items: center; justify-content: space-between; align-self: stretch; gap: 10px; margin-bottom: 22px; }
.service-category { color: var(--orange-ink); }
.service-icon { width: 48px; height: 48px; flex: none; color: var(--indigo); fill: none; stroke: currentColor; stroke-width: 2.1; stroke-linecap: round; stroke-linejoin: round; }
.service-item:first-child .service-icon { color: #FFA185; }
.service-item h3 { letter-spacing: -.035em; }
.service-item p { color: var(--slate); margin-top: 11px; margin-bottom: 16px; }
.service-item .text-link { margin-top: auto; }

.pathways { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 15px; }
.pathway { display: flex; flex-direction: column; align-items: start; padding: clamp(24px, 4vw, 47px); border: 1px solid #D1CEDB; border-radius: 5px; background: #F4F1F9; color: var(--ink); }
.pathway:nth-child(2) { background: var(--indigo); color: white; border-color: var(--indigo); }
.pathway-label { color: var(--orange-ink); }
.pathway:nth-child(2) .pathway-label { color: #FFA185; }
.pathway h3 { max-width: 20ch; margin-top: 14px; font-size: clamp(25px, 3vw, 41px); }
.pathway p { max-width: 45ch; margin: 14px 0 21px; color: var(--slate); }
.pathway:nth-child(2) p { color: #E6E2F4; }
.pathway .text-link { margin-top: auto; padding: 7px 12px; border: 1px solid #8A849F; border-radius: 4px; }
.pathway:nth-child(2) .text-link { color: white; }
.pathway:nth-child(2) .text-link span { color: #FFA185; }
@media (min-width: 521px) {
  @supports (grid-template-rows: subgrid) {
    .pathways { row-gap: 0; }
    .pathway { display: grid; grid-row: span 4; grid-template-rows: subgrid; justify-items: start; }
  }
}

.record-intro p, .faq-intro p { margin-top: 16px; color: var(--slate); }
.record-link, .credential-copy .btn { margin-top: 23px; }
.record-list { border-top: 2px solid var(--indigo); }
.record-row { display: grid; grid-template-columns: 57px minmax(0, 1fr); align-items: baseline; gap: 12px; padding: 15px 0; border-bottom: 1px solid #D9D5D1; }
.record-year { color: var(--orange-ink); font: 800 .86rem/1.4 var(--mono); }
.record-row strong { display: block; color: var(--navy); font: 800 1.02rem/1.4 var(--display); }
.record-row div > span { display: block; color: var(--slate); font-size: .86rem; }

#credentials { background: var(--navy); color: white; border-top: 3px solid var(--orange); }
.credential-copy p, .credential-note { color: #DAD8E8; margin-top: 15px; }
.credential-list { border: 1px solid #555573; border-radius: 5px; background: #FFFFFF08; }
.credential-row { display: grid; grid-template-columns: minmax(0, 1fr) minmax(0, 1.15fr); gap: 8px 13px; align-items: baseline; padding: 14px 17px; border-bottom: 1px solid #555573; }
.credential-row strong { font: 800 1rem/1.4 var(--display); }
.credential-row span, .credential-note { color: #DAD8E8; font-size: .89rem; }
.credential-note { margin: 0; padding: 13px 17px; }

.faq-layout { align-items: start; }
.faq-list { border-block: 1px solid #C5C2CB; }
.faq-item + .faq-item { border-top: 1px solid #C5C2CB; }
.faq-question { width: 100%; display: flex; align-items: center; justify-content: space-between; gap: 16px; min-height: 58px; padding: 13px 5px; border: 0; background: transparent; text-align: left; color: var(--ink); font: 800 1rem/1.45 var(--display); cursor: pointer; }
.faq-question:focus-visible { outline-offset: -2px; }
.faq-question span:last-child { color: var(--orange-ink); flex: none; font: 700 22px/1 var(--mono); }
.faq-answer { color: var(--slate); padding: 0 30px 16px 5px; }

.contact { background: var(--indigo); color: white; }
.contact-layout { align-items: center; }
.contact-copy p { color: #E8E5F5; margin-top: 17px; max-width: 55ch; }
.contact-details { padding: 4px 19px; border: 1px solid #9991C0; border-radius: 5px; background: #19174144; }
.contact-detail { display: grid; grid-template-columns: 88px minmax(0, 1fr); gap: 5px 13px; padding-block: 12px; }
.contact-detail + .contact-detail { border-top: 1px solid #837AA9; }
.contact-detail span { color: #D9D4F3; }
.contact-detail a, .contact-detail strong { font-weight: 700; overflow-wrap: anywhere; }
.contact-detail a:hover { text-decoration: underline; text-underline-offset: 4px; }
.footer { background: #111327; color: #DFDDE9; padding-block: 42px 20px; }
.footer-top { display: flex; justify-content: space-between; gap: 35px; padding-bottom: 26px; }
.footer-brand { color: white; }

.footer-about { max-width: 43ch; margin-top: 13px; }
.footer-links { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); align-content: start; gap: 12px 22px; }
.footer-links a:hover { text-decoration: underline; text-underline-offset: 4px; }
.footer-bottom { display: flex; flex-wrap: wrap; justify-content: space-between; gap: 8px 15px; padding-top: 13px; border-top: 1px solid #535467; font-size: 13px; }
.mobile-cta { display: none; }

@media (max-width: 1050px) {
  .nav-cta { display: none; }
  .nav-links { gap: clamp(13px, 2.5vw, 27px); }
  .hero-grid { min-height: 0; padding-block: 56px; }
  .hero-actions .btn { justify-content: space-between; }
}
@media (max-width: 800px) {
  :root { --nav-height: 64px; --gutter: 18px; }



  .menu-toggle { display: grid; place-items: center; }
  .nav-links {
    position: absolute; inset: 100% 0 auto; display: none; overflow-y: auto;
    max-height: max(90px, calc(100dvh - var(--nav-height) - var(--mobile-bar) - env(safe-area-inset-bottom)));
    padding: 5px var(--gutter) 12px; background: white; border-bottom: 1px solid var(--line); box-shadow: 0 18px 26px #171A2F30;
  }
  .nav-links.is-open { display: grid; gap: 0; }
  .nav-links a { padding: 13px 3px; border-bottom: 1px solid var(--line); }
  .hero-grid { grid-template-columns: minmax(0, 1fr); gap: 25px; padding-block: 42px 29px; }
  .hero h1 { max-width: 14ch; }
  .hero-visual { width: 100%; }

  .proof-ribbon-inner { align-items: start; flex-direction: column; gap: 5px; }
  .proof-ribbon span { font-size: .87rem; }
  .intro-grid, .record-layout, .credentials, .faq-layout, .contact-layout { grid-template-columns: minmax(0, 1fr); }
  .services-intro { align-items: start; flex-direction: column; }
  .service-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .pathways { gap: 12px; }
  .footer-top { flex-direction: column; gap: 22px; }
}
@media (max-width: 520px) {
  :root { --gutter: 16px; }
  html { scroll-padding-bottom: calc(var(--mobile-bar) + env(safe-area-inset-bottom)); }
  .hero-actions, .contact-actions { display: grid; grid-template-columns: minmax(0, 1fr); }
  .hero-proof { gap: 5px 14px; margin-top: 20px; }

  .service-grid, .pathways { grid-template-columns: minmax(0, 1fr); }
  .service-item { padding: 18px 20px 17px; }
  .service-top { margin-bottom: 10px; }
  .service-icon { width: 43px; height: 43px; }

  .contact-detail { grid-template-columns: minmax(0, 1fr); }
  .contact-actions .btn { justify-content: space-between; }
  .footer { padding-bottom: calc(var(--mobile-bar) + 17px + env(safe-area-inset-bottom)); }
  .mobile-cta {
    display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 8px; position: fixed;
    z-index: 9; inset: auto 0 0; padding: 9px var(--gutter) calc(9px + env(safe-area-inset-bottom)); background: #FFF; border-top: 1px solid var(--line);
  }
  .mobile-cta .btn { min-height: 45px; padding: 8px 6px; font-size: .82rem; }
  .mobile-cta .btn:nth-child(2) { background: var(--indigo); color: white; }
}
@media (prefers-reduced-motion: no-preference) {
  .reveal.is-observed { transition: opacity .85s ease, translate .85s cubic-bezier(.22,1,.36,1); }
  .reveal.is-observed:not(.visible):not(:focus-within) { opacity: 0; translate: 0 16px; }
}
@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  .btn { transition: none; }
}
/* A wide wordmark on a light, translucent navigation bar */
.header {
  background: radial-gradient(ellipse at 29% 18%, #d7c3b6a8, transparent 27%),
    radial-gradient(ellipse at 72% 80%, #c4b8b58c, transparent 27%), #fffffff0;
  backdrop-filter: blur(18px) saturate(110%);
  -webkit-backdrop-filter: blur(18px) saturate(110%);
  border-color: #271f561d;
}
.nav { gap: clamp(14px, 2vw, 31px); }
.brand, .footer-brand { display: inline-flex; align-items: center; flex: none; color: var(--indigo); }
.brand-mark { position: relative; display: block; overflow: hidden; width: clamp(164px, 17vw, 218px); aspect-ratio: 4.85; }
.brand-mark img { position: absolute; left: -9.1%; top: 50%; width: 119%; height: auto; max-width: none; transform: translateY(-46.4%); }
.brand-text { font: 800 1rem/1.2 var(--display); }
.nav-links { gap: clamp(13px, 1.65vw, 26px); }
.nav-links a { color: var(--indigo); white-space: nowrap; }
.nav-links a[aria-current="page"] { color: var(--orange-ink); }
.footer-brand { background: white; border-radius: 4px; padding: 8px 13px; }
.footer-brand .brand-mark { width: 176px; }

/* The original on-site photo takes the lead */
.hero { background: #171A2F; }
.hero-grid { min-height: 0; grid-template-columns: minmax(0,.93fr) minmax(0,1.07fr); padding-block: clamp(42px, 6vw, 96px); }
.hero-content { min-width: 0; }
.hero h1 { font-size: clamp(42px, 5.3vw, 83px); }
.hero-visual { display: grid; grid-template-rows: minmax(0, 1fr) auto; min-width: 0; align-self: stretch; }
.hero-image {
  position: relative; min-height: 360px; overflow: hidden; border-radius: 5px 5px 0 0;
  isolation: isolate; background: #272944;
}
.hero-image img { position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; object-position: 51% center; }
.hero-image::after { content: ""; position: absolute; inset: 0; border: 1px solid #FFFFFF35; border-bottom: 0; pointer-events: none; border-radius: 5px 5px 0 0; }
.hero-visual figcaption {
  padding: 10px 14px; color: #F0EDF8; background: #24233F; border-left: 3px solid var(--orange);
  font: 700 .75rem/1.4 var(--mono);
}
.about-facts {
  display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 1px; margin: clamp(25px, 4vw, 45px) 0 0;
  border: 1px solid var(--line); border-radius: 5px; overflow: hidden; background: var(--line);
}
.about-facts > div { background: #F7F5FA; padding: clamp(12px, 2.4vw, 26px); }
.about-facts dt { font-weight: 700; color: var(--slate); }
.about-facts dd { margin: 0 0 3px; color: var(--indigo); font: 800 clamp(25px, 4vw, 46px)/1.05 var(--display); letter-spacing: -.045em; }
.facts-source { margin-top: 9px; color: var(--slate); font-size: .85rem; }

/* Product highlights */
.products-section { background: white; }
.products-feature { display: grid; grid-template-columns: minmax(0, 1fr) minmax(0, 1fr); border-radius: 6px; overflow: hidden; background: var(--indigo); color: white; }
.products-copy { padding: clamp(25px, 5.4vw, 65px); }
.products-copy .eyebrow { color: #FFA185; }
.products-copy p { margin-top: 16px; color: #EEEAF8; }
.products-copy .btn { margin-top: 24px; }
.products-list { padding: 0; margin: 22px 0 0; list-style: none; display: grid; grid-template-columns: repeat(2,minmax(0,1fr)); gap: 9px 14px; }
.products-list li { border-top: 1px solid #FFFFFF4D; padding-top: 8px; font-weight: 700; line-height: 1.35; }
.products-image { position: relative; min-height: 320px; background: #363954; }
.products-image img { position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; object-position: 55% center; }

/* Real maintenance sites, award marks and existing clients */
.project-showcase { margin-top: clamp(32px, 6vw, 65px); }
.project-showcase > h3 { margin-bottom: 18px; color: var(--indigo); }
.project-grid, .awards-grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 14px; }
.project-card, .award { overflow: hidden; border-radius: 5px; border: 1px solid var(--line); background: white; }
.project-card img { width: 100%; aspect-ratio: 1.61; object-fit: cover; background: #E7E4EC; }
.project-card figcaption { padding: 14px 16px; }
.project-card strong, .award strong { display: block; font-family: var(--display); font-weight: 800; color: var(--indigo); }
.project-card span, .award span { color: var(--slate); font-size: .88rem; }
.recognition { background: #FBFAF8; }
.recognition .section-head, .clients .section-head { margin-bottom: 27px; }
.award { display: flex; min-width: 0; flex-direction: column; justify-content: space-between; padding: clamp(14px, 2vw, 26px); }
.award img { width: 100%; height: clamp(88px, 12vw, 135px); object-fit: contain; margin-bottom: 17px; }
.award figcaption { border-top: 1px solid var(--line); padding-top: 11px; }
.clients { padding-block: clamp(46px, 6vw, 76px); }
.client-grid { display: grid; grid-template-columns: repeat(6, minmax(0, 1fr)); gap: 1px; list-style: none; padding: 0; margin: 0; border: 1px solid var(--line); border-radius: 5px; overflow: hidden; background: var(--line); }
.client-grid li { min-width: 0; background: #FFF; display: grid; place-items: center; min-height: 90px; padding: 13px; }
.client-grid img { width: 100%; height: 62px; object-fit: contain; }

/* Customer voices, without a carousel */
.testimonials { background: #EFEDF6; }
.testimonial-grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 14px; }
.testimonial { display: flex; min-width: 0; flex-direction: column; align-items: start; justify-content: space-between; padding: clamp(20px, 3.5vw, 39px); border: 1px solid #D6D1E4; border-radius: 6px; background: #FFF; }
.testimonial::before { content: "“"; display: block; color: var(--orange-ink); font: 800 58px/.73 Georgia, serif; }
.testimonial blockquote { max-width: 62ch; margin: 10px 0 20px; color: var(--ink); font: 500 clamp(15px, 1.32vw, 17px)/1.65 var(--body); letter-spacing: normal; }
.testimonial figcaption { margin-top: auto; align-self: stretch; padding-top: 12px; border-top: 1px solid var(--line); color: var(--slate); font-size: .88rem; }
.testimonial figcaption strong { display: block; color: var(--indigo); font: 800 .98rem/1.4 var(--display); }

@media (max-width: 1080px) {
  .nav-cta { display: none; }
  .service-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
}
@media (min-width: 1081px) {
  .service-grid { grid-template-columns: repeat(4, minmax(0, 1fr)); }
}
@media (max-width: 980px) {
  .menu-toggle { display: grid; place-items: center; }
  .nav-links {
    position: absolute; inset: 100% 0 auto; display: none; overflow-y: auto;
    max-height: max(90px, calc(100dvh - var(--nav-height) - var(--mobile-bar) - env(safe-area-inset-bottom)));
    padding: 6px var(--gutter) 12px; background: #FFFEFD; border-bottom: 1px solid var(--line); box-shadow: 0 18px 26px #171A2F30;
  }
  .nav-links.is-open { display: grid; gap: 0; }
  .nav-links a { padding: 12px 3px; border-bottom: 1px solid var(--line); }
}
@media (max-width: 800px) {
  .hero-grid, .products-feature { grid-template-columns: minmax(0, 1fr); }
  .hero-image, .products-image { min-height: 0; aspect-ratio: 16/9; }
  .project-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .client-grid { grid-template-columns: repeat(3, minmax(0, 1fr)); }
}
@media (max-width: 520px) {
  .brand-mark { width: 166px; }
  .hero-grid { gap: 24px; }
  .about-facts dt { font-size: .8rem; line-height: 1.36; }
  .about-facts dd { font-size: clamp(19px, 5.5vw, 28px); }
  .project-grid, .testimonial-grid, .service-grid, .awards-grid { grid-template-columns: minmax(0, 1fr); }
  .award { display: grid; grid-template-columns: minmax(0, .85fr) minmax(0, 1.15fr); align-items: center; gap: 13px; }
  .award img { margin: 0; height: 70px; }
  .award figcaption { padding: 0; border: 0; }
  .client-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .client-grid li { min-height: 76px; padding: 8px 13px; }
  .client-grid img { height: 56px; }
}
  </style>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "J.Keart Alliances Pte Ltd",
    "url": "https://jkeart.com/",
    "telephone": "+65 6844 4648",
    "email": "enquiry@jkeart.com",
    "address": {
      "@type": "PostalAddress",
      "streetAddress": "207 Henderson Road, #01-04 Henderson Industrial Park",
      "addressLocality": "Singapore",
      "postalCode": "159550",
      "addressCountry": "SG"
    },
    "foundingDate": "1988",
    "description": "Mechanical and engineering works for fire protection systems and fire-safety-related services in Singapore."
  }
  </script>
</head>

<body>
  <header class="header">
    <div class="wrap nav">
      <a class="brand" href="#home" aria-label="J.Keart Alliances home">
        <span class="brand-mark"><img src="https://jkeart.com/wp-content/uploads/2025/07/JKEART-logo.webp" width="1000" height="1000" alt="" decoding="async"></span>
        <span class="brand-text" hidden>J.Keart Alliances</span>
      </a>

      <button class="menu-toggle" type="button" aria-label="Open navigation" aria-expanded="false" aria-controls="primary-navigation">☰</button>

      <nav class="nav-links" id="primary-navigation" aria-label="Main navigation">
        <a href="#home" aria-current="page">Home</a>
        <a href="#about">About us</a>
        <a href="#services">Fire services</a>
        <a href="#products">Fire products</a>
        <a href="#track-record">Track record</a>
        <a href="#contact">Contact us</a>
      </nav>

      <a class="btn btn--orange nav-cta" href="#contact">Discuss a project <span class="arrow" aria-hidden="true">↗</span></a>
    </div>
  </header>

  <main id="home" tabindex="-1">
    <section class="hero">
      <div class="wrap hero-grid">
        <div class="hero-content">
          <span class="eyebrow">Protecting lives since 1988</span>
          <h1>Fire protection, <span>engineered</span> with purpose.</h1>
          <p class="hero-copy">
            From fire protection installations and equipment maintenance to SCDF submissions and Fire Certificate renewals, J.Keart supports safer commercial and industrial buildings across Singapore.
          </p>
          <div class="hero-actions">
            <a class="btn btn--orange" href="#contact">Discuss your fire-safety needs <span class="arrow" aria-hidden="true">↗</span></a>
            <a class="btn btn--outline" href="#services">Explore our services <span class="arrow" aria-hidden="true">↓</span></a>
          </div>
          <div class="hero-proof">
            <span><strong>Established 1988</strong></span>
            <span><strong>BCA ME06 L5</strong> listed on company website</span>
            <span><strong>Singapore</strong> fire-safety services</span>
          </div>
        </div>


        <figure class="hero-visual">
          <div class="hero-image">
            <img src="https://jkeart.com/wp-content/uploads/2025/09/WhatsApp-Image-2025-09-17-at-10.47.40_1a498c16.jpg" alt="J.Keart personnel in hard hats inspecting red fire-protection pipework" fetchpriority="high" decoding="async">
          </div>
          <figcaption>J.Keart’s fire-protection team on site</figcaption>
        </figure>
      </div>
    </section>

    <div class="proof-ribbon">
      <div class="wrap proof-ribbon-inner">
        <strong>One specialist partner across the fire-safety lifecycle.</strong>
        <span>Installation · Compliance support · Maintenance · Equipment</span>
      </div>
    </div>

    <section class="section" id="about" tabindex="-1">
      <div class="wrap intro-grid reveal">
        <div>
          <span class="eyebrow">A practical partner</span>
          <h2>Built around the safety of the places people depend on.</h2>
        </div>
        <div class="intro-statement">
          <p class="lead">
            J.Keart Alliances Pte Ltd was incorporated in November 1988. Its principal activities are engineering works for fire protection systems and fire-safety-related services, with a track record in commercial and industrial building maintenance.
          </p>
          <p>
            The team’s published service range covers project installations, SCDF submissions, Fire Certificate renewals, equipment servicing, specialist fire-safety installations and builder works.
          </p>
          <div class="intro-note">
            A connected service offering for building owners, facilities teams, developers and project partners.
          </div>
        </div>
      </div>
      <div class="wrap">
        <dl class="about-facts">
          <div><dt>Sq ft of factory space</dt><dd>45,000</dd></div>
          <div><dt>Staff members</dt><dd>170</dd></div>
          <div><dt>Projects carried out</dt><dd>12,000</dd></div>
        </dl>
        <p class="facts-source">Figures published by J.Keart.</p>
      </div>
    </section>

    <section class="section section--mist" id="services" tabindex="-1">
      <div class="wrap">
        <div class="services-intro">
          <div class="section-head reveal">
            <span class="eyebrow">What we do</span>
            <h2>Fire-safety services, clearly connected.</h2>
            <p class="lead">Explore the key areas of support, from project-stage fire protection to the ongoing care of installed systems and equipment.</p>
          </div>
          <a class="btn btn--light" href="https://jkeart.com/fire-services/">View all fire services <span class="arrow" aria-hidden="true">↗</span></a>
        </div>

        <div class="service-grid">
          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">PROJECTS</span>
              <svg class="service-icon" viewBox="0 0 64 64" role="img" aria-label="Fire project installation icon">
                <path d="M10 52V18h44v34M18 52V27h28v25M25 27v-9M39 27v-9M6 52h52M25 39h14M25 46h14"/>
                <path d="M32 5v8M28 9h8"/>
              </svg>
            </div>
            <h3>Fire project installations</h3>
            <p>Fire protection system engineering and installation. J.Keart describes using pre-fabrication technology and computerised machinery for pipe installation work.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#Project">Explore installations <span aria-hidden="true">↗</span></a>
          </article>

          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">COMPLIANCE</span>
              <svg class="service-icon" viewBox="0 0 64 64" role="img" aria-label="SCDF submission icon">
                <path d="M18 8h20l10 10v38H18zM38 8v12h10M25 31h16M25 39h16M25 47h10"/>
                <path d="m8 28 5 5 9-10"/>
              </svg>
            </div>
            <h3>SCDF submissions</h3>
            <p>Support for fire-safety-related submissions associated with proposed alterations and works that may affect building fire-safety provisions.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#SCDF">Explore submissions <span aria-hidden="true">↗</span></a>
          </article>

          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">CERTIFICATION</span>
              <svg class="service-icon" viewBox="0 0 64 64" role="img" aria-label="Fire Certificate renewal icon">
                <path d="M17 9h30v43H17zM24 20h16M24 28h16M24 36h10"/>
                <circle cx="42" cy="43" r="9"/>
                <path d="m38 43 3 3 6-7"/>
              </svg>
            </div>
            <h3>Fire Certificate renewals</h3>
            <p>Assistance with Fire Certificate renewal requirements and the testing of fire-safety measures in line with applicable requirements.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#Certificate">Explore renewals <span aria-hidden="true">↗</span></a>
          </article>

          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">MAINTENANCE</span>
              <svg class="service-icon" viewBox="0 0 64 64" role="img" aria-label="Fire equipment maintenance icon">
                <path d="M25 10h14v8H25zM22 18h20v34H22zM28 26h8M28 33h8"/>
                <path d="M42 26h8v14h-8M22 43h-7v-9h7"/>
                <path d="M32 39v6M29 42h6"/>
              </svg>
            </div>
            <h3>Fire equipment maintenance</h3>
            <p>Regular testing and servicing intended to help keep fire protection products and systems in working condition.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#Equipment">Explore maintenance <span aria-hidden="true">↗</span></a>
          </article>

          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">EQUIPMENT</span>
              <svg class="service-icon" viewBox="0 0 64 64" role="img" aria-label="Fire extinguisher refilling icon">
                <path d="M27 12h12v7H27zM25 19h16v34H25zM30 12V7h8M41 24h8v10h-8"/>
                <path d="M30 29h6M30 36h6M30 43h6"/>
                <path d="M22 53h22"/>
              </svg>
            </div>
            <h3>Fire extinguisher refilling</h3>
            <p>Refilling services for fire extinguishers, alongside the company’s wider fire equipment maintenance offering.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#Refilling">Explore refilling <span aria-hidden="true">↗</span></a>
          </article>

          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">KITCHEN SYSTEMS</span>
              <svg class="service-icon" viewBox="0 0 64 64" role="img" aria-label="Kitchen fire-suppression installation icon">
                <path d="M10 52h44M15 52V20h34v32M22 20V11h20v9M22 31h20M22 39h20"/>
                <path d="M32 11V5M28 8h8"/>
                <path d="M43 31h6M43 39h6"/>
              </svg>
            </div>
            <h3>Kitchen wet chemical systems</h3>
            <p>Kitchen wet chemical systems for commercial kitchens, designed around the requirements of the premises.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#Kitchen">Explore kitchen systems <span aria-hidden="true">↗</span></a>
          </article>
          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">Passive protection</span>
              <svg class="service-icon" viewBox="0 0 64 64" aria-hidden="true"><path d="M15 54V10h34v44M21 54V16h22v38M36 34h2M10 54h44"/></svg>
            </div>
            <h3>Fire-rated boards and doors</h3>
            <p>Installation of passive protection products for new projects and alterations.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#Boards">Explore boards and doors <span aria-hidden="true">↗</span></a>
          </article>
          <article class="service-item reveal">
            <div class="service-top">
              <span class="service-category">Construction</span>
              <svg class="service-icon" viewBox="0 0 64 64" aria-hidden="true"><path d="M8 53h48M13 50V31h14v19M27 50V19h13v31M40 50V12h11v38M16 39h7M30 28h7M43 20h5"/></svg>
            </div>
            <h3>Builder works</h3>
            <p>Construction support alongside fire-protection works, from planning and coordination to site execution.</p>
            <a class="text-link" href="https://jkeart.com/fire-services/#Builder">Explore builder works <span aria-hidden="true">↗</span></a>
          </article>
        </div>
      </div>
    </section>

        <section class="section products-section" id="products" tabindex="-1">
      <div class="wrap">
        <div class="products-feature">
          <div class="products-copy">
            <span class="eyebrow">Fire safety products</span>
            <h2>Equipment for your building.</h2>
            <p>Browse J.Keart’s published range of fire-fighting equipment, refills and replacement parts.</p>
            <ul class="products-list">
              <li>Fire extinguishers</li><li>Hose reels</li>
              <li>Wet and dry riser equipment</li><li>Cabinets, refills and spares</li>
            </ul>
            <a class="btn btn--orange" href="https://jkeart.com/fire-products/">Explore fire products <span class="arrow" aria-hidden="true">↗</span></a>
          </div>
          <div class="products-image">
            <img src="https://jkeart.com/wp-content/uploads/2025/09/WhatsApp-Image-2025-09-17-at-10.47.40_cf53f56c.jpg" alt="An outdoor fire-extinguisher demonstration featured by J.Keart" loading="lazy" decoding="async">
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="approach" tabindex="-1">
      <div class="wrap">
        <div class="section-head reveal">
          <span class="eyebrow">Find the right starting point</span>
          <h2>What does your building need next?</h2>
          <p class="lead">Different building and project requirements call for different conversations. Choose the pathway that best describes your requirement.</p>
        </div>
        <div class="pathways">
          <article class="pathway reveal">
            <span class="pathway-label">For existing buildings</span>
            <h3>Maintain and service installed fire protection systems.</h3>
            <p>Discuss regular servicing, equipment maintenance, extinguisher refilling or Fire Certificate renewal requirements.</p>
            <a class="text-link" href="#contact">Discuss maintenance needs <span aria-hidden="true">↗</span></a>
          </article>
          <article class="pathway reveal">
            <span class="pathway-label">For new projects and alterations</span>
            <h3>Plan fire protection works with the project team.</h3>
            <p>Explore fire protection installations, SCDF-related submissions, kitchen suppression systems and associated builder works.</p>
            <a class="text-link" href="#contact">Discuss a project <span aria-hidden="true">↗</span></a>
          </article>
        </div>
      </div>
    </section>

    <section class="section section--warm" id="track-record" tabindex="-1">
      <div class="wrap record-layout">
        <div class="record-intro reveal">
          <span class="eyebrow">Selected experience</span>
          <h2>Project and maintenance experience across Singapore.</h2>
          <p>J.Keart’s published track record includes public-sector, commercial, industrial and institutional environments. The examples shown here are drawn from its project and maintenance record.</p>
          <a class="btn btn--orange record-link" href="https://jkeart.com/track-record/">View track record <span class="arrow" aria-hidden="true">↗</span></a>
        </div>

        <div class="record-list reveal">
          <div class="record-row">
            <span class="record-year">2025</span>
            <div><strong>Willing Hearts</strong><span>Published project / maintenance record</span></div>
          </div>
          <div class="record-row">
            <span class="record-year">2024</span>
            <div><strong>Ministry of National Development</strong><span>Published project / maintenance record</span></div>
          </div>
          <div class="record-row">
            <span class="record-year">2023</span>
            <div><strong>UE Square · PUB Tuas Water Reclamation</strong><span>Published project / maintenance record</span></div>
          </div>
          <div class="record-row">
            <span class="record-year">2022</span>
            <div><strong>Jalan Besar Town Council · SP Group UGSS Water Mist</strong><span>Published project / maintenance record</span></div>
          </div>
          <div class="record-row">
            <span class="record-year">2021</span>
            <div><strong>IKEA Tampines Singapore</strong><span>Published project / maintenance record</span></div>
          </div>
          <div class="record-row">
            <span class="record-year">2018</span>
            <div><strong>HDB Civil Defence Shelters · Singtel</strong><span>Published project / maintenance record</span></div>
          </div>
        </div>
      </div>
      <div class="wrap project-showcase reveal">
        <h3>Selected maintenance sites</h3>
        <div class="project-grid">
          <figure class="project-card">
            <img src="https://jkeart.com/wp-content/uploads/2025/07/Screenshot-2025-07-21-173635.webp" alt="" loading="lazy" decoding="async">
            <figcaption><strong>CHIJMES</strong><span>Victoria Street · Fire protection maintenance</span></figcaption>
          </figure>
          <figure class="project-card">
            <img src="https://jkeart.com/wp-content/uploads/2025/07/Screenshot-2025-07-21-173644.webp" alt="" loading="lazy" decoding="async">
            <figcaption><strong>Tanglin Mall</strong><span>Fire alarm and equipment maintenance</span></figcaption>
          </figure>
          <figure class="project-card">
            <img src="https://jkeart.com/wp-content/uploads/2025/07/Screenshot-2025-07-21-173658.webp" alt="" loading="lazy" decoding="async">
            <figcaption><strong>Factory at Tuas</strong><span>Jotun Singapore · Fire protection maintenance</span></figcaption>
          </figure>
        </div>
      </div>
    </section>

    <section class="section" id="credentials" tabindex="-1">
      <div class="wrap credentials">
        <div class="credential-copy reveal">
          <span class="eyebrow">Credentials and standards</span>
          <h2>Fire protection credentials and standards.</h2>
          <p>The company website presents a range of management-system certifications, safety recognition and fire-protection registrations.</p>
          <a class="btn btn--orange" href="https://jkeart.com/about-us/">Learn more about J.Keart <span class="arrow" aria-hidden="true">↗</span></a>
        </div>
        <div class="credential-list reveal">
          <div class="credential-row">
            <strong>ISO 9001:2015</strong>
            <span>Quality management</span>
          </div>
          <div class="credential-row">
            <strong>ISO 45001:2018</strong>
            <span>Occupational health and safety</span>
          </div>
          <div class="credential-row">
            <strong>bizSAFE STAR</strong>
            <span>Workplace safety recognition</span>
          </div>
          <div class="credential-row">
            <strong>BCA ME06 · L5</strong>
            <span>Fire protection workhead, as stated on company website</span>
          </div>
          <div class="credential-row">
            <strong>Approved workshop</strong>
            <span>Portable fire extinguisher servicing and maintenance</span>
          </div>
          <p class="credential-note">Contact J.Keart to confirm current credential validity.</p>
        </div>
      </div>
    </section>

    <section class="section recognition" id="recognition" tabindex="-1">
      <div class="wrap">
        <div class="section-head reveal">
          <span class="eyebrow">Industry recognition</span>
          <h2>Awards &amp; accreditations.</h2>
          <p class="lead">Brand and entrepreneurship awards published by J.Keart.</p>
        </div>
        <div class="awards-grid reveal">
          <figure class="award">
            <img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/SPB_logo-01-scaled-r92dv6h46fxozzply3zt4j604c8gjfdge6nkan77cw.webp" alt="" loading="lazy" decoding="async">
            <figcaption><strong>Singapore Prominent Brands</strong><span>2015 / 2016</span></figcaption>
          </figure>
          <figure class="award">
            <img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/APEA-Logo-r92dv9amqy1jytlihn7ou0gdwhuk6ionekm0qh30u8.webp" alt="" loading="lazy" decoding="async">
            <figcaption><strong>Asia Pacific Entrepreneurship Awards</strong><span>APEA 2016</span></figcaption>
          </figure>
          <figure class="award">
            <img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Winner-Established-Brands_Gold-scaled-r92dv2prf3sjpjv2k2dauk45qsqzomyj1o1mdjcs1s.webp" alt="" loading="lazy" decoding="async">
            <figcaption><strong>Singapore Prestige Brand Award</strong><span>2016 winner · Established Brands</span></figcaption>
          </figure>
        </div>
      </div>
    </section>

    <section class="section clients" id="clients" tabindex="-1">
      <div class="wrap">
        <div class="section-head reveal">
          <h2>Our clients.</h2>
        </div>
        <ul class="client-grid reveal" aria-label="Selected clients published by J.Keart">
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/EM-Services-Pte-Ltd-r92ed3aeesge8hozcupvn0g7mny97shbiu6nign4sg.webp" alt="EM Services" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Concorde-Hotel-r92ed3aeesge8hozcupvn0g7mny97shbiu6nign4sg.webp" alt="Concorde Hotel Singapore" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Archer_1-r92ed2ck7yf3wvqcicb92ior1a2w03dl6pj616oiyo.webp" alt="Archer" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/HDB-r92ed488lmhok3nm7d4i7i7o81tmfhl1uyu4zqlqm8.webp" alt="Housing &amp; Development Board" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Keppel-r92ed63wzak97bkvwdxrchqletkcuvsij853yaiy9s.webp" alt="Keppel" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Mapletree-r92ed71r64ljixjiqwcdwzi207fq2kw8vcslfkhk3k.webp" alt="Mapletree" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Parkway-Hospitals-Singapore-r92ekbnozwctkh6s4h9jboqw6eaxfy6yumw5g3x2ww.webp" alt="Parkway Hospitals Singapore" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/OSIM-r92ekbnozwctkh6s4h9jboqw6eaxfy6yumw5g3x2ww.webp" alt="OSIM" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/WahHong-logo-r92ek1bgwpyo0rlssusn29ctn5pw3a1x57pt62cetc.webp" alt="Wah Hong" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/vanguard-logo-r92ek29b3jzycdkfnd79mr4a8jl9az5nhcdancb0n4.webp" alt="Vanguard Fire Systems" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/JTC-r92ed562sgiyvpm91vj4rzz4tfozn6os73hmh0kcg0.webp" alt="JTC" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Ang-Mo-Kio-Town-Council-r92ed2ck7yf3wvqcicb92ior1a2w03dl6pj616oiyo.webp" alt="Ang Mo Kio Town Council" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/BP-r92ed2ck7yf3wvqcicb92ior1a2w03dl6pj616oiyo.webp" alt="BP" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/ITE-College-Central-r92ed488lmhok3nm7d4i7i7o81tmfhl1uyu4zqlqm8.webp" alt="ITE College Central" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/UES-Engineers-r92ek29b3jzycdkfnd79mr4a8jl9az5nhcdancb0n4.webp" alt="UES Engineers" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Spore-Cruise-Centre-r92ek7wc8k7oa1c8qfn11pp1sutgl5s1i4a7j02nls.webp" alt="Singapore Cruise Centre" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/Grand-Park-r92ed488lmhok3nm7d4i7i7o81tmfhl1uyu4zqlqm8.webp" alt="Grand Park" loading="lazy" decoding="async"></li>
          <li><img src="https://jkeart.com/wp-content/uploads/elementor/thumbs/People-Association-r92ekaput2bj8v859yuwr6zfl0fk8938ii8nytyh34.webp" alt="People’s Association" loading="lazy" decoding="async"></li>
        </ul>
      </div>
    </section>

    <section class="section testimonials" id="testimonials" tabindex="-1">
      <div class="wrap">
        <div class="section-head reveal">
          <h2>Customer testimonials.</h2>
        </div>
        <div class="testimonial-grid">
          <figure class="testimonial reveal">
            <blockquote><p>I engaged J.Keart to carry out A&amp;A works for my semi-detached house and I am extremely satisfied with the results. The entire process was smooth and stress-free and they delivered the work on schedule. I would highly recommend J.Keart to anyone looking for a reliable and capable builder.</p></blockquote>
            <figcaption><strong>Or Siew Hong</strong>Homeowner, Sunrise Avenue</figcaption>
          </figure>
          <figure class="testimonial reveal">
            <blockquote><p>For the past few years, J.Keart has been maintaining the fire alarm system in my warehouse at Mandai Connection. Their team is knowledgeable, efficient and thorough in ensuring that my systems are fully compliant with fire safety regulations. I have peace of mind knowing that my property is well-protected and that the inspections are carried out by experienced professionals — a trusted partner I can count on year after year.</p></blockquote>
            <figcaption><strong>Marcus Ng</strong>Director, Food Paradise Enterprise Holding Pte Ltd</figcaption>
          </figure>
          <figure class="testimonial reveal">
            <blockquote><p>In our industry of design and construction, the challenge to ensure that the project is successfully completed requires much professionalism, accuracy, commitment, cooperation and so much more. Your team provided all of the components! Thank you for the whole team for your cooperation.</p></blockquote>
            <figcaption><strong>Yew Eng Piow</strong>General Manager, Sato Kogyo</figcaption>
          </figure>
          <figure class="testimonial reveal">
            <blockquote><p>J.Keart was highly responsive and met every deadline established. We were working with tight deadlines and found the experience to be extremely satisfactory.</p></blockquote>
            <figcaption><strong>Johnson Tang</strong>Managing Director, UES Holdings Pte Ltd</figcaption>
          </figure>
        </div>
      </div>
    </section>

    <section class="section section--mist">
      <div class="wrap faq-layout">
        <div class="faq-intro reveal">
          <span class="eyebrow">Useful information</span>
          <h2>Questions about fire-safety services?</h2>
          <p>Some common starting points for building owners, facilities managers and project teams.</p>
        </div>
        <div class="faq-list reveal">
          <div class="faq-item is-open">
            <button class="faq-question" type="button" aria-expanded="true" aria-controls="faq-answer-1">
              <span>What fire protection services does J.Keart provide?</span><span aria-hidden="true">−</span>
            </button>
            <div class="faq-answer" id="faq-answer-1">The published service range includes fire project installations, SCDF submissions, Fire Certificate renewals, fire equipment maintenance, extinguisher refilling, fire-rated boards and doors, kitchen wet chemical installation and builder works.</div>
          </div>
          <div class="faq-item">
            <button class="faq-question" type="button" aria-expanded="false" aria-controls="faq-answer-2">
              <span>Can J.Keart assist with SCDF submissions?</span><span aria-hidden="true">+</span>
            </button>
            <div class="faq-answer" id="faq-answer-2">SCDF submission support is listed as one of J.Keart’s services. Contact the team with details of the proposed work to discuss the appropriate requirements and next steps.</div>
          </div>
          <div class="faq-item">
            <button class="faq-question" type="button" aria-expanded="false" aria-controls="faq-answer-3">
              <span>Does J.Keart provide ongoing fire equipment maintenance?</span><span aria-hidden="true">+</span>
            </button>
            <div class="faq-answer" id="faq-answer-3">Yes. The company describes regular testing and servicing programmes for fire protection products and systems. The scope and schedule can be discussed directly with the team.</div>
          </div>
          <div class="faq-item">
            <button class="faq-question" type="button" aria-expanded="false" aria-controls="faq-answer-4">
              <span>How long has J.Keart been operating?</span><span aria-hidden="true">+</span>
            </button>
            <div class="faq-answer" id="faq-answer-4">J.Keart Alliances Pte Ltd states that it was incorporated in November 1988.</div>
          </div>
          <div class="faq-item">
            <button class="faq-question" type="button" aria-expanded="false" aria-controls="faq-answer-5">
              <span>How can I discuss a project or maintenance requirement?</span><span aria-hidden="true">+</span>
            </button>
            <div class="faq-answer" id="faq-answer-5">Call +65 6844 4648 or email enquiry@jkeart.com. You can also use the official contact page to reach the company.</div>
          </div>
        </div>
      </div>
    </section>

    <section class="section contact" id="contact" tabindex="-1">
      <div class="wrap contact-layout">
        <div class="contact-copy reveal">
          <span class="eyebrow">Start a conversation</span>
          <h2>Let’s discuss what your building needs.</h2>
          <p>Whether you are planning a fire protection installation, arranging ongoing maintenance or seeking support with fire-safety requirements, contact J.Keart to discuss your project.</p>
          <div class="contact-actions">
            <a class="btn btn--orange" href="tel:+6568444648">Call J.Keart <span class="arrow" aria-hidden="true">↗</span></a>
            <a class="btn btn--outline" href="mailto:enquiry@jkeart.com">Email an enquiry <span class="arrow" aria-hidden="true">↗</span></a>
          </div>
        </div>
        <div class="contact-details reveal">
          <div class="contact-detail">
            <span>Telephone</span>
            <a href="tel:+6568444648">+65 6844 4648</a>
          </div>
          <div class="contact-detail">
            <span>Email</span>
            <a href="mailto:enquiry@jkeart.com">enquiry@jkeart.com</a>
          </div>
          <div class="contact-detail">
            <span>Address</span>
            <strong>207 Henderson Road, #01-04 Henderson Industrial Park, Singapore 159550</strong>
          </div>
          <div class="contact-detail">
            <span>Website</span>
            <a href="https://jkeart.com/contact-us/">Official contact page ↗</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="wrap">
      <div class="footer-top">
        <div>
          <a class="footer-brand" href="#home" aria-label="J.Keart Alliances home">
            <span class="brand-mark"><img src="https://jkeart.com/wp-content/uploads/2025/07/JKEART-logo.webp" width="1000" height="1000" alt="" decoding="async" loading="lazy"></span>
        <span class="brand-text" hidden>J.Keart Alliances</span>
          </a>
          <p class="footer-about">Fire protection engineering and fire-safety-related services for commercial and industrial buildings in Singapore. Protecting lives since 1988.</p>
        </div>
        <nav class="footer-links" aria-label="Footer navigation">
          <a href="#services">Services</a>
          <a href="#approach">Our approach</a>
          <a href="#track-record">Track record</a>
          <a href="#credentials">Credentials</a>
          <a href="#recognition">Awards</a>
          <a href="#clients">Our clients</a>
          <a href="#testimonials">Testimonials</a>
          <a href="https://jkeart.com/career/">Careers</a>
          <a href="https://jkeart.com/fire-products/">Fire products</a>
          <a href="https://jkeart.com/contact-us/">Contact us</a>
        </nav>
      </div>
      <div class="footer-bottom">
        <span>© <span id="year">2026</span> J.Keart Alliances Pte Ltd. All rights reserved.</span>
        <span>Fire protection · Engineering · Singapore</span>
      </div>
    </div>
  </footer>

  <div class="mobile-cta" aria-label="Quick contact actions">
    <a class="btn btn--orange" href="tel:+6568444648">Call J.Keart</a>
    <a class="btn" href="mailto:enquiry@jkeart.com">Email enquiry</a>
  </div>

  <script>
    const menuButton = document.querySelector(".menu-toggle");
    const navLinks = document.querySelector(".nav-links");
    const mobileNav = window.matchMedia("(max-width: 980px)");

    function setNavigation(open) {
      navLinks.classList.toggle("is-open", open);
      menuButton.setAttribute("aria-expanded", String(open));
      menuButton.setAttribute("aria-label", open ? "Close navigation" : "Open navigation");
      menuButton.textContent = open ? "×" : "☰";
    }

    menuButton.addEventListener("click", () => setNavigation(!navLinks.classList.contains("is-open")));
    mobileNav.addEventListener("change", () => setNavigation(false));

    document.addEventListener("keydown", event => {
      if (event.key === "Escape" && navLinks.classList.contains("is-open")) {
        setNavigation(false);
        menuButton.focus({ preventScroll: true });
      }
    });

    document.addEventListener("click", event => {
      if (navLinks.classList.contains("is-open") && !navLinks.contains(event.target) && !menuButton.contains(event.target)) {
        setNavigation(false);
      }
    });

    navLinks.addEventListener("click", event => {
      const link = event.target.closest("a");
      if (!link || !mobileNav.matches) return;
      setNavigation(false);
      const target = document.getElementById(link.hash.slice(1));
      target?.focus({ preventScroll: true });
    });

    for (const button of document.querySelectorAll(".faq-question")) {
      const answer = document.getElementById(button.getAttribute("aria-controls"));
      const indicator = button.querySelector("span:last-child");
      const update = open => {
        button.setAttribute("aria-expanded", String(open));
        answer.hidden = !open;
        indicator.textContent = open ? "−" : "+";
      };
      update(button.getAttribute("aria-expanded") === "true");
      button.addEventListener("click", () => update(button.getAttribute("aria-expanded") !== "true"));
    }

    const motion = window.matchMedia("(prefers-reduced-motion: no-preference)");
    if (motion.matches && "IntersectionObserver" in window) {
      const observer = new IntersectionObserver(entries => {
        for (const entry of entries) {
          if (!entry.isIntersecting) continue;
          entry.target.classList.add("visible");
          observer.unobserve(entry.target);
        }
      }, { threshold: 0.08 });
      for (const element of document.querySelectorAll(".reveal")) {
        if (element.getBoundingClientRect().top >= window.innerHeight) {
          observer.observe(element);
          element.classList.add("is-observed");
        }
      }
    }

    for (const logo of document.querySelectorAll(".brand-mark img")) {
      const showFallback = () => {
        const mark = logo.closest(".brand-mark");
        mark.hidden = true;
        mark.nextElementSibling.hidden = false;
      };
      logo.addEventListener("error", showFallback);
      if (logo.complete && !logo.naturalWidth) showFallback();
    }

    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
