---
layout: post
title: "Fried Chicken Matcha Latte: Viral KFC Oreo Halloween Creation & Review"
date: 2026-10-25
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Grandstander:wght@600;800&family=Figtree:wght@400;600;700&display=swap" rel="stylesheet">

<style>
  .cs {
    --banana: #FFD23F;
    --pudding: #FFF4C7;
    --matcha: #5B7F2B;
    --matcha-deep: #2F4A1A;
    --foam: #E9F1D8;
    --ink: #2A2616;
    --denim: #3A6EA5;
    --display: 'Grandstander', 'Trebuchet MS', 'Comic Sans MS', system-ui, sans-serif;
    --body: 'Figtree', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    font-family: var(--body);
    color: var(--ink);
    line-height: 1.6;
    max-width: 640px;
    margin: 0 auto;
  }
  .cs *, .cs *::before, .cs *::after { box-sizing: border-box; }
  .cs a { color: var(--denim); text-underline-offset: 3px; }
  .cs a:focus-visible { outline: 3px solid var(--denim); outline-offset: 3px; border-radius: 6px; }
  .cs p { margin: 0 0 16px; }

  /* Brand strip */
  .cs-brand {
    position: relative; overflow: hidden;
    display: grid; grid-template-columns: auto 1fr; align-items: center; column-gap: 16px;
    padding: 18px 20px 18px 22px; margin: 8px 6px 32px 0;
    border: 2px solid var(--ink); border-radius: 24px; background: var(--banana);
    box-shadow: 6px 6px 0 var(--ink);
  }
  /* Goggle strap running in from the left edge */
  .cs-brand::before {
    content: ""; position: absolute; left: 0; top: 50%; width: 60px; height: 14px;
    transform: translateY(-50%); background: var(--ink);
  }
  /* The goggle itself, with the matcha bowl as the eye */
  .cs-goggle {
    position: relative; z-index: 1;
    width: 72px; height: 72px; border-radius: 50%;
    display: grid; place-items: center; font-size: 34px; line-height: 1;
    background: #fff; border: 7px solid #A7ADB4;
    box-shadow: 0 0 0 2px var(--ink), inset 0 0 0 2px var(--ink);
  }
  .cs-brand-text { min-width: 0; }
  .cs-brand-name { font-family: var(--display); font-weight: 800; font-size: 24px; line-height: 1.1; }
  .cs-tagline { margin: 2px 0 12px !important; font-size: 13px; color: #4d4418; }
  .cs-social { display: flex; flex-wrap: wrap; gap: 6px; }
  .cs .cs-social a {
    padding: 6px 13px; border-radius: 999px; font-size: 12px; font-weight: 700;
    color: #fff; text-decoration: none; border: 2px solid var(--ink);
  }
  .cs-ig { background: #E1306C; } .cs-tt { background: #000; } .cs-fb { background: #1877F2; } .cs-yt { background: #FF0000; }

  /* Hero: the stall's two counters, side by side */
  .cs-hero { border: 2px solid var(--ink); border-radius: 28px; overflow: hidden; margin-bottom: 28px; }
  .cs-hero-top { background: #fff; padding: 24px 22px 20px; }
  .cs h1.cs-title {
    font-family: var(--display); font-weight: 800; font-size: clamp(30px, 7vw, 44px);
    line-height: 1.05; letter-spacing: -0.5px; margin: 0 0 10px; color: var(--ink);
  }
  .cs-where { margin: 0; font-size: 15px; color: #5c5640; }
  .cs-counters { display: grid; grid-template-columns: 1fr 1fr; border-top: 2px solid var(--ink); }
  .cs-counter { padding: 18px 22px 22px; }
  .cs-counter + .cs-counter { border-left: 2px solid var(--ink); }
  .cs-counter-banana { background: var(--banana); }
  .cs-counter-matcha { background: var(--matcha); color: #fff; }
  .cs-counter-emoji { font-size: 34px; line-height: 1; display: block; margin-bottom: 8px; }
  .cs-counter strong { display: block; font-family: var(--display); font-size: 21px; line-height: 1.15; }
  .cs-counter span.cs-from { font-size: 14px; opacity: .9; }

  /* Video */
  .cs h2 {
    font-family: var(--display); font-weight: 800; font-size: 26px; line-height: 1.15;
    margin: 0 0 14px; color: inherit;
  }
  .cs-video { text-align: center; margin: 36px 0; }
  .cs-video h2 { text-align: left; }
  .cs-btn {
    display: inline-block; margin-top: 14px; padding: 11px 22px; border-radius: 999px;
    background: #E1306C; color: #fff !important; font-weight: 700; text-decoration: none;
    border: 2px solid var(--ink);
  }
  .cs-yt-frame {
    position: relative; width: 100%; max-width: 300px; margin: 12px auto 0; aspect-ratio: 9/16;
    border-radius: 20px; overflow: hidden; border: 2px solid var(--ink);
  }
  .cs-yt-frame iframe { position: absolute; inset: 0; width: 100%; height: 100%; border: 0; }
  .cs-alt { margin: 26px 0 0; font-size: 14px; color: #5c5640; }
  .cs-more { margin-top: 14px; font-size: 14px; }

  /* Menu boards */
  .cs-board { border: 2px solid var(--ink); border-radius: 28px; padding: 26px 22px; margin: 0 0 22px; }
  .cs-board-banana { background: var(--pudding); }
  .cs-board-matcha { background: var(--foam); }
  .cs-board-matcha h2 { color: var(--matcha-deep); }
  .cs-lede { font-size: 15px; }
  .cs-prices { list-style: none; margin: 0 0 8px; padding: 0; }
  .cs-prices li { display: flex; align-items: baseline; gap: 8px; padding: 8px 0; font-size: 17px; margin: 0; }
  .cs-prices .cs-item { font-weight: 600; }
  .cs-prices .cs-dots { flex: 1; border-bottom: 2px dotted rgba(42,38,22,.35); transform: translateY(-4px); min-width: 20px; }
  .cs-prices .cs-price { font-family: var(--display); font-weight: 800; font-size: 19px; }
  .cs h3.cs-sub { font-family: var(--display); font-weight: 600; font-size: 18px; margin: 22px 0 10px; }
  .cs-group { margin: 0 0 14px; }
  .cs-group-name { font-size: 14px; font-weight: 700; margin: 0 0 6px; color: #6b5a12; }
  .cs-chips { display: flex; flex-wrap: wrap; gap: 6px; list-style: none; margin: 0; padding: 0; }
  .cs-chips li {
    margin: 0; padding: 5px 12px; border-radius: 999px; font-size: 14px;
    background: #fff; border: 1.5px solid var(--ink);
  }
  .cs-note {
    margin: 0; padding: 14px 16px; border-radius: 16px; background: #fff; font-size: 14px;
    border: 1.5px dashed var(--matcha);
  }

  /* Store info */
  .cs-info { border: 2px solid var(--ink); border-radius: 28px; padding: 26px 22px; margin: 0 0 30px; background: #fff; }
  .cs-info dl { margin: 0; display: grid; grid-template-columns: 120px 1fr; gap: 12px 16px; }
  .cs-info dt { font-weight: 700; font-size: 14px; color: #6b6550; }
  .cs-info dd { margin: 0; font-size: 16px; }
  .cs-map {
    display: inline-block; margin-top: 18px; padding: 10px 18px; border-radius: 999px;
    background: var(--banana); color: var(--ink) !important; font-weight: 700; text-decoration: none;
    border: 2px solid var(--ink);
  }

  @media (max-width: 520px) {
    .cs-brand { column-gap: 12px; padding: 16px 16px 16px 18px; }
    .cs-goggle { width: 58px; height: 58px; font-size: 26px; border-width: 6px; }
    .cs-brand::before { width: 40px; height: 11px; }
    .cs-brand-name { font-size: 20px; }
    .cs-counters { grid-template-columns: 1fr; }
    .cs-counter + .cs-counter { border-left: 0; border-top: 2px solid var(--ink); }
    .cs-info dl { grid-template-columns: 1fr; gap: 2px; }
    .cs-info dd { margin-bottom: 10px; }
  }

  /* Review items (drinks & pies) */
  .cs-items { list-style: none; margin: 0; padding: 0; display: grid; gap: 12px; }
  .cs-items > li { margin: 0; background: #fff; border: 1.5px solid var(--ink); border-radius: 18px; padding: 16px 18px; }
  .cs-items-head { display: flex; flex-wrap: wrap; align-items: center; gap: 8px 10px; margin-bottom: 6px; }
  .cs-items h3 { font-family: var(--display); font-weight: 800; font-size: 19px; line-height: 1.2; margin: 0; }
  .cs-tag { font-size: 12px; font-weight: 700; padding: 3px 10px; border-radius: 999px; border: 1.5px solid var(--ink); }
  .cs-board-matcha .cs-tag { background: var(--foam); color: var(--matcha-deep); }
  .cs-board-banana .cs-tag { background: var(--pudding); color: #6b5a12; }
  .cs-items p { margin: 0; font-size: 15px; }
  .cs-crosslink { margin: 0 0 16px; padding: 14px 16px; border-radius: 16px; background: var(--pudding); font-size: 14px; border: 1.5px dashed #C9A21B; }

  /* VE/LA additions */
  .cs-items .cs-chips { margin-top: 10px; }
  .cs-items .cs-chips li { font-size: 13px; padding: 4px 10px; }
  .cs-board-matcha .cs-items .cs-chips li { background: var(--foam); }
  .cs-special { background: #fff; border: 1.5px solid var(--ink); border-radius: 18px; padding: 16px 18px; margin: 6px 0 4px; }
  .cs-special-head { display: flex; flex-wrap: wrap; align-items: center; gap: 8px 10px; margin-bottom: 6px; }
  .cs-special h4 { font-family: var(--display); font-weight: 800; font-size: 18px; line-height: 1.2; margin: 0; }
  .cs-special p { margin: 0; font-size: 15px; }
  .cs-special + .cs-special { margin-top: 12px; }
  .cs-special-price { margin-left: auto; font-family: var(--display); font-weight: 800; font-size: 19px; white-space: nowrap; }
  .cs-also { margin: 4px 0 0; font-size: 14px; }
  .cs-also .cs-chips { margin-top: 6px; }
  .cs-board .cs-note { margin-top: 18px; }
  .cs-prices .cs-price { white-space: nowrap; }
  .cs-prices .cs-item small { font-weight: 400; font-size: 13px; color: #6b6550; }

  /* Ippodo additions */
  .cs-prices .cs-item small.cs-jp { font-weight: 400; font-size: 13px; color: #6b6550; margin-left: 4px; }
  .cs-prices .cs-item .cs-tag { margin-left: 6px; font-size: 11px; padding: 2px 8px; vertical-align: 2px; white-space: nowrap; }
  .cs-limited { display: inline-block; margin: 0 0 6px; font-size: 13px; font-weight: 700; padding: 4px 12px; border-radius: 999px; background: var(--ink); color: var(--banana); }
  .cs-items .cs-prices { margin: 8px 0 10px; }
  .cs-items .cs-prices li { font-size: 15px; padding: 5px 0; }
  .cs-items .cs-prices .cs-price { font-size: 16px; }
  .cs-mini-head { font-size: 13px; font-weight: 700; color: #6b6550; margin: 10px 0 0 !important; }
  /* Autumn promo */
  .cs-promo { margin-top: 16px; border: 2px solid var(--ink); border-radius: 16px; overflow: hidden; background: #FFF1E3; }
  .cs-promo-head { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 6px 10px; padding: 12px 14px; background: #D2692E; color: #fff; border-bottom: 2px solid var(--ink); }
  .cs-promo-badge { font-family: var(--display); font-weight: 800; font-size: 17px; }
  .cs-promo-sub { font-size: 13px; font-weight: 700; }
  .cs-tiers { list-style: none; margin: 0; padding: 0; }
  .cs .cs-tiers li { display: grid; grid-template-columns: 118px 1fr; gap: 12px; align-items: baseline; margin: 0; padding: 11px 14px; font-size: 15px; }
  .cs .cs-tiers li + li { border-top: 1.5px dashed rgba(42,38,22,.3); }
  .cs-spend { font-family: var(--display); font-weight: 800; font-size: 16px; color: #A94A18; white-space: nowrap; }
  .cs-gift small { color: #6b6550; font-size: 13px; }
  @media (max-width: 520px) { .cs .cs-tiers li { grid-template-columns: 1fr; gap: 2px; } }

  /* KOKO KAWANE additions */
  .cs-special h4 small.cs-jp { font-family: var(--body); font-weight: 400; font-size: 13px; color: #6b6550; margin-left: 4px; }
  .cs-special .cs-chips { margin-top: 10px; }
  .cs-special .cs-chips li { font-size: 13px; padding: 3px 10px; }
  .cs-board-matcha .cs-special .cs-chips li { background: var(--foam); }
  .cs-board-banana .cs-special .cs-chips li { background: var(--pudding); }
  .cs-special-head .cs-tag { white-space: nowrap; }
  .cs-mill { background: var(--matcha); color: #fff; border: 2px solid var(--ink); border-radius: 18px; padding: 16px 18px; margin-bottom: 6px; }
  .cs-mill-head { display: flex; flex-wrap: wrap; align-items: baseline; gap: 6px 10px; margin-bottom: 6px; }
  .cs-mill h4 { font-family: var(--display); font-weight: 800; font-size: 19px; margin: 0; color: #fff; }
  .cs-mill .cs-special-price { color: var(--banana); }
  .cs-mill p { margin: 0; font-size: 15px; }
  .cs-mill small { opacity: .85; }
  .cs-promo-dark .cs-promo-head { background: var(--ink); color: var(--banana); }
  .cs-promo-dark { background: #fff; }
  .cs-collect { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; list-style: none; margin: 0; padding: 14px; }
  .cs .cs-collect li { margin: 0; padding: 14px 12px; border: 1.5px solid var(--ink); border-radius: 16px; background: var(--pudding); text-align: center; }
  .cs .cs-collect li.cs-secret { background: var(--ink); color: #fff; }
  .cs-collect strong { display: block; font-family: var(--display); font-size: 16px; line-height: 1.2; margin-bottom: 4px; }
  .cs-collect span { font-size: 13px; }
  .cs-collect .cs-collect-emoji { display: block; font-size: 28px; margin-bottom: 6px; }
  .cs-promo-body { padding: 14px 14px 0; font-size: 15px; }
  .cs-promo-body p { margin: 0; }
  @media (max-width: 520px) { .cs-collect { grid-template-columns: 1fr; } }
  .cs-steps { list-style: none; counter-reset: step; margin: 0; padding: 0; display: grid; gap: 12px; }
  .cs-steps > li {
    counter-increment: step; position: relative; margin: 0;
    background: #fff; border: 1.5px solid var(--ink); border-radius: 18px;
    padding: 16px 18px 16px 70px;
  }
  .cs-steps > li::before {
    content: counter(step); position: absolute; left: 16px; top: 14px;
    width: 38px; height: 38px; border-radius: 50%; display: grid; place-items: center;
    font-family: var(--display); font-weight: 800; font-size: 19px;
    background: var(--banana); border: 2px solid var(--ink); color: var(--ink);
  }
  .cs-steps h4 { font-family: var(--display); font-weight: 800; font-size: 18px; line-height: 1.2; margin: 0 0 4px; }
  .cs-steps p { margin: 0; font-size: 15px; }
  .cs-steps ul { margin: 8px 0 0; padding-left: 18px; font-size: 15px; }
  .cs-steps ul li { margin: 0 0 4px; }
  @media (max-width: 520px) {
    .cs-steps > li { padding: 58px 16px 16px; }
    .cs-steps > li::before { top: 12px; }
  }
  .cs-steps .cs-tag { margin-left: 8px; font-size: 11px; padding: 2px 8px; vertical-align: 3px; background: var(--banana); }

  /* Showdown rounds */
  .cs-round { background: #fff; border: 1.5px solid var(--ink); border-radius: 18px; overflow: hidden; }
  .cs-round + .cs-round { margin-top: 14px; }
  .cs-round-head { padding: 12px 16px; border-bottom: 1.5px solid var(--ink); }
  .cs-round-head span { display: block; font-size: 12px; font-weight: 700; color: #6b6550; }
  .cs-round-head h3 { font-family: var(--display); font-weight: 800; font-size: 19px; line-height: 1.2; margin: 0; }
  .cs-vs { display: grid; grid-template-columns: 1fr 1fr; }
  .cs-vs > div { padding: 14px 16px; font-size: 15px; }
  .cs-vs > div + div { border-left: 1.5px solid var(--ink); }
  .cs-vs-std { background: var(--pudding); }
  .cs-vs-sas { background: var(--foam); }
  .cs-vs strong { display: block; font-family: var(--display); font-size: 15px; margin-bottom: 4px; }
  .cs-vs-sas strong { color: var(--matcha-deep); }
  .cs-vs p { margin: 0; }
  @media (max-width: 520px) {
    .cs-vs { grid-template-columns: 1fr; }
    .cs-vs > div + div { border-left: 0; border-top: 1.5px solid var(--ink); }
  }

  /* Highball additions */
  .cs-info .cs-collect { padding: 6px 0 18px; }
  .cs-info .cs-collect strong { font-size: 20px; }
  .cs-prices .cs-item .cs-tag { margin-left: 6px; font-size: 11px; padding: 2px 8px; vertical-align: 2px; white-space: nowrap; background: var(--banana); }

  /* Magnolia vs Marigold additions */
  .cs-vs strong .cs-win { margin-left: 6px; }
  .cs-win { display: inline-block; font-family: var(--body); font-size: 11px; font-weight: 700; padding: 2px 8px; border-radius: 999px; background: var(--ink); color: var(--banana); vertical-align: 2px; white-space: nowrap; }
  .cs-vs-std strong, .cs-vs-sas strong { font-size: 16px; }
  .cs-vs .cs-big { display: block; font-family: var(--display); font-weight: 800; font-size: 26px; line-height: 1.1; margin: 2px 0 4px; }
  .cs-round-sub { padding: 10px 16px; border-top: 1.5px solid var(--ink); border-bottom: 1.5px solid var(--ink); background: #fff; font-size: 13px; font-weight: 700; color: #6b6550; }
  .cs-round-note { padding: 12px 16px; font-size: 15px; border-bottom: 1.5px solid var(--ink); }
  .cs-round-head + .cs-round-sub { border-top: 0; }
  .cs-table-wrap { overflow-x: auto; margin: 0 0 4px; }
  .cs-table { width: 100%; border-collapse: separate; border-spacing: 0; font-size: 15px; border: 1.5px solid var(--ink); border-radius: 16px; overflow: hidden; }
  .cs-table th, .cs-table td { padding: 10px 12px; text-align: left; vertical-align: top; border-bottom: 1px solid rgba(42,38,22,.2); }
  .cs-table tr:last-child th, .cs-table tr:last-child td { border-bottom: 0; }
  .cs-table thead th { font-family: var(--display); font-weight: 800; font-size: 15px; border-bottom: 1.5px solid var(--ink); }
  .cs-table thead th:nth-child(2) { background: var(--banana); }
  .cs-table thead th:nth-child(3) { background: var(--matcha); color: #fff; }
  .cs-table tbody th { font-weight: 700; font-size: 14px; color: #6b6550; background: #fff; width: 32%; }
  .cs-table td:nth-child(2) { background: var(--pudding); }
  .cs-table td:nth-child(3) { background: var(--foam); }
  .cs-picks { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
  .cs-pick { border: 2px solid var(--ink); border-radius: 18px; padding: 16px 18px; }
  .cs-pick-magnolia { background: var(--banana); }
  .cs-pick-marigold { background: var(--matcha); color: #fff; }
  .cs-pick h3 { font-family: var(--display); font-weight: 800; font-size: 19px; line-height: 1.2; margin: 0 0 8px; }
  .cs-pick ul { margin: 0; padding-left: 18px; font-size: 15px; }
  .cs-pick li { margin: 0 0 4px; }
  @media (max-width: 520px) { .cs-picks { grid-template-columns: 1fr; } }
  .cs-table tr.cs-table-group th { background: #fff; font-family: var(--display); font-weight: 800; font-size: 14px; color: var(--ink); border-top: 1.5px solid var(--ink); }
  .cs-ingredients { font-size: 14px !important; }

  /* KFC Oreo additions */
  .cs-counter-ink { background: var(--ink); color: var(--banana); }
  .cs-counter-ink span.cs-from { color: #fff; }
  .cs-vs-dark { background: var(--ink); color: #fff; }
  .cs-vs .cs-vs-dark strong { color: var(--banana); }
  .cs-glass-wrap { display: grid; grid-template-columns: 150px 1fr; gap: 20px; align-items: center; margin: 4px 0 8px; }
  .cs-glass { display: flex; flex-direction: column; border: 2px solid var(--ink); border-top: 0; border-radius: 0 0 26px 26px; overflow: hidden; height: 230px; background: #fff; }
  .cs-glass div { display: grid; place-items: center; font-size: 12px; font-weight: 700; text-align: center; padding: 0 6px; border-top: 1.5px dashed rgba(42,38,22,.35); }
  .cs-glass .g-foam { flex: 1.1; background: #FBE3B6; color: var(--ink); border-top: 0; }
  .cs-glass .g-matcha { flex: 1; background: #7FA03A; color: #fff; }
  .cs-glass .g-milk { flex: 1.3; background: #FFFBF0; color: var(--ink); }
  .cs-glass .g-base { flex: 1; background: #2B2420; color: #fff; }
  .cs-glass-key { list-style: none; margin: 0; padding: 0; display: grid; gap: 10px; }
  .cs .cs-glass-key li { margin: 0; font-size: 15px; display: flex; gap: 10px; align-items: baseline; }
  .cs-swatch { flex: none; width: 14px; height: 14px; border-radius: 4px; border: 1.5px solid var(--ink); transform: translateY(2px); }
  @media (max-width: 520px) { .cs-glass-wrap { grid-template-columns: 110px 1fr; gap: 14px; } .cs-glass { height: 200px; } }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Recipe",
      "name": "Fried Chicken Matcha Latte (KFC Oreo Edition)",
      "description": "A spooky layered Halloween drink featuring a rich black Oreo cookie paste base, Hokkaido milk, ceremonial Naoki Matcha, and a savoury KFC Fried Chicken cold foam cap.",
      "image": "https://img.youtube.com/vi/7uve1jeHDnM/hqdefault.jpg",
      "author": {
        "@type": "Person",
        "name": "minionxmatcha"
      },
      "recipeCategory": "Beverage",
      "recipeCuisine": "Fusion",
      "recipeYield": "1 drink",
      "keywords": "matcha, kfc oreo, fried chicken matcha latte, halloween drink recipe, savoury cold foam",
      "recipeIngredient": [
        "3–4 KFC × Oreo sandwich cookies",
        "120ml Yotsuba Hokkaido Whole Milk (divided)",
        "3–4g Naoki Matcha (Chiyo no Shiro)",
        "30ml water at 80°C",
        "50ml whipping cream or thickened heavy cream",
        "Ice cubes",
        "Candy googly eyes"
      ],
      "recipeInstructions": [
        { "@type": "HowToStep", "name": "Dissect the cookies", "text": "Twist open the KFC Oreos. Scrape the orange savoury filling into a frothing vessel and keep the black chocolate wafers separate." },
        { "@type": "HowToStep", "name": "Blend the black base", "text": "Blend the dark wafers with a splash of Hokkaido milk until smooth and velvety. Pour into the bottom of your serving glass." },
        { "@type": "HowToStep", "name": "Whip the savoury foam", "text": "Add heavy cream to the orange filling. Whisk or shake vigorously until it reaches a thick, pourable cold foam consistency." },
        { "@type": "HowToStep", "name": "Whisk the matcha", "text": "Sift 3–4g of ceremonial matcha into a chawan and whisk briskly with 30ml of 80°C water using a bamboo chasen until an even micro-foam appears." },
        { "@type": "HowToStep", "name": "Layer and garnish", "text": "Add ice over the black Oreo paste, pour in the Hokkaido milk, gently pour over the matcha, and top with the savoury fried chicken cream foam. Garnish with an Oreo monster topped with candy eyes." }
      ]
    },
    {
      "@type": "VideoObject",
      "name": "Fried Chicken Matcha Latte: KFC Oreo Halloween Drink",
      "description": "Making a Halloween layered drink with KFC x Oreo fried chicken cookies, Yotsuba Hokkaido milk, and Naoki Matcha.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/7uve1jeHDnM/hqdefault.jpg"
      ],
      "uploadDate": "2026-10-25",
      "contentUrl": "https://www.youtube.com/shorts/7uve1jeHDnM",
      "embedUrl": "https://www.youtube.com/embed/7uve1jeHDnM"
    }
  ]
}
</script>

<div class="cs">

  <!-- Brand strip -->
  <div class="cs-brand">
    <div class="cs-goggle" aria-hidden="true">🍵</div>
    <div class="cs-brand-text">
    <div class="cs-brand-name">minionxmatcha</div>
    <p class="cs-tagline">Matcha reviews, cafe walkthroughs & tea guides in Singapore</p>
    <nav class="cs-social" aria-label="minionxmatcha on social media">
      <a class="cs-ig" href="https://www.instagram.com/minionxmatcha" target="_blank" rel="noopener">Instagram</a>
      <a class="cs-tt" href="https://www.tiktok.com/@minionxmatcha" target="_blank" rel="noopener">TikTok</a>
      <a class="cs-fb" href="https://www.facebook.com/p/Minionxmatcha-61592062657121/" target="_blank" rel="noopener">Facebook</a>
      <a class="cs-yt" href="https://www.youtube.com/@minionxmatcha" target="_blank" rel="noopener">YouTube</a>
    </nav>
    </div>
  </div>

  <!-- Hero: one cookie, split in two -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">Fried Chicken Matcha Latte: Viral KFC Oreo Halloween Creation</h1>
      <p class="cs-where">One cookie, two layers · Halloween recipe & taste review</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-ink" href="#recipe" style="text-decoration:none;color:var(--banana);">
        <span class="cs-counter-emoji" aria-hidden="true">🍪</span>
        <strong>Black wafers</strong>
        <span class="cs-from">Blended into a dark Oreo milk base</span>
      </a>
      <a class="cs-counter cs-counter-banana" href="#recipe" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🍗</span>
        <strong>Savoury filling</strong>
        <span class="cs-from">Whipped into a fried chicken cold foam</span>
      </a>
    </div>
  </header>

  <p>Halloween is the season for culinary mad science. When the viral <strong>KFC × Oreo Fried Chicken Flavoured Sandwich Cookie</strong> landed, its combination of sweet chocolate wafers and peppery, savoury filling sparked massive debate.</p>
  <p>Instead of eating it whole, I broke down its elements: turning the cocoa wafers into a dark base and whipping the spiced cream into a rich, savoury cold foam on top of ceremonial matcha.</p>

  <p class="cs-crosslink">🎃 <strong>Want to make it?</strong> Jump straight to the <a href="#recipe">ingredients and 5-step method</a>.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video walkthrough</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/De5w364OpDs/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/De5w364OpDs/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/7uve1jeHDnM"
        title="Fried Chicken Matcha Latte: KFC Oreo Halloween Drink"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSgxYasqy/" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/share/r/1F1EAWqvRE/" target="_blank" rel="noopener">watch on Facebook</a>
    </p>
  </section>

  <!-- Tasting review -->
  <section class="cs-board cs-board-banana">
    <h2>👅 Tasting review: what does the KFC Oreo taste like?</h2>
    <p class="cs-lede">The KFC Oreo is a bizarre, polarising novelty where a standard sweet cocoa wafer clashes directly with a heavily spiced, MSG-forward savoury filling.</p>

    <div class="cs-round">
      <div class="cs-round-head"><span>The brain-break moment</span><h3>Aroma vs taste</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-std"><strong>👃 The smell</strong><p>Just like an everyday chocolate Oreo. Zero chicken aroma and no fried-oil scent.</p></div>
        <div class="cs-vs-dark"><strong>👅 The taste</strong><p>The shock hits the moment you reach the orange-tinted filling. Classic sweet vanilla is replaced by a purely savoury profile (纯咸口的).</p></div>
      </div>
    </div>

    <h3 class="cs-sub">Flavour profile</h3>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Spices & heat</h4></div>
      <p>Rather than tasting like actual meat, the "11 secret herbs and spices" cream is closer to savoury Asian snack seasonings.</p>
      <ul class="cs-chips" aria-label="Flavour notes"><li>Sharp white pepper</li><li>Prominent garlic powder</li><li>Gentle lingering heat</li></ul>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Tastes like…</h4></div>
      <p>Instant noodle seasoning packets (ramen powder), or crunchy Asian chicken-foot biscuit snacks (ขนมขาไก่).</p>
    </div>

    <h3 class="cs-sub">Why deconstructing it works for matcha</h3>
    <p class="cs-lede">The filling delivers concentrated white pepper, salt and garlic while the wafers stay pure chocolate, so separating them makes sense.</p>
    <div class="cs-round">
      <div class="cs-vs">
        <div class="cs-vs-dark"><strong>🍪 The wafers</strong><p>Become a luscious chocolate milk pudding layer at the bottom.</p></div>
        <div class="cs-vs-std"><strong>🍗 The filling</strong><p>Whipped with heavy cream, it works like a spiced cheese foam or salted cream cap, contrasting the earthy umami of whisked matcha.</p></div>
      </div>
    </div>
  </section>

  <!-- Recipe -->
  <section class="cs-board cs-board-matcha" id="recipe">
    <h2>🎃 Recipe: the layered monster latte</h2>

    <h3 class="cs-sub">How the layers stack</h3>
    <div class="cs-glass-wrap">
      <div class="cs-glass" aria-hidden="true">
        <div class="g-foam">Chicken foam</div>
        <div class="g-matcha">Matcha</div>
        <div class="g-milk">Milk + ice</div>
        <div class="g-base">Oreo base</div>
      </div>
      <ul class="cs-glass-key" aria-label="Layers from top to bottom">
        <li><span class="cs-swatch" style="background:#FBE3B6"></span><span><strong>Top:</strong> savoury fried chicken cold foam, plus an Oreo monster with candy eyes</span></li>
        <li><span class="cs-swatch" style="background:#7FA03A"></span><span><strong>Matcha:</strong> Naoki Chiyo no Shiro, freshly whisked</span></li>
        <li><span class="cs-swatch" style="background:#FFFBF0"></span><span><strong>Milk:</strong> Yotsuba Hokkaido whole milk over ice</span></li>
        <li><span class="cs-swatch" style="background:#2B2420"></span><span><strong>Bottom:</strong> black Oreo wafer paste</span></li>
      </ul>
    </div>

    <h3 class="cs-sub">Ingredients</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">KFC × Oreo sandwich cookies</span><span class="cs-dots"></span><span class="cs-price">3–4</span></li>
      <li><span class="cs-item">Yotsuba Hokkaido Whole Milk <small>(divided)</small></span><span class="cs-dots"></span><span class="cs-price">120ml</span></li>
      <li><span class="cs-item">Naoki Matcha <small>(Chiyo no Shiro)</small></span><span class="cs-dots"></span><span class="cs-price">3–4g</span></li>
      <li><span class="cs-item">Water at 80°C</span><span class="cs-dots"></span><span class="cs-price">30ml</span></li>
      <li><span class="cs-item">Whipping cream <small>(or thickened heavy cream)</small></span><span class="cs-dots"></span><span class="cs-price">50ml</span></li>
      <li><span class="cs-item">Ice cubes & candy googly eyes</span><span class="cs-dots"></span><span class="cs-price">To serve</span></li>
    </ul>

    <h3 class="cs-sub">Method</h3>
    <ol class="cs-steps">
      <li>
        <h4>Dissect the cookies</h4>
        <p>Twist open the KFC Oreos. Scrape the orange savoury filling into a frothing vessel and keep the black chocolate wafers separate.</p>
      </li>
      <li>
        <h4>Blend the black base</h4>
        <p>Blend the dark wafers with a splash of the Hokkaido milk in a personal blender until smooth and velvety. Pour into the bottom of your serving glass.</p>
      </li>
      <li>
        <h4>Whip the savoury foam</h4>
        <p>Add the heavy cream to the orange filling. Whisk or shake vigorously until it reaches a thick, pourable cold foam consistency.</p>
      </li>
      <li>
        <h4>Whisk the matcha</h4>
        <p>Sift 3–4g of matcha into a chawan, add 30ml of 80°C water and whisk briskly with a bamboo chasen until an even micro-foam appears.</p>
      </li>
      <li>
        <h4>Layer & garnish</h4>
        <p>Add ice over the black Oreo paste, pour in the rest of the Hokkaido milk, then gently pour over the matcha. Top with the savoury fried chicken foam and dip an Oreo monster with candy eyes into the froth.</p>
      </li>
    </ol>
  </section>

</div>
