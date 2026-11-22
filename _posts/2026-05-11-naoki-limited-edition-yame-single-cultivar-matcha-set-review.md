---
layout: post
title: "Naoki Limited Edition Yame Single-Cultivar Matcha Set Review: 4-Cultivar Blind Latte Test"
date: 2026-05-11
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

  /* Yame cultivar set additions */
  .cs-glasses { list-style: none; margin: 0; padding: 0; display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; }
  .cs .cs-glasses li { margin: 0; background: #fff; border: 1.5px solid var(--ink); border-radius: 16px; overflow: hidden; display: flex; flex-direction: column; text-align: center; }
  .cs-glass-label { padding: 6px 4px; font-size: 12px; font-weight: 800; letter-spacing: .5px; border-bottom: 1.5px solid var(--ink); }
  .cs-glass-icon { font-size: 30px; line-height: 1; padding: 12px 0 4px; }
  .cs-glass-name { font-family: var(--display); font-weight: 800; font-size: 17px; line-height: 1.15; padding: 0 8px; }
  .cs-glass-jp { font-size: 12px; color: #6b6550; padding: 2px 8px 0; }
  .cs-glass-match { margin: 8px auto 12px; display: inline-block; font-size: 11px; font-weight: 700; padding: 2px 9px; border-radius: 999px; border: 1.5px solid var(--ink); background: var(--foam); color: var(--matcha-deep); }
  .l-bold { background: #3F8A3A; color: #fff; }
  .l-smooth { background: #2F6FB5; color: #fff; }
  .l-mellow { background: #F2C230; color: var(--ink); }
  .l-roast { background: #7A4A2A; color: #fff; }
  .cs-round-head .cs-label-pill { display: inline-block; font-size: 11px; font-weight: 800; padding: 2px 9px; border-radius: 999px; border: 1.5px solid var(--ink); margin-right: 8px; vertical-align: 3px; }
  .cs-round-head span.cs-label-pill { display: inline-block; }
  .cs-round-head span.l-bold, .cs-round-head span.l-smooth, .cs-round-head span.l-roast { color: #fff; }
  .cs-round-head span.l-mellow { color: var(--ink); }
  .cs-round-head h3 small { font-family: var(--body); font-weight: 400; font-size: 13px; color: #6b6550; margin-left: 4px; }
  .cs-round-body { padding: 12px 16px 14px; border-top: 1.5px solid var(--ink); font-size: 15px; }
  .cs-round-body p { margin: 0; }
  .cs-vs .cs-vs-naoki { background: #fff; }
  .cs-vs .cs-vs-naoki strong { color: #6b6550; }
  @media (max-width: 600px) { .cs-glasses { grid-template-columns: repeat(2, 1fr); } }

  /* Related Naoki reviews */
  .cs-related { list-style: none; margin: 0; padding: 0; display: grid; gap: 10px; }
  .cs .cs-related li { margin: 0; }
  .cs .cs-related a { display: grid; grid-template-columns: 64px 1fr; gap: 14px; align-items: center; padding: 12px 14px; background: #fff; border: 1.5px solid var(--ink); border-radius: 16px; color: var(--ink); text-decoration: none; }
  .cs .cs-related a:hover { background: var(--pudding); }
  .cs .cs-related a:focus-visible { outline: 3px solid var(--denim); outline-offset: 3px; }
  .cs-rel-date { display: grid; place-items: center; text-align: center; width: 64px; height: 58px; border: 1.5px solid var(--ink); border-radius: 12px; background: var(--banana); line-height: 1; }
  .cs-rel-date strong { display: block; font-family: var(--display); font-weight: 800; font-size: 20px; }
  .cs-rel-date span { display: block; font-size: 11px; font-weight: 700; margin-top: 2px; }
  .cs .cs-related li.cs-rel-new .cs-rel-date { background: #1C2B4F; color: #E5C77A; }
  .cs .cs-related li.cs-rel-new .cs-rel-date span { color: #fff; }
  .cs-rel-title { display: block; font-weight: 700; font-size: 16px; line-height: 1.3; }
  .cs-rel-blurb { display: block; font-size: 14px; color: #5c5640; margin-top: 2px; }
  .cs-rel-new-tag { display: inline-block; font-size: 11px; font-weight: 700; padding: 1px 8px; border-radius: 999px; background: #1C2B4F; color: #E5C77A; margin-left: 6px; vertical-align: 2px; }
  .cs-crosslink-navy { background: #1C2B4F; color: #fff; border: 2px solid var(--ink); }
  .cs .cs-crosslink-navy a { color: #E5C77A; }
  .cs-crosslink-navy strong { color: #E5C77A; }
  @media (max-width: 520px) { .cs .cs-related a { grid-template-columns: 52px 1fr; gap: 12px; } .cs-rel-date { width: 52px; height: 52px; } .cs-rel-date strong { font-size: 17px; } }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Product",
      "name": "Naoki Matcha Limited Edition Yame Single-Cultivar Matcha Set (Kirari 31, Okumidori, Seimei, Yabukita)",
      "description": "Limited edition four-pouch single-cultivar Japanese matcha gift set from Yame, Fukuoka by Naoki Matcha (4 x 30g pouches): Yame Bold (Kirari 31), Yame Smooth (Okumidori), Yame Mellow (Seimei), and Yame Deep Roast (Yabukita).",
      "image": "https://img.youtube.com/vi/MDe7jL9s0kA/hqdefault.jpg",
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
        "reviewBody": "Tested all four single-cultivar Yame matchas in a blind iced latte flight and successfully matched all four cultivars using Naoki's tasting notes. Kirari 31 (Bold) stands out with next-level brothy umami; Okumidori (Smooth) is the creamiest and most balanced; Seimei (Mellow) is the lightest with a gentle sweet finish; and Yabukita (Deep Roast) leans distinctly earthy and toasty."
      }
    },
    {
      "@type": "VideoObject",
      "name": "Naoki Limited Edition Yame Single-Cultivar Matcha Set Blind Test",
      "description": "Blind tasting four single-cultivar Yame matchas from Naoki Matcha (Kirari 31, Okumidori, Seimei, and Yabukita) in iced lattes to see if each cultivar's distinct flavour profile shines through milk.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/MDe7jL9s0kA/hqdefault.jpg"
      ],
      "uploadDate": "2026-05-11",
      "contentUrl": "https://www.youtube.com/shorts/MDe7jL9s0kA",
      "embedUrl": "https://www.youtube.com/embed/MDe7jL9s0kA"
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
      <h1 class="cs-title">Naoki Limited Edition Yame Single-Cultivar Set: 4-Cultivar Blind Latte Test</h1>
      <p class="cs-where">Yame, Fukuoka · 4 × 30g pouches · Iced latte blind test</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-banana" href="#result" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🎯</span>
        <strong>4 / 4 matched</strong>
        <span class="cs-from">Every cultivar identified blind</span>
      </a>
      <a class="cs-counter cs-counter-matcha" href="#cultivars" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">🌱</span>
        <strong>4 single cultivars</strong>
        <span class="cs-from">Kirari 31, Okumidori, Seimei, Yabukita</span>
      </a>
    </div>
  </header>

  <p>Can you actually taste the difference between single-cultivar matchas once they're in an iced latte? Using <strong>Naoki Matcha's Limited Edition Yame Single-Cultivar Matcha Gift Set</strong> from <strong>Yame, Fukuoka</strong>, the Minions taped the four cultivar names (<strong>Kirari 31</strong>, <strong>Okumidori</strong>, <strong>Seimei</strong> and <strong>Yabukita</strong>) under four identical glasses and shuffled them for a blind tasting challenge.</p>
  <p>Here's how each cultivar performed in the blind test, and how to tell them apart on the palate.</p>

  <p class="cs-crosslink cs-crosslink-navy">✨ <strong>Newest Naoki review:</strong> the one-time <a href="/2026/11/20/naoki-tenth-harvest-matcha-masters-collection-review.html">Tenth Harvest Matcha (Masters Collection)</a>, celebrating 10 years of Naoki. Only 200 tins for Singapore.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the 4-cultivar blind test</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DYKDF1szWBH/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DYKDF1szWBH/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/MDe7jL9s0kA"
        title="Naoki Limited Edition Yame Single-Cultivar Matcha Set Review"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSp734C7q/" target="_blank" rel="noopener">Watch on TikTok</a>
    </p>
  </section>

  <!-- Result -->
  <section class="cs-board cs-board-banana" id="result">
    <h2>🎯 The blind test: all four matched</h2>
    <p class="cs-lede">Using Naoki's tasting notes, I matched every glass to its cultivar. Each pouch's label colour is shown on top.</p>
    <ul class="cs-glasses">
      <li><span class="cs-glass-label l-bold">BOLD</span><span class="cs-glass-icon" aria-hidden="true">🥛</span><span class="cs-glass-name">Kirari 31</span><span class="cs-glass-jp">きらり31</span><span><span class="cs-glass-match">✓ Matched</span></span></li>
      <li><span class="cs-glass-label l-smooth">SMOOTH</span><span class="cs-glass-icon" aria-hidden="true">🥛</span><span class="cs-glass-name">Okumidori</span><span class="cs-glass-jp">おくみどり</span><span><span class="cs-glass-match">✓ Matched</span></span></li>
      <li><span class="cs-glass-label l-mellow">MELLOW</span><span class="cs-glass-icon" aria-hidden="true">🥛</span><span class="cs-glass-name">Seimei</span><span class="cs-glass-jp">せいめい</span><span><span class="cs-glass-match">✓ Matched</span></span></li>
      <li><span class="cs-glass-label l-roast">ROAST</span><span class="cs-glass-icon" aria-hidden="true">🥛</span><span class="cs-glass-name">Yabukita</span><span class="cs-glass-jp">やぶきた</span><span><span class="cs-glass-match">✓ Matched</span></span></li>
    </ul>
  </section>

  <!-- Cultivars -->
  <section class="cs-board cs-board-matcha" id="cultivars">
    <h2>🌱 How to tell the 4 cultivars apart</h2>
    <div class="cs-round" id="kirari-31">
      <div class="cs-round-head"><span><span class="cs-label-pill l-bold">BOLD</span>Yame Bold · 30g pouch</span><h3>Kirari 31<small>きらり31</small></h3></div>
      <div class="cs-vs">
        <div class="cs-vs-naoki"><strong>Naoki's profile</strong><p>Bold with lingering umami-savoury notes.</p></div>
        <div class="cs-vs-sas"><strong>My blind latte impression</strong><p>Distinct brothy notes and next-level umami intensity.</p></div>
      </div>
      <div class="cs-round-body"><p>Right from the first sip, Kirari 31 announces itself with unmistakable brothy, savoury notes. Even diluted with milk and ice, its umami depth is on a completely different level from standard blends.</p></div>
    </div>
    <div class="cs-round" id="okumidori">
      <div class="cs-round-head"><span><span class="cs-label-pill l-smooth">SMOOTH</span>Yame Smooth · 30g pouch</span><h3>Okumidori<small>おくみどり</small></h3></div>
      <div class="cs-vs">
        <div class="cs-vs-naoki"><strong>Naoki's profile</strong><p>Silky smooth with no bitterness.</p></div>
        <div class="cs-vs-sas"><strong>My blind latte impression</strong><p>Easily the creamiest and most balanced cup.</p></div>
      </div>
      <div class="cs-round-body"><p>True to its name, Okumidori had the creamiest mouthfeel of the four glasses. With zero bitterness and a rounded body, it stood out as the most harmonious, well-balanced everyday latte cultivar.</p><p style="margin-top:8px;font-size:14px;color:#5c5640;">🌟 Okumidori also stars in Naoki's one-time <a href="/2026/11/20/naoki-tenth-harvest-matcha-masters-collection-review.html">Tenth Harvest Matcha</a>, blended with Saemidori from Uji.</p></div>
    </div>
    <div class="cs-round" id="seimei">
      <div class="cs-round-head"><span><span class="cs-label-pill l-mellow">MELLOW</span>Yame Mellow · 30g pouch</span><h3>Seimei<small>せいめい</small></h3></div>
      <div class="cs-vs">
        <div class="cs-vs-naoki"><strong>Naoki's profile</strong><p>Gentle umami with natural sweetness.</p></div>
        <div class="cs-vs-sas"><strong>My blind latte impression</strong><p>The lightest body in the flight, with a clean hint of sweetness.</p></div>
      </div>
      <div class="cs-round-body"><p>A modern Japanese cultivar prized for its approachable delicacy. In the blind flight, Seimei was immediately identifiable as the lightest-bodied cup, finishing with a gentle, natural sweetness.</p></div>
    </div>
    <div class="cs-round" id="yabukita">
      <div class="cs-round-head"><span><span class="cs-label-pill l-roast">ROAST</span>Yame Deep Roast · 30g pouch</span><h3>Yabukita<small>やぶきた</small></h3></div>
      <div class="cs-vs">
        <div class="cs-vs-naoki"><strong>Naoki's profile</strong><p>Roasty with balanced savoury-sweetness.</p></div>
        <div class="cs-vs-sas"><strong>My blind latte impression</strong><p>Leans noticeably towards earthy, toasty notes.</p></div>
      </div>
      <div class="cs-round-body"><p>Yabukita is Japan's most widely grown tea cultivar, but Yame shading and a higher firing give this pouch a distinct earthy, toasty character that sets it apart from the brighter, sweeter cultivars in the box.</p></div>
    </div>
  </section>

  <!-- Verdict -->
  <section class="cs-info">
    <h2>Verdict: who is this set for?</h2>
    <p>If you usually drink multi-cultivar blends and want to train your palate to recognise individual cultivars, or you want to explore why <strong>Yame, Fukuoka</strong> is celebrated for its rich, shaded teas, this set is one of the most educational and enjoyable ways to taste them side by side. For an everyday Yame blend, try <a href="/2026/04/26/naoki-matcha-japan-hatsu-roku-house-roast-hojicha-review.html">Naoki's Roku from the Japan Series</a>, which earned a Minion Approved stamp.</p>
    <dl>
      <dt>Set</dt>
      <dd>Naoki Matcha Limited Edition Yame Single-Cultivar Matcha Gift Set</dd>
      <dt>Origin</dt>
      <dd>Yame, Fukuoka, Japan</dd>
      <dt>Contents</dt>
      <dd>4 × 30g resealable pouches: Bold, Smooth, Mellow and Deep Roast</dd>
    </dl>
  </section>


  <!-- More Naoki reviews -->
  <section class="cs-board cs-board-matcha" id="more-naoki">
    <h2>🍵 More Naoki Matcha reviews</h2>
    <p class="cs-lede">My other Naoki Matcha reviews, newest first.</p>
    <ul class="cs-related">
      <li class="cs-rel-new"><a href="/2026/11/20/naoki-tenth-harvest-matcha-masters-collection-review.html"><span class="cs-rel-date"><span><strong>20</strong><span>Nov 26</span></span></span><span><span class="cs-rel-title">Naoki Tenth Harvest Matcha Review (Masters Collection)<span class="cs-rel-new-tag">Newest</span></span><span class="cs-rel-blurb">A one-time Okumidori × Saemidori release, with only 200 tins for Singapore.</span></span></a></li>
      <li><a href="/2026/08/31/naoki-uji-harmony-2-0-matcha-review.html"><span class="cs-rel-date"><span><strong>31</strong><span>Aug 26</span></span></span><span><span class="cs-rel-title">Naoki Uji Harmony 2.0 Review: 5-Cultivar Uji Matcha</span><span class="cs-rel-blurb">Five Uji cultivars in an iced dairy latte, with a bitter dark-chocolate finish.</span></span></a></li>
      <li><a href="/2026/04/26/naoki-matcha-japan-hatsu-roku-house-roast-hojicha-review.html"><span class="cs-rel-date"><span><strong>26</strong><span>Apr 26</span></span></span><span><span class="cs-rel-title">Naoki Matcha Japan Series: Hatsu, Roku & House Roast Hojicha</span><span class="cs-rel-blurb">Uji vs Yame matcha, plus a smoky, chocolatey hojicha.</span></span></a></li>
      <li><a href="/2026/03/25/naoki-matcha-barista-pro-blend-home-pop-up-review.html"><span class="cs-rel-date"><span><strong>25</strong><span>Mar 26</span></span></span><span><span class="cs-rel-title">Naoki Matcha Barista Pro Blend Review</span><span class="cs-rel-blurb">The first-harvest Uji blend that holds up in milk and fruit purees at a home pop-up.</span></span></a></li>
      <li><a href="/2025/12/28/naoki-hojicha-powder-light-vs-dark-roast-comparison.html"><span class="cs-rel-date"><span><strong>28</strong><span>Dec 25</span></span></span><span><span class="cs-rel-title">Naoki Hojicha Powder Review: Light vs Dark Roast</span><span class="cs-rel-blurb">Naoki Classic Roast vs Sundays Kuma in an iced hojicha latte.</span></span></a></li>
      <li><a href="/2025/11/23/naoki-organic-matcha-blend-l-plus-review.html"><span class="cs-rel-date"><span><strong>23</strong><span>Nov 25</span></span></span><span><span class="cs-rel-title">Naoki Organic Matcha Blend L+ Review</span><span class="cs-rel-blurb">A ~50kg limited-edition Uji micro-lot, tested as an iced Bonsoy latte.</span></span></a></li>
    </ul>
  </section>

</div>
