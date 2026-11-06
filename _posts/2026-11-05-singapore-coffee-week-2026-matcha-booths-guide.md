---
layout: post
title: "Singapore Coffee Week 2026: Complete Matcha Booths & Price Guide"
date: 2026-11-05
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

  /* Coffee Week additions */
  .cs-booth { display: inline-block; margin: 0 0 8px; font-size: 13px; font-weight: 700; padding: 4px 12px; border-radius: 999px; background: var(--ink); color: var(--banana); }
  .cs-board > p.cs-lede:first-of-type { margin-top: -4px; }
  .cs-dir { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; list-style: none; margin: 0 0 28px; padding: 0; }
  .cs .cs-dir li { margin: 0; }
  .cs .cs-dir a { display: block; height: 100%; padding: 10px 12px; border: 1.5px solid var(--ink); border-radius: 14px; background: #fff; color: var(--ink); text-decoration: none; font-size: 14px; font-weight: 700; line-height: 1.25; }
  .cs .cs-dir a span { display: block; font-size: 12px; font-weight: 700; color: #6b6550; margin-bottom: 2px; }
  .cs .cs-dir a:hover { background: var(--pudding); }
  .cs-prices .cs-item .cs-num { display: inline-block; min-width: 26px; font-weight: 700; color: #6b6550; }
  .cs-prices .cs-was { font-size: 14px; font-weight: 400; color: #6b6550; text-decoration: line-through; margin-right: 6px; font-family: var(--body); }
  .cs-chips li.cs-chip-plain { background: transparent; border-style: dashed; }
  .cs-table-moss tbody th { width: 46%; color: var(--ink); }
  .cs-table-moss td { text-align: right; white-space: nowrap; }
  .cs-table-moss thead th { text-align: right; }
  .cs-table-moss small { display: block; font-weight: 400; color: #6b6550; font-size: 12px; }
  .cs-table-moss tbody tr.cs-table-group th { width: auto; }
  .cs-special .cs-special-price small { font-family: var(--body); font-weight: 400; font-size: 13px; color: #6b6550; }
  .cs-special .cs-chips + p, .cs-special p + .cs-chips { margin-top: 10px; }
  .cs-special .cs-tag-row { display: flex; flex-wrap: wrap; gap: 6px; margin: 0 0 8px; }
  @media (max-width: 600px) { .cs-dir { grid-template-columns: repeat(2, 1fr); } }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Event",
      "name": "Singapore Coffee Week 2026",
      "description": "Complete guide to every matcha booth, drink menu, and retail tea tin price at Singapore Coffee Week 2026 at Marina Bay Sands Expo & Convention Centre.",
      "image": "https://img.youtube.com/vi/pb7sEMwnWfs/hqdefault.jpg",
      "startDate": "2026-11-05",
      "endDate": "2026-11-08",
      "eventAttendanceMode": "https://schema.org/OfflineEventAttendanceMode",
      "eventStatus": "https://schema.org/EventScheduled",
      "location": {
        "@type": "Place",
        "name": "Sands Expo & Convention Centre, Level 1, Hall C",
        "address": {
          "@type": "PostalAddress",
          "streetAddress": "10 Bayfront Avenue",
          "addressLocality": "Singapore",
          "postalCode": "018956",
          "addressCountry": "SG"
        }
      },
      "organizer": {
        "@type": "Organization",
        "name": "Singapore Coffee Week",
        "url": "https://www.marinabaysands.com"
      },
      "performer": {
        "@type": "Organization",
        "name": "OHMATCHA, Moss Matcha, HIKA.GEN, Hello Arigato, Grounded Pleasures"
      },
      "offers": {
        "@type": "Offer",
        "price": "0",
        "priceCurrency": "SGD",
        "availability": "https://schema.org/InStock",
        "url": "https://minionxmatcha.github.io/2026/11/05/singapore-coffee-week-2026-matcha-booths-guide.html"
      }
    },
    {
      "@type": "VideoObject",
      "name": "Coffee Week Singapore 2026 Matcha Hunting Guide",
      "description": "Hunting for matcha at Singapore Coffee Week 2026 across OHMATCHA, Grounded Pleasures, Moss Matcha, HIKA.GEN Kagoshima, Hello Arigato, and Cheerful Goat.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/pb7sEMwnWfs/hqdefault.jpg"
      ],
      "uploadDate": "2026-11-05",
      "contentUrl": "https://www.youtube.com/shorts/pb7sEMwnWfs",
      "embedUrl": "https://www.youtube.com/embed/pb7sEMwnWfs"
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

  <!-- Hero -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">Singapore Coffee Week 2026: Every Matcha Booth & Price</h1>
      <p class="cs-where">Sands Expo Hall C · 5 – 8 Nov 2026 · 6 booths</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-matcha" href="#booths" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">🥤</span>
        <strong>Drinks</strong>
        <span class="cs-from">From $6.50 to $25</span>
      </a>
      <a class="cs-counter cs-counter-banana" href="#booths" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🥫</span>
        <strong>Tins & boxes</strong>
        <span class="cs-from">From $16 to $120</span>
      </a>
    </div>
  </header>

  <p>Even at <strong>Singapore Coffee Week 2026</strong>, held at Marina Bay Sands Expo & Convention Centre (Level 1, Hall C) from <strong>5 to 8 November 2026</strong>, there is plenty for matcha lovers to explore. From $120 Kyoto single-origin tins to $18 organic Kagoshima matcha and $21 100g flavoured matcha boxes, here is the complete booth-by-booth price guide.</p>

  <!-- Booth directory -->
  <nav aria-label="Jump to a booth" id="booths">
    <ul class="cs-dir">
      <li><a href="#ohmatcha"><span>Booth 920</span>OHMATCHA</a></li>
      <li><a href="#grounded"><span>Booth 526</span>Grounded Pleasures</a></li>
      <li><a href="#moss"><span>Booth 112</span>Moss Matcha</a></li>
      <li><a href="#hikagen"><span>Booth 909</span>HIKA.GEN</a></li>
      <li><a href="#hello-arigato"><span>Booth 605</span>Hello Arigato</a></li>
      <li><a href="#cheerful-goat"><span>Booth 603</span>Cheerful Goat</a></li>
    </ul>
  </nav>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video walkthrough</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DfXL-NzpeFG/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DfXL-NzpeFG/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/pb7sEMwnWfs"
        title="Coffee Week Singapore 2026 Matcha Guide"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSpjLupXA/" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/share/r/19w1kMZQbm/" target="_blank" rel="noopener">watch on Facebook</a>
    </p>
  </section>

  <!-- 1. OHMATCHA -->
  <section class="cs-board cs-board-matcha" id="ohmatcha">
    <span class="cs-booth">Booth 920</span>
    <h2>🇯🇵 OHMATCHA (Japan)</h2>
    <p class="cs-lede">Multi-region Japanese matcha drinks and ultra-premium retail tins.</p>

    <h3 class="cs-sub">Lattes</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Iced Matcha Latte <small>(Uji matcha from Ippodo Tea Co. & Marukyu Koyamaen)</small></span><span class="cs-dots"></span><span class="cs-price">$11.00</span></li>
      <li><span class="cs-item">Iced Hojicha Latte</span><span class="cs-dots"></span><span class="cs-price">$9.00</span></li>
    </ul>

    <h3 class="cs-sub">Straight matcha (usucha by region)</h3>
    <ul class="cs-prices">
      <li><span class="cs-item"><span class="cs-num">#1</span>Ise, Mie</span><span class="cs-dots"></span><span class="cs-price">$9.00</span></li>
      <li><span class="cs-item"><span class="cs-num">#2</span>Kawane, Shizuoka</span><span class="cs-dots"></span><span class="cs-price">$11.00</span></li>
      <li><span class="cs-item"><span class="cs-num">#3</span>Yame, Fukuoka</span><span class="cs-dots"></span><span class="cs-price">$11.00</span></li>
      <li><span class="cs-item"><span class="cs-num">#4</span>Nishio, Aichi</span><span class="cs-dots"></span><span class="cs-price">$13.00</span></li>
      <li><span class="cs-item"><span class="cs-num">#5</span>Ujitawaramachi, Kyoto</span><span class="cs-dots"></span><span class="cs-price">$25.00</span></li>
    </ul>

    <h3 class="cs-sub">Retail tins</h3>
    <ul class="cs-prices">
      <li><span class="cs-item"><span class="cs-num">#4</span>Nishio, Aichi <small>30g</small></span><span class="cs-dots"></span><span class="cs-price">$80.00</span></li>
      <li><span class="cs-item"><span class="cs-num">#2</span>Ujitawara, Kyoto <small>20g</small></span><span class="cs-dots"></span><span class="cs-price">$120.00</span></li>
    </ul>
  </section>

  <!-- 2. Grounded Pleasures -->
  <section class="cs-board cs-board-banana" id="grounded">
    <span class="cs-booth">Booth 526</span>
    <h2>🍓 Grounded Pleasures</h2>
    <ul class="cs-prices">
      <li><span class="cs-item">100g flavoured matcha box <span class="cs-tag">Launch promo</span></span><span class="cs-dots"></span><span class="cs-price"><span class="cs-was">$26.00</span>$21.00</span></li>
    </ul>
    <h3 class="cs-sub">Flavours</h3>
    <ul class="cs-chips"><li>Exquisite Strawberry Matcha</li><li>Vanilla Matcha</li><li>Raspberry Matcha</li></ul>
    <p class="cs-note">All three are gluten-free, vegan and organic.</p>
  </section>

  <!-- 3. Moss Matcha -->
  <section class="cs-board cs-board-matcha" id="moss">
    <span class="cs-booth">Booth 112</span>
    <h2>🌿 Moss Matcha (Singapore)</h2>
    <p class="cs-lede">A local specialty brand with an interactive sensory bar where you can inspect and smell cultivars from <strong>Uji, Japan</strong> and <strong>Hangzhou, China</strong>.</p>

    <div class="cs-table-wrap">
      <table class="cs-table cs-table-moss">
        <thead>
          <tr><td></td><th scope="col">Usucha</th><th scope="col">Latte</th></tr>
        </thead>
        <tbody>
          <tr class="cs-table-group"><th scope="rowgroup" colspan="3">🇯🇵 Uji, Japan</th></tr>
          <tr><th scope="row">Unmu no Mukashi<small>雲夢の昔</small></th><td>$8.50</td><td>$9.90</td></tr>
          <tr><th scope="row">Gyokuri no Mori<small>玉彩の森</small></th><td>—</td><td>$7.90</td></tr>
          <tr><th scope="row">Wakaba no Hikari<small>若葉の光</small></th><td>$7.50</td><td>$8.90</td></tr>
          <tr><th scope="row">Kazetake no Hikari<small>風竹の光</small></th><td>$6.50</td><td>$7.90</td></tr>
          <tr><th scope="row">Getsurin no Hana<small>月輪の花</small></th><td>$9.50</td><td>$10.90</td></tr>
          <tr class="cs-table-group"><th scope="rowgroup" colspan="3">🇨🇳 Hangzhou, China</th></tr>
          <tr><th scope="row">Moss Matcha Blend</th><td>—</td><td>$7.90</td></tr>
          <tr><th scope="row">Longjing Cuilu</th><td>—</td><td>$7.90</td></tr>
          <tr><th scope="row">Wuzao Xiaolu</th><td>$6.50</td><td>$7.90</td></tr>
        </tbody>
      </table>
    </div>
    <p class="cs-note">Lattes are made with koicha and milk. A dash means it's not offered as straight usucha.</p>

    <h3 class="cs-sub">Hojicha lattes ($6.90 each)</h3>
    <ul class="cs-chips"><li>Midori no In <span class="cs-hint">(medium-light roast)</span></li><li>Kohaku no Ka <span class="cs-hint">(medium roast)</span></li><li>Yaka no Ka <span class="cs-hint">(dark roast)</span></li></ul>
  </section>

  <!-- 4. HIKA.GEN -->
  <section class="cs-board cs-board-banana" id="hikagen">
    <span class="cs-booth">Booth 909 · at Lighthouse Coffee</span>
    <h2>🌋 HIKA.GEN (Kagoshima, Japan)</h2>
    <p class="cs-lede">Wallet-friendly, single-origin organic teas from Shibushi, Kagoshima.</p>

    <div class="cs-special">
      <div class="cs-special-head"><h4>Kasumi 霞 Ceremonial Matcha</h4><span class="cs-special-price">$24.00 <small>30g</small></span></div>
      <div class="cs-tag-row"><span class="cs-tag">1st harvest</span></div>
      <p>Smooth and elegant.</p>
      <ul class="cs-chips" aria-label="Tasting notes"><li>Sweet cream</li><li>Umami</li><li>Jasmine</li><li>White peach</li></ul>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Niwa 庭 Premium Matcha</h4><span class="cs-special-price">$18.00 <small>30g</small></span></div>
      <div class="cs-tag-row"><span class="cs-tag">1st & 2nd harvest</span></div>
      <p>Vibrant and balanced.</p>
      <ul class="cs-chips" aria-label="Tasting notes"><li>Steamed greens</li><li>Nori</li><li>Chestnut</li><li>Citrus</li></ul>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Nagomi 和 Premium Hojicha</h4><span class="cs-special-price">$16.00 <small>30g</small></span></div>
      <div class="cs-tag-row"><span class="cs-tag">1st & 2nd harvest</span></div>
      <p>Toasty and warm.</p>
      <ul class="cs-chips" aria-label="Tasting notes"><li>Roasted hazelnut</li><li>Dark cocoa</li><li>Brown sugar</li></ul>
    </div>

    <ul class="cs-prices" style="margin-top:14px;">
      <li><span class="cs-item">Complete 3-tin bundle <small>(all of the above)</small></span><span class="cs-dots"></span><span class="cs-price">$52.00</span></li>
    </ul>
  </section>

  <!-- 5. Hello Arigato -->
  <section class="cs-board cs-board-matcha" id="hello-arigato">
    <span class="cs-booth">Booth 605</span>
    <h2>☁️ Hello Arigato</h2>
    <p class="cs-lede">Serving <strong>single-origin Okumidori matcha</strong>: smooth, creamy and full of umami.</p>

    <h3 class="cs-sub">Matcha clouds</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Coconut Matcha Cloud</span><span class="cs-dots"></span><span class="cs-price">$6.50</span></li>
      <li><span class="cs-item">Strawberry Matcha Cloud</span><span class="cs-dots"></span><span class="cs-price">$7.50</span></li>
      <li><span class="cs-item">Coffee Matcha Cloud</span><span class="cs-dots"></span><span class="cs-price">$8.00</span></li>
    </ul>

    <h3 class="cs-sub">Lattes</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Matcha Latte <small>(hot / iced)</small></span><span class="cs-dots"></span><span class="cs-price">$7.00 / $8.00</span></li>
      <li><span class="cs-item">Iced Strawberry Matcha Latte</span><span class="cs-dots"></span><span class="cs-price">$9.00</span></li>
      <li><span class="cs-item">Iced Dirty Matcha Latte</span><span class="cs-dots"></span><span class="cs-price">$9.00</span></li>
    </ul>
  </section>

  <!-- 6. Cheerful Goat -->
  <section class="cs-board cs-board-banana" id="cheerful-goat">
    <span class="cs-booth">Booth 603</span>
    <h2>🐐 Cheerful Goat</h2>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Minion spotting 💛</h4><span class="cs-tag">Not matcha, but worth a stop</span></div>
      <p>Spot the yellow <strong>Minion-themed pocket coffee capsules</strong> alongside pink editions and interactive smoke-bubble blasters.</p>
    </div>
  </section>

  <!-- Event details -->
  <section class="cs-info">
    <h2>Event details</h2>
    <dl>
      <dt>Event</dt>
      <dd>Singapore Coffee Week 2026</dd>
      <dt>Dates</dt>
      <dd>5 – 8 November 2026</dd>
      <dt>Venue</dt>
      <dd>Marina Bay Sands Expo & Convention Centre<br>Level 1, Hall C, 10 Bayfront Avenue</dd>
    </dl>
    <a class="cs-map" href="https://www.google.com/maps/search/?api=1&query=Sands+Expo+and+Convention+Centre+10+Bayfront+Avenue+Singapore+018956" target="_blank" rel="noopener">Open in Google Maps</a>
  </section>

</div>
