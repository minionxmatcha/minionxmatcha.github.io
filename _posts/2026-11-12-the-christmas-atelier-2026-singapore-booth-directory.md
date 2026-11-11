---
layout: post
title: "The Christmas Atelier 2026 Singapore: Complete Booth Directory & Matcha Guide"
date: 2026-11-12
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

  /* Christmas Atelier additions */
  .cs-booth-list { list-style: none; margin: 0; padding: 0; display: grid; grid-template-columns: repeat(2, 1fr); gap: 8px; }
  .cs .cs-booth-list li { margin: 0; display: flex; align-items: center; justify-content: space-between; gap: 10px; padding: 9px 12px; background: #fff; border: 1.5px solid var(--ink); border-radius: 12px; font-size: 15px; }
  .cs-bname { font-weight: 600; line-height: 1.25; }
  .cs-bname a { font-weight: 400; font-size: 13px; margin-left: 4px; white-space: nowrap; }
  .cs-bnum { flex: none; font-size: 12px; font-weight: 700; padding: 3px 9px; border-radius: 999px; background: var(--banana); border: 1.5px solid var(--ink); white-space: nowrap; }
  .cs-bnum-show { background: var(--ink); color: var(--banana); }
  .cs-board .cs-booth-list + h3.cs-sub { margin-top: 26px; }
  .cs-board-xmas { background: var(--ink); color: #fff; }
  .cs-board-xmas h2 { color: var(--banana); }
  .cs-board-xmas .cs-lede { color: #e8e2c8; }
  .cs-board-xmas .cs-chips li { background: transparent; color: #fff; border-color: var(--banana); }
  .cs .cs-dir a .cs-count { display: inline; font-weight: 400; color: #6b6550; margin: 0 0 0 4px; font-size: 12px; }
  @media (max-width: 600px) { .cs-booth-list { grid-template-columns: 1fr; } }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Event",
  "name": "The Christmas Atelier 2026",
  "description": "Complete booth directory and brand guide for The Christmas Atelier 2026 at Marina Bay Sands Expo & Convention Centre, featuring over 130 F&B, matcha, specialty tea, fashion, beauty, and lifestyle brands.",
  "image": "https://minionxmatcha.github.io/assets/logo.png",
  "startDate": "2026-11-12",
  "endDate": "2026-11-14",
  "eventAttendanceMode": "https://schema.org/OfflineEventAttendanceMode",
  "eventStatus": "https://schema.org/EventScheduled",
  "location": {
    "@type": "Place",
    "name": "Marina Bay Sands Expo & Convention Centre, Level 1, Hall C",
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
    "name": "The Floral Atelier",
    "url": "https://www.thefloralatelier.co"
  },
  "performer": {
    "@type": "Organization",
    "name": "Kashinoki Matcha, Creamie Sippies, Antea Social, Hello Arigato, Mariage Frères Tea, Fossa Chocolate, Mr. Bucket Chocolaterie"
  },
  "offers": {
    "@type": "Offer",
    "price": "0",
    "priceCurrency": "SGD",
    "availability": "https://schema.org/InStock",
    "url": "https://minionxmatcha.github.io/2026/11/12/the-christmas-atelier-2026-singapore-booth-directory.html"
  }
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
      <h1 class="cs-title">The Christmas Atelier 2026: Complete Booth Directory</h1>
      <p class="cs-where">Sands Expo Hall C · 12 – 14 Nov 2026 · 130+ booths</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-matcha" href="#matcha" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">🍵</span>
        <strong>Matcha & tea first</strong>
        <span class="cs-from">7 tea stops with booth numbers</span>
      </a>
      <a class="cs-counter cs-counter-banana" href="#all-booths" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🎄</span>
        <strong>Every booth</strong>
        <span class="cs-from">F&B, fashion, beauty, lifestyle & more</span>
      </a>
    </div>
  </header>

  <p><strong>The Christmas Atelier 2026</strong> returns to <strong>Marina Bay Sands Expo & Convention Centre, Level 1, Hall C</strong> from <strong>12 to 14 November 2026</strong>. With over 130 curated booths across gourmet food and drink, specialty matcha and tea, artisanal bakes, fashion, beauty and lifestyle, here is the complete categorised booth directory to help you navigate the event floor.</p>

  <!-- Category directory -->
  <nav aria-label="Jump to a category" id="all-booths">
    <ul class="cs-dir">
      <li><a href="#matcha">🍵 Matcha & tea<span class="cs-count">(7)</span></a></li>
      <li><a href="#showcase">🎄 Floral Atelier<span class="cs-count">(8)</span></a></li>
      <li><a href="#fnb">🍽️ Food & drinks<span class="cs-count">(30)</span></a></li>
      <li><a href="#fashion">👗 Fashion<span class="cs-count">(35)</span></a></li>
      <li><a href="#accessories">💍 Accessories<span class="cs-count">(16)</span></a></li>
      <li><a href="#beauty">💄 Beauty<span class="cs-count">(14)</span></a></li>
      <li><a href="#lifestyle">🕯️ Lifestyle<span class="cs-count">(13)</span></a></li>
      <li><a href="#kids">🧸 Kids<span class="cs-count">(11)</span></a></li>
      <li><a href="#more">🧘 Wellness, activities & pets<span class="cs-count">(9)</span></a></li>
    </ul>
  </nav>

  <!-- Matcha & tea -->
  <section class="cs-board cs-board-matcha" id="matcha">
    <h2>🍵 Matcha, specialty tea & non-alcoholic drinks</h2>
    <p class="cs-lede">Start here if you're on a matcha hunt.</p>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Antea Social</span><span class="cs-bnum">Booth 126</span></li>
      <li><span class="cs-bname">Creamie Sippies <a href="/2026/09/25/creamie-sippies-bugis-street.html">our review</a></span><span class="cs-bnum">Booth 80</span></li>
      <li><span class="cs-bname">HIC</span><span class="cs-bnum">Booth 115</span></li>
      <li><span class="cs-bname">Kashinoki Matcha</span><span class="cs-bnum">Booth 116</span></li>
      <li><span class="cs-bname">Soi Coco</span><span class="cs-bnum">Booth 64</span></li>
      <li><span class="cs-bname">Tily Tea &amp; The Gifting Studio</span><span class="cs-bnum">Booth 72</span></li>
      <li><span class="cs-bname">Mariage Frères Tea</span><span class="cs-bnum cs-bnum-show">The Floral Atelier Showcase</span></li>
    </ul>
    <p class="cs-note">🍵 Also worth a stop: <strong>Hello Arigato (Booth 95)</strong> is listed under bakes, but it serves single-origin matcha drinks too. See <a href="/2026/11/05/singapore-coffee-week-2026-matcha-booths-guide.html#hello-arigato">their Coffee Week menu</a>.</p>
  </section>

  <!-- Floral Atelier showcase -->
  <section class="cs-board cs-board-xmas" id="showcase">
    <h2>🎄 The Floral Atelier (curated showcase)</h2>
    <p class="cs-lede">A curated showcase area with no individual booth numbers.</p>
    <ul class="cs-chips">
      <li>Bordallo Pinheiro</li>
      <li>Dolce &amp; Gabbana</li>
      <li>Evermore Candles</li>
      <li>Mariage Frères Tea</li>
      <li>Mon Dada Candles</li>
      <li>Prada</li>
      <li>The Floral Atelier Collection</li>
      <li>To&#x27;ak Luxury Chocolate</li>
    </ul>
  </section>

  <!-- F&B -->
  <section class="cs-board cs-board-banana" id="fnb">
    <h2>🍽️ Food & drinks</h2>
    <h3 class="cs-sub">🥐 Artisanal bakes, pastries & patisserie</h3>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Bob The Baker Boy</span><span class="cs-bnum">Booth 69</span></li>
      <li><span class="cs-bname">Butter Bread</span><span class="cs-bnum">Booth 118</span></li>
      <li><span class="cs-bname">Cranki Patisserie</span><span class="cs-bnum">Booth 125</span></li>
      <li><span class="cs-bname">Guilt Free Food</span><span class="cs-bnum">Booth 119</span></li>
      <li><span class="cs-bname">Hello Arigato</span><span class="cs-bnum">Booth 95</span></li>
      <li><span class="cs-bname">Kobashi</span><span class="cs-bnum">Booth 65</span></li>
      <li><span class="cs-bname">Miss Van Dough</span><span class="cs-bnum">Booth 124</span></li>
      <li><span class="cs-bname">Ollella</span><span class="cs-bnum">Booth 127</span></li>
      <li><span class="cs-bname">Patisserie Woo</span><span class="cs-bnum">Booth 82</span></li>
      <li><span class="cs-bname">Róa Midnight</span><span class="cs-bnum">Booth 67</span></li>
      <li><span class="cs-bname">Sweedy Cafesserie</span><span class="cs-bnum">Booth 81</span></li>
    </ul>
    <h3 class="cs-sub">🍫 Chocolates, gelato & sweet confections</h3>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Berrybar</span><span class="cs-bnum">Booth 96</span></li>
      <li><span class="cs-bname">Fossa Chocolate</span><span class="cs-bnum">Booth 62</span></li>
      <li><span class="cs-bname">Mr. Bucket Chocolaterie</span><span class="cs-bnum">Booth 68</span></li>
      <li><span class="cs-bname">SecondFloorLab Gelato</span><span class="cs-bnum">Booth 120</span></li>
      <li><span class="cs-bname">Wu Tang Club</span><span class="cs-bnum">Booth 123</span></li>
      <li><span class="cs-bname">To&#x27;ak Luxury Chocolate</span><span class="cs-bnum cs-bnum-show">The Floral Atelier Showcase</span></li>
    </ul>
    <h3 class="cs-sub">🧀 Savoury, cheese, condiments & gourmet pantry</h3>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Borderlessbutter</span><span class="cs-bnum">Booth 70</span></li>
      <li><span class="cs-bname">Cheeselads</span><span class="cs-bnum">Booth 99</span></li>
      <li><span class="cs-bname">Edit*</span><span class="cs-bnum">Booth 15</span></li>
      <li><span class="cs-bname">Mireia</span><span class="cs-bnum">Booth 128</span></li>
      <li><span class="cs-bname">Omollomo</span><span class="cs-bnum">Booth 117</span></li>
      <li><span class="cs-bname">The Portside Market</span><span class="cs-bnum">Booth 23</span></li>
      <li><span class="cs-bname">The Rare Honey Company</span><span class="cs-bnum">Booth 97</span></li>
    </ul>
    <h3 class="cs-sub">🍸 Craft spirits, whisky, gin & natural wines</h3>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Brass Lion Distillery</span><span class="cs-bnum">Booth 98</span></li>
      <li><span class="cs-bname">Clumzy</span><span class="cs-bnum">Booth 66</span></li>
      <li><span class="cs-bname">Distillius Craft Distillery</span><span class="cs-bnum">Booth 121</span></li>
      <li><span class="cs-bname">East Asia Whisky</span><span class="cs-bnum">Booth 130</span></li>
      <li><span class="cs-bname">Ghosts of the Ocean</span><span class="cs-bnum">Booth 129</span></li>
      <li><span class="cs-bname">Whet Your Whistle</span><span class="cs-bnum">Booth 122</span></li>
    </ul>
  </section>

  <section class="cs-board cs-board-banana" id="fashion">
    <h2>👗 Fashion</h2>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Aijek</span><span class="cs-bnum">Booth 54</span></li>
      <li><span class="cs-bname">Akinn</span><span class="cs-bnum">Booth 63</span></li>
      <li><span class="cs-bname">Ans.Ein</span><span class="cs-bnum">Booth 43</span></li>
      <li><span class="cs-bname">As Intended</span><span class="cs-bnum">Booth 111</span></li>
      <li><span class="cs-bname">Atlas Kind</span><span class="cs-bnum">Booth 53</span></li>
      <li><span class="cs-bname">Bridge &amp; Bella</span><span class="cs-bnum">Booth 27</span></li>
      <li><span class="cs-bname">Bound Designs</span><span class="cs-bnum">Booth 28</span></li>
      <li><span class="cs-bname">Bubsmamy</span><span class="cs-bnum">Booth 35</span></li>
      <li><span class="cs-bname">Chello</span><span class="cs-bnum">Booth 90</span></li>
      <li><span class="cs-bname">Eltwine</span><span class="cs-bnum">Booth 113</span></li>
      <li><span class="cs-bname">Etna</span><span class="cs-bnum">Booth 110</span></li>
      <li><span class="cs-bname">House of Abr</span><span class="cs-bnum">Booth 44</span></li>
      <li><span class="cs-bname">Like Saturdays</span><span class="cs-bnum">Booth 76</span></li>
      <li><span class="cs-bname">Ohhgranny</span><span class="cs-bnum">Booth 13</span></li>
      <li><span class="cs-bname">Olive Basics</span><span class="cs-bnum">Booth 45</span></li>
      <li><span class="cs-bname">Paper Palette Studio</span><span class="cs-bnum">Booth 93</span></li>
      <li><span class="cs-bname">Paopao</span><span class="cs-bnum">Booth 57</span></li>
      <li><span class="cs-bname">Rawbought</span><span class="cs-bnum">Booth 40</span></li>
      <li><span class="cs-bname">Ryan Lee Kuala Lumpur</span><span class="cs-bnum">Booth 56</span></li>
      <li><span class="cs-bname">Sabrinagoh</span><span class="cs-bnum">Booth 94</span></li>
      <li><span class="cs-bname">Second Sons</span><span class="cs-bnum">Booth 109</span></li>
      <li><span class="cs-bname">Selenightco</span><span class="cs-bnum">Booth 75</span></li>
      <li><span class="cs-bname">Sensibilities</span><span class="cs-bnum">Booth 91</span></li>
      <li><span class="cs-bname">Stolen</span><span class="cs-bnum">Booth 55</span></li>
      <li><span class="cs-bname">Studio Gypsied</span><span class="cs-bnum">Booth 112</span></li>
      <li><span class="cs-bname">Studio Qiling</span><span class="cs-bnum">Booth 47</span></li>
      <li><span class="cs-bname">Talking Toes</span><span class="cs-bnum">Booth 20</span></li>
      <li><span class="cs-bname">The Cotton Tale</span><span class="cs-bnum">Booth 87</span></li>
      <li><span class="cs-bname">The Form</span><span class="cs-bnum">Booth 42</span></li>
      <li><span class="cs-bname">The Good Apparel</span><span class="cs-bnum">Booth 3</span></li>
      <li><span class="cs-bname">The Ordinary Co</span><span class="cs-bnum">Booth 31</span></li>
      <li><span class="cs-bname">The Shirt Bar</span><span class="cs-bnum">Booth 2</span></li>
      <li><span class="cs-bname">Tow Tow</span><span class="cs-bnum">Booth 19</span></li>
      <li><span class="cs-bname">Tria The Label</span><span class="cs-bnum">Booth 39</span></li>
      <li><span class="cs-bname">Wūhaūs</span><span class="cs-bnum">Booth 51</span></li>
    </ul>
  </section>

  <section class="cs-board cs-board-matcha" id="accessories">
    <h2>💍 Accessories</h2>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">5ive Letters</span><span class="cs-bnum">Booth 6</span></li>
      <li><span class="cs-bname">Carrie K.</span><span class="cs-bnum">Booth 50</span></li>
      <li><span class="cs-bname">Cheru Crystals</span><span class="cs-bnum">Booth 61</span></li>
      <li><span class="cs-bname">Dear Diary Co.</span><span class="cs-bnum">Booth 60</span></li>
      <li><span class="cs-bname">Embrace Jewellery</span><span class="cs-bnum">Booth 49</span></li>
      <li><span class="cs-bname">Envet</span><span class="cs-bnum">Booth 37</span></li>
      <li><span class="cs-bname">Euniqyou</span><span class="cs-bnum">Booth 5</span></li>
      <li><span class="cs-bname">Forbidden Hill</span><span class="cs-bnum">Booth 4</span></li>
      <li><span class="cs-bname">Ivonovi Jewellery</span><span class="cs-bnum">Booth 7</span></li>
      <li><span class="cs-bname">Locket Allegro</span><span class="cs-bnum">Booth 25</span></li>
      <li><span class="cs-bname">Myrrh</span><span class="cs-bnum">Booth 38</span></li>
      <li><span class="cs-bname">Nakedglory</span><span class="cs-bnum">Booth 108</span></li>
      <li><span class="cs-bname">Ourheartbeads</span><span class="cs-bnum">Booth 12</span></li>
      <li><span class="cs-bname">Sunnysde</span><span class="cs-bnum">Booth 52</span></li>
      <li><span class="cs-bname">Wherebilly</span><span class="cs-bnum">Booth 114</span></li>
      <li><span class="cs-bname">Yard Yarn</span><span class="cs-bnum">Booth 88</span></li>
    </ul>
  </section>

  <section class="cs-board cs-board-banana" id="beauty">
    <h2>💄 Beauty</h2>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Alaaya Skin</span><span class="cs-bnum">Booth 14</span></li>
      <li><span class="cs-bname">Aporenaturals</span><span class="cs-bnum">Booth 1</span></li>
      <li><span class="cs-bname">Bycaxs</span><span class="cs-bnum">Booth 85</span></li>
      <li><span class="cs-bname">Clean Folks Club</span><span class="cs-bnum">Booth 71</span></li>
      <li><span class="cs-bname">Elleco Beauty</span><span class="cs-bnum">Booth 89</span></li>
      <li><span class="cs-bname">Gentle Therapy</span><span class="cs-bnum">Booth 78</span></li>
      <li><span class="cs-bname">Handmade Heroes</span><span class="cs-bnum">Booth 74</span></li>
      <li><span class="cs-bname">Ingu Skin</span><span class="cs-bnum">Booth 48</span></li>
      <li><span class="cs-bname">Nodspark</span><span class="cs-bnum">Booth 24</span></li>
      <li><span class="cs-bname">Postcard</span><span class="cs-bnum">Booth 22</span></li>
      <li><span class="cs-bname">Romi Beauty</span><span class="cs-bnum">Booth 41</span></li>
      <li><span class="cs-bname">Sukoon</span><span class="cs-bnum">Booth 59</span></li>
      <li><span class="cs-bname">The Daily Press</span><span class="cs-bnum">Booth 11</span></li>
      <li><span class="cs-bname">The Powder Shampoo</span><span class="cs-bnum">Booth 10</span></li>
    </ul>
  </section>

  <section class="cs-board cs-board-matcha" id="lifestyle">
    <h2>🕯️ Lifestyle</h2>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Bask In The Glow</span><span class="cs-bnum">Booth 29</span></li>
      <li><span class="cs-bname">Bynd Artisan</span><span class="cs-bnum">Booth 46</span></li>
      <li><span class="cs-bname">Cherry Pie Farmhouse</span><span class="cs-bnum">Booth 83</span></li>
      <li><span class="cs-bname">Chezhemdi</span><span class="cs-bnum">Booth 18</span></li>
      <li><span class="cs-bname">Fushi Maison</span><span class="cs-bnum">Booth 79</span></li>
      <li><span class="cs-bname">Inwarmregard</span><span class="cs-bnum">Booth 21</span></li>
      <li><span class="cs-bname">Kinu Supply</span><span class="cs-bnum">Booth 8</span></li>
      <li><span class="cs-bname">Love Curates Studio</span><span class="cs-bnum">Booth 36</span></li>
      <li><span class="cs-bname">Papercranes Design</span><span class="cs-bnum">Booth 30</span></li>
      <li><span class="cs-bname">Scent Journer</span><span class="cs-bnum">Booth 77</span></li>
      <li><span class="cs-bname">The Squishy Town</span><span class="cs-bnum">Booth 105</span></li>
      <li><span class="cs-bname">Urban Li&#x27;l</span><span class="cs-bnum">Booth 34</span></li>
      <li><span class="cs-bname">Wearesuper</span><span class="cs-bnum">Booth 58</span></li>
    </ul>
  </section>

  <section class="cs-board cs-board-banana" id="kids">
    <h2>🧸 Kids</h2>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Cosoco Kids</span><span class="cs-bnum">Booth 101</span></li>
      <li><span class="cs-bname">Evryday Studios</span><span class="cs-bnum">Booth 17</span></li>
      <li><span class="cs-bname">Fennec Folk</span><span class="cs-bnum">Booth 107</span></li>
      <li><span class="cs-bname">House of Holly</span><span class="cs-bnum">Booth 26</span></li>
      <li><span class="cs-bname">Mellow</span><span class="cs-bnum">Booth 103</span></li>
      <li><span class="cs-bname">Momoka</span><span class="cs-bnum">Booth 102</span></li>
      <li><span class="cs-bname">Petit Beary</span><span class="cs-bnum">Booth 104</span></li>
      <li><span class="cs-bname">Poppy James</span><span class="cs-bnum">Booth 33</span></li>
      <li><span class="cs-bname">Soft Spot</span><span class="cs-bnum">Booth 100</span></li>
      <li><span class="cs-bname">These Tiny Things</span><span class="cs-bnum">Booth 32</span></li>
      <li><span class="cs-bname">Tiny Dots Wonder</span><span class="cs-bnum">Booth 106</span></li>
    </ul>
  </section>

  <section class="cs-board cs-board-matcha" id="more">
    <h2>🧘 Wellness, activities & pets</h2>
    <h3 class="cs-sub">🧘‍♀️ Health & fitness</h3>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Cheak</span><span class="cs-bnum">Booth 92</span></li>
      <li><span class="cs-bname">Company of Wellness</span><span class="cs-bnum">Booth 86</span></li>
      <li><span class="cs-bname">Moom Health</span><span class="cs-bnum">Booth 73</span></li>
      <li><span class="cs-bname">Nestbloom</span><span class="cs-bnum">Booth 84</span></li>
    </ul>
    <h3 class="cs-sub">🎨 Activities</h3>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">David&#x27;s Henna Art</span><span class="cs-bnum">Booth 131</span></li>
      <li><span class="cs-bname">OIC Singapore</span><span class="cs-bnum">Booth 133</span></li>
      <li><span class="cs-bname">Poison Studio</span><span class="cs-bnum">Booth 132</span></li>
    </ul>
    <h3 class="cs-sub">🐾 Pets</h3>
    <ul class="cs-booth-list">
      <li><span class="cs-bname">Gentle Pet Store</span><span class="cs-bnum">Booth 16</span></li>
      <li><span class="cs-bname">Vetreska</span><span class="cs-bnum">Booth 9</span></li>
    </ul>
  </section>

  <!-- Event details -->
  <section class="cs-info">
    <h2>Event details</h2>
    <dl>
      <dt>Event</dt>
      <dd>The Christmas Atelier 2026</dd>
      <dt>Dates</dt>
      <dd>12 – 14 November 2026</dd>
      <dt>Venue</dt>
      <dd>Marina Bay Sands Expo & Convention Centre<br>Level 1, Hall C, 10 Bayfront Avenue</dd>
      <dt>Organiser</dt>
      <dd>The Floral Atelier</dd>
    </dl>
    <a class="cs-map" href="https://www.google.com/maps/search/?api=1&query=Sands+Expo+and+Convention+Centre+10+Bayfront+Avenue+Singapore+018956" target="_blank" rel="noopener">Open in Google Maps</a>
  </section>

</div>
