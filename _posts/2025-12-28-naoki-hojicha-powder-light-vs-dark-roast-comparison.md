---
layout: post
title: "Naoki Hojicha Powder Review: Light Roast vs. Dark Roast Hojicha Latte Comparison"
date: 2025-12-28
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

  /* Tea tasting additions */
  .cs-tier-cn { font-family: var(--body); font-weight: 400; font-size: 13px; color: #6b6550; margin-left: 4px; }
  .cs-ware { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .cs-ware .cs-special { margin: 0; }
  .cs-ware .cs-special + .cs-special { margin-top: 0; }
  .cs-pinyin { display: block; font-style: italic; font-size: 13px; color: #6b6550; margin: -2px 0 6px; }
  .cs-jars { list-style: none; margin: 0; padding: 0; display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .cs .cs-jars li { margin: 0; display: grid; grid-template-columns: 40px 1fr; gap: 12px; align-items: center; padding: 12px 14px; background: #fff; border: 1.5px solid var(--ink); border-radius: 16px; }
  .cs .cs-jars li.cs-star { background: var(--ink); color: #fff; }
  .cs-jar-num { width: 40px; height: 40px; border-radius: 50%; display: grid; place-items: center; font-family: var(--display); font-weight: 800; font-size: 19px; background: var(--banana); border: 2px solid var(--ink); color: var(--ink); }
  .cs-jar-name { display: block; font-weight: 700; font-size: 15px; line-height: 1.25; }
  .cs-jar-cn { display: block; font-size: 13px; color: #6b6550; margin: 1px 0 6px; }
  .cs-star .cs-jar-cn { color: #d8d2b8; }
  .cs-type { display: inline-block; font-size: 11px; font-weight: 700; padding: 2px 9px; border-radius: 999px; border: 1.5px solid var(--ink); color: var(--ink); }
  .cs-type-green { background: #DCEBC0; }
  .cs-type-red { background: #F6D3C4; }
  .cs-type-white { background: #F4F1E8; }
  .cs-type-oolong { background: #F2E2C4; }
  .cs-type-jasmine { background: #F9E3EE; }
  .cs-star-badge { display: inline-block; margin-left: 4px; font-size: 11px; font-weight: 700; padding: 2px 8px; border-radius: 999px; background: var(--banana); color: var(--ink); border: 1.5px solid var(--banana); }
  .cs-special .cs-special-head .cs-nick { font-family: var(--body); font-weight: 400; font-style: italic; font-size: 14px; color: #6b6550; }
  @media (max-width: 600px) { .cs-ware, .cs-jars { grid-template-columns: 1fr; } }

  /* Hojicha roast additions */
  .cs-counter-light { background: #E2B46A; color: var(--ink); }
  .cs-counter-dark { background: #4A2E1F; color: #fff; }
  .cs-vs .cs-vs-light { background: #F7EAD2; }
  .cs-vs .cs-vs-dark { background: #4A2E1F; color: #fff; }
  .cs-vs .cs-vs-dark strong { color: #F2C98A; }
  .cs-vs .cs-vs-light strong { color: #7A4B16; }
  .cs-swatch-dot { display: inline-block; width: 14px; height: 14px; border-radius: 50%; border: 1.5px solid currentColor; vertical-align: -2px; margin-right: 6px; }
  .cs-special-light { border-left: 8px solid #E2B46A; }
  .cs-special-dark { border-left: 8px solid #4A2E1F; }
  .cs-foam { list-style: none; margin: 0; padding: 0; display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; }
  .cs .cs-foam li { margin: 0; background: #fff; border: 1.5px solid var(--ink); border-radius: 16px; overflow: hidden; display: flex; flex-direction: column; }
  .cs-cup { height: 96px; display: flex; flex-direction: column; justify-content: flex-end; border-bottom: 1.5px solid var(--ink); }
  .cs-cup-foam { background: repeating-radial-gradient(circle at 30% 40%, #FFFDF4 0 3px, #F3EBD3 3px 6px); border-top: 1.5px dashed rgba(42,38,22,.35); }
  .cs-cup-tea { height: 44px; }
  .cs-foam-body { padding: 12px 14px 14px; }
  .cs-foam-body strong { display: block; font-family: var(--display); font-weight: 800; font-size: 17px; line-height: 1.2; margin-bottom: 4px; }
  .cs-foam-body p { margin: 0; font-size: 14px; }
  .cs-foam-level { display: inline-block; font-size: 12px; font-weight: 700; padding: 2px 9px; border-radius: 999px; border: 1.5px solid var(--ink); background: var(--foam); margin-bottom: 6px; }
  @media (max-width: 600px) { .cs-foam { grid-template-columns: 1fr; } .cs-cup { height: 70px; } .cs-cup-tea { height: 30px; } }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Product",
      "name": "Naoki Matcha Classic Roast Hojicha Powder (50g)",
      "description": "Light-to-classic roast Japanese Hojicha powder by Naoki Matcha (50g resealable pouch), delivering a gentle, nutty, and kinako-like flavour profile ideal for iced hojicha lattes.",
      "image": "https://img.youtube.com/vi/AwaXwGQw2t8/hqdefault.jpg",
      "brand": {
        "@type": "Brand",
        "name": "Naoki Matcha"
      },
      "review": {
        "@type": "Review",
        "author": {
          "@type": "Person",
          "name": "minionxmatcha"
        },
        "reviewBody": "Naoki's Classic Roast Hojicha Powder presents a warm golden-brown hue and retains more natural tea saponins than dark-roast alternatives, creating noticeably better microfoam when whisked. In an iced latte, it tastes gentle, nutty, and almost kinako-like—making it a top pick for milk tea lovers."
      }
    },
    {
      "@type": "VideoObject",
      "name": "Light Roast vs Dark Roast Hojicha: Naoki Hojicha Powder vs Sundays Kuma Hojicha",
      "description": "Side-by-side comparison of Naoki Matcha's Classic Roast Hojicha Powder (Light Roast) and Sundays Kuma Deep Roast Hojicha Powder (Dark Roast), testing powder colour, saponin microfoam retention, and iced latte flavour profiles.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/AwaXwGQw2t8/hqdefault.jpg"
      ],
      "uploadDate": "2025-12-28",
      "contentUrl": "https://www.youtube.com/shorts/AwaXwGQw2t8",
      "embedUrl": "https://www.youtube.com/embed/AwaXwGQw2t8"
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

  <!-- Hero: light vs dark -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">Naoki Hojicha Powder Review: Light Roast vs Dark Roast</h1>
      <p class="cs-where">Same tea-to-milk ratio · Powder colour, microfoam & iced latte taste</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-light" href="#team-light" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🌾</span>
        <strong>Team Light Roast</strong>
        <span class="cs-from">Naoki Classic Roast · 50g pouch</span>
      </a>
      <a class="cs-counter cs-counter-dark" href="#team-dark" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">🍫</span>
        <strong>Team Dark Roast</strong>
        <span class="cs-from">Sundays Kuma · 30g jar</span>
      </a>
    </div>
  </header>

  <p>Are you <strong>Team Light Roast</strong> or <strong>Team Dark Roast</strong> when it comes to hojicha lattes? I put <strong>Naoki Matcha's Classic Roast Hojicha Powder</strong> head to head against <strong>Sundays Kuma Deep Roast Hojicha</strong>, comparing dry powder colour, microfoam and iced latte flavour using exactly the same tea-to-milk ratio.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video comparison</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DSzhM70kylK/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DSzhM70kylK/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/AwaXwGQw2t8"
        title="Light Roast vs Dark Roast Hojicha: Naoki Hojicha Powder Review"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSp77FX2j/" target="_blank" rel="noopener">Watch on TikTok</a>
    </p>
  </section>

  <!-- Side by side -->
  <section class="cs-board cs-board-banana">
    <h2>🥊 Side-by-side comparison</h2>

    <div class="cs-round">
      <div class="cs-round-head"><span>Round 1</span><h3>Powder colour</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-light"><strong><span class="cs-swatch-dot" style="background:#C98E45;color:#7A4B16;"></span>Naoki Classic Roast</strong><p>Warm golden brown.</p></div>
        <div class="cs-vs-dark"><strong><span class="cs-swatch-dot" style="background:#6B4128;color:#F2C98A;"></span>Sundays Kuma</strong><p>Deeper cocoa brown. Close at a glance, but clearly darker side by side.</p></div>
      </div>
    </div>

    <div class="cs-round">
      <div class="cs-round-head"><span>Round 2</span><h3>Whisked microfoam</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-light"><strong>Naoki Classic Roast <span class="cs-win">More froth</span></strong><p>Thicker foam, thanks to more natural saponins.</p></div>
        <div class="cs-vs-dark"><strong>Sundays Kuma</strong><p>Less froth, as the deeper roast leaves fewer saponins.</p></div>
      </div>
    </div>

    <div class="cs-round">
      <div class="cs-round-head"><span>Round 3</span><h3>Iced latte flavour</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-light"><strong>Naoki Classic Roast</strong><p>Gentle, nutty, almost kinako-like.</p></div>
        <div class="cs-vs-dark"><strong>Sundays Kuma</strong><p>Bold dark chocolate notes with a coffee-like body.</p></div>
      </div>
    </div>

    <div class="cs-round">
      <div class="cs-round-head"><span>Verdict</span><h3>Best for</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-light"><strong>Naoki Classic Roast</strong><p>Milk tea lovers.</p></div>
        <div class="cs-vs-dark"><strong>Sundays Kuma</strong><p>Roasted oolong and coffee fans.</p></div>
      </div>
    </div>
  </section>

  <!-- Detailed notes -->
  <section class="cs-board cs-board-matcha">
    <h2>📝 Tasting notes</h2>

    <div class="cs-special cs-special-light" id="team-light">
      <div class="cs-special-head"><h4>Naoki Matcha Classic Roast Hojicha Powder</h4><span class="cs-tag">Team Light Roast</span></div>
      <div class="cs-tag-row"><span class="cs-tag">50g resealable pouch</span><span class="cs-tag">3g per cup</span></div>
      <p><strong>Visuals & whisking:</strong> right out of the pouch, it's a warm golden brown. Whisked with water, it builds noticeably thicker froth than deep-roast powders, because the lighter roast preserves more of the leaf's natural foaming agents.</p>
      <p style="margin-top:8px;"><strong>Taste:</strong> over ice and milk, the cup is gentle, nutty and almost kinako-like, reminiscent of toasted soybean flour. It never overwhelms the milk, making it the clear winner for milk tea lovers after a comforting, creamy daily latte.</p>
      <ul class="cs-chips" aria-label="Tasting notes"><li>Gentle</li><li>Nutty</li><li>Kinako-like</li></ul>
    </div>

    <div class="cs-special cs-special-dark" id="team-dark">
      <div class="cs-special-head"><h4>Sundays Kuma Hojicha</h4><span class="cs-tag">Team Dark Roast</span></div>
      <div class="cs-tag-row"><span class="cs-tag">30g jar</span><span class="cs-tag">Deep roast</span></div>
      <p><strong>Visuals & whisking:</strong> the dry powder looks surprisingly close to Naoki's at a glance, but side by side it's a deeper, darker brown.</p>
      <p style="margin-top:8px;"><strong>Taste:</strong> with the exact same milk and tea ratio, the dark roast gives a bold, intense cup. Ideal for roasted oolong fans and espresso drinkers looking for a low-caffeine kick.</p>
      <ul class="cs-chips" aria-label="Tasting notes"><li>Bold</li><li>Dark chocolate</li><li>Coffee-like body</li></ul>
    </div>
  </section>

  <!-- Tea science -->
  <section class="cs-board cs-board-banana">
    <h2>🔬 Tea science: why hojicha foams less than matcha</h2>
    <p class="cs-lede">Whisked hojicha never builds the same dense microfoam as ceremonial matcha. It comes down to <strong>saponins</strong>, the natural foaming compounds in green tea leaves. The more the leaves are roasted, the more saponins break down.</p>
    <ol class="cs-foam">
      <li>
        <div class="cs-cup"><div class="cs-cup-foam" style="height:52px;"></div><div class="cs-cup-tea" style="background:#7FA03A;"></div></div>
        <div class="cs-foam-body"><span class="cs-foam-level">Rich foam</span><strong>Unroasted matcha</strong><p>Keeps its natural saponins, so it whips into a rich, stable microfoam.</p></div>
      </li>
      <li>
        <div class="cs-cup"><div class="cs-cup-foam" style="height:26px;"></div><div class="cs-cup-tea" style="background:#C98E45;"></div></div>
        <div class="cs-foam-body"><span class="cs-foam-level">Moderate foam</span><strong>Light roast hojicha</strong><p>Naoki Classic Roast. Roasting starts breaking down saponins, giving a lighter froth.</p></div>
      </li>
      <li>
        <div class="cs-cup"><div class="cs-cup-foam" style="height:8px;"></div><div class="cs-cup-tea" style="background:#6B4128;"></div></div>
        <div class="cs-foam-body"><span class="cs-foam-level">Minimal foam</span><strong>Dark roast hojicha</strong><p>Sundays Kuma. Extended deep roasting breaks down most saponins, so even vigorous whisking makes little foam.</p></div>
      </li>
    </ol>
  </section>

</div>
