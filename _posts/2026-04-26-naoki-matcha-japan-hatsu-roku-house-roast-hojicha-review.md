---
layout: post
title: "Naoki Matcha Japan Series Review: Hatsu (Uji), Roku (Yame) & House Roast Hojicha"
date: 2026-04-26
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

  /* Naoki JP series additions */
  .cs-counters-3 { grid-template-columns: repeat(3, 1fr); }
  .cs-counters-3 .cs-counter + .cs-counter { border-left: 2px solid var(--ink); }
  .cs-kanji { display: block; font-family: 'Noto Serif JP', 'Hiragino Mincho ProN', 'Yu Mincho', serif; font-weight: 700; font-size: 40px; line-height: 1; margin-bottom: 8px; }
  .cs-p-hatsu { background: #F7F3EE; color: var(--ink); box-shadow: inset 0 -8px 0 #7B2D4A; }
  .cs-p-roku { background: #1F2F55; color: #fff; box-shadow: inset 0 -8px 0 #2FA3A0; }
  .cs-p-hoji { background: #4A2E1F; color: #fff; box-shadow: inset 0 -8px 0 #B5532E; }
  .cs-pouch { border: 1.5px solid var(--ink); border-radius: 18px; overflow: hidden; background: #fff; }
  .cs-pouch + .cs-pouch { margin-top: 14px; }
  .cs-pouch-head { display: grid; grid-template-columns: 56px 1fr auto; gap: 14px; align-items: center; padding: 16px 18px 22px; }
  .cs-pouch-head .cs-kanji { margin: 0; font-size: 44px; text-align: center; }
  .cs-pouch-head h3 { font-family: var(--display); font-weight: 800; font-size: 21px; line-height: 1.15; margin: 0; color: inherit; }
  .cs-pouch-head small { display: block; font-family: var(--body); font-weight: 400; font-size: 13px; opacity: .85; margin-top: 2px; }
  .cs-pouch-body { padding: 16px 18px 18px; }
  .cs-pouch-body p { margin: 0 0 10px; font-size: 15px; }
  .cs-pouch-body dl { margin: 12px 0 0; display: grid; grid-template-columns: 90px 1fr; gap: 6px 12px; font-size: 14px; }
  .cs-pouch-body dt { font-weight: 700; color: #6b6550; }
  .cs-pouch-body dd { margin: 0; }
  .cs-pouch-body p.cs-pouch-link { margin: 12px 0 0; font-size: 14px; color: #5c5640; }
  .cs-approved { display: inline-block; font-size: 12px; font-weight: 800; padding: 5px 11px; border-radius: 999px; background: var(--banana); color: var(--ink); border: 2px solid var(--ink); white-space: nowrap; transform: rotate(-4deg); }
  .cs-table-jp thead th:nth-child(2) { background: #F7F3EE; color: var(--ink); box-shadow: inset 0 -4px 0 #7B2D4A; }
  .cs-table-jp thead th:nth-child(3) { background: #1F2F55; color: #fff; box-shadow: inset 0 -4px 0 #2FA3A0; }
  .cs-table-jp thead th:nth-child(4) { background: #4A2E1F; color: #fff; box-shadow: inset 0 -4px 0 #B5532E; }
  .cs-table-jp td { background: #fff !important; font-size: 14px; }
  .cs-table-jp tbody th { width: 22%; color: var(--ink); }
  @media (max-width: 600px) {
    .cs-counters-3 { grid-template-columns: 1fr; }
    .cs-counters-3 .cs-counter + .cs-counter { border-left: 0; border-top: 2px solid var(--ink); }
    .cs-pouch-head { grid-template-columns: 44px 1fr; }
    .cs-pouch-head .cs-kanji { font-size: 36px; }
    .cs-pouch-head .cs-approved { grid-column: 1 / -1; justify-self: start; }
    .cs-table-jp th, .cs-table-jp td { padding: 8px 6px; font-size: 12px !important; overflow-wrap: anywhere; }
    .cs-table-jp tbody th { width: 70px; overflow-wrap: normal; font-size: 11px !important; }
  }

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
      "name": "Naoki Matcha Japan Series (Hatsu Uji Matcha, Roku Yame Matcha & House Roast Hojicha)",
      "description": "40g Japanese tea pouches from Naoki Matcha's Japan (JP) series: Hatsu (Uji, Kyoto), Roku (Yame, Fukuoka), and House Roast Hojicha.",
      "image": "https://img.youtube.com/vi/vABgEbRHTng/hqdefault.jpg",
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
        "reviewBody": "Hatsu from Uji surprises with an unexpectedly roasty yet smooth, balanced profile suited for everyday lattes. Roku from Yame delivers signature nutty, creamy depth that earns a Minion-approved stamp. House Roast Hojicha brings a rich, smoky, and chocolatey body ideal for curing hojicha latte cravings."
      }
    },
    {
      "@type": "VideoObject",
      "name": "Naoki Matcha Japan: Hatsu, Roku & House Roast Hojicha Review",
      "description": "Unboxing and tasting Naoki Matcha Japan's three 40g blends: Hatsu (Uji), Roku (Yame), and House Roast Hojicha.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/vABgEbRHTng/hqdefault.jpg"
      ],
      "uploadDate": "2026-04-26",
      "contentUrl": "https://www.youtube.com/shorts/vABgEbRHTng",
      "embedUrl": "https://www.youtube.com/embed/vABgEbRHTng"
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

  <!-- Hero: the three pouches -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">Naoki Matcha Japan Series Review: Hatsu, Roku & House Roast Hojicha</h1>
      <p class="cs-where">JP Series · Three 40g pouches · Whisked & poured over Minion ice</p>
    </div>
    <div class="cs-counters cs-counters-3">
      <a class="cs-counter cs-p-hatsu" href="#hatsu" style="text-decoration:none;color:var(--ink);">
        <span class="cs-kanji" aria-hidden="true">初</span>
        <strong>Hatsu</strong>
        <span class="cs-from">Uji, Kyoto</span>
      </a>
      <a class="cs-counter cs-p-roku" href="#roku" style="text-decoration:none;color:#fff;">
        <span class="cs-kanji" aria-hidden="true">六</span>
        <strong>Roku</strong>
        <span class="cs-from">Yame, Fukuoka</span>
      </a>
      <a class="cs-counter cs-p-hoji" href="#house-roast" style="text-decoration:none;color:#fff;">
        <span class="cs-kanji" aria-hidden="true">焙</span>
        <strong>House Roast</strong>
        <span class="cs-from">Hojicha</span>
      </a>
    </div>
  </header>

  <p><strong>Naoki Matcha Japan</strong> sent over three 40g blends from their <strong>JP Series</strong>: <strong>Hatsu (初)</strong> from Uji, <strong>Roku (六)</strong> from Yame, and <strong>House Roast Hojicha (焙)</strong>.</p>
  <p>Whisked with my Minion-charmed bamboo chasen and poured over a 3D Minion ice cube, here's how all three pouches compare.</p>

  <p class="cs-crosslink cs-crosslink-navy">✨ <strong>Newest Naoki review:</strong> the one-time <a href="/2026/11/20/naoki-tenth-harvest-matcha-masters-collection-review.html">Tenth Harvest Matcha (Masters Collection)</a>, celebrating 10 years of Naoki. Only 200 tins for Singapore.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video review</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DXl6roME9de/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DXl6roME9de/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/vABgEbRHTng"
        title="Naoki Matcha Japan: Hatsu, Roku & House Roast Hojicha"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSp7cnRHA/" target="_blank" rel="noopener">Watch on TikTok</a>
    </p>
  </section>

  <!-- Tasting notes -->
  <section class="cs-board cs-board-banana">
    <h2>👅 Tasting notes</h2>

    <article class="cs-pouch" id="hatsu">
      <div class="cs-pouch-head cs-p-hatsu">
        <span class="cs-kanji" aria-hidden="true">初</span>
        <h3>Hatsu matcha<small>Uji, Kyoto · 40g</small></h3>
      </div>
      <div class="cs-pouch-body">
        <p>The biggest surprise of the trio. Uji matchas usually lean vegetal or marine, but Hatsu has a pleasant, unexpectedly roasty warmth while staying smooth and well balanced, which makes it an easy pick for an everyday iced latte.</p>
        <ul class="cs-chips" aria-label="Tasting notes"><li>Unexpectedly roasty</li><li>Smooth</li><li>Balanced</li></ul>
        <dl>
          <dt>Best for</dt><dd>Easy-drinking everyday matcha</dd>
          <dt>Pouch</dt><dd>White matte with a purple-maroon wave</dd>
        </dl>
      </div>
    </article>

    <article class="cs-pouch" id="roku">
      <div class="cs-pouch-head cs-p-roku">
        <span class="cs-kanji" aria-hidden="true">六</span>
        <h3>Roku matcha<small>Yame, Fukuoka · 40g</small></h3>
        <span class="cs-approved">🍌 Minion Approved</span>
      </div>
      <div class="cs-pouch-body">
        <p>If you have a soft spot for Yame matcha, Roku delivers right on cue. It whisks into a glossy emerald microfoam and brings that signature nutty, creamy richness, shining through milk with no harsh astringency.</p>
        <ul class="cs-chips" aria-label="Tasting notes"><li>Nutty</li><li>Creamy</li><li>Rich microfoam</li></ul>
        <dl>
          <dt>Best for</dt><dd>Yame matcha fans</dd>
          <dt>Pouch</dt><dd>Navy matte with a teal wave</dd>
        </dl>
        <p class="cs-pouch-link">🌿 More Yame: I blind-tested four single-cultivar Yame matchas in <a href="/2026/05/11/naoki-limited-edition-yame-single-cultivar-matcha-set-review.html">Naoki's Limited Edition Yame Set</a>.</p>
      </div>
    </article>

    <article class="cs-pouch" id="house-roast">
      <div class="cs-pouch-head cs-p-hoji">
        <span class="cs-kanji" aria-hidden="true">焙</span>
        <h3>House Roast hojicha<small>Japan · 40g</small></h3>
      </div>
      <div class="cs-pouch-body">
        <p>Boldly smoky and chocolatey from the first sip. When a late-afternoon or evening hojicha craving hits, this dark, aromatic roast cuts cleanly through cold milk for a comforting, cocoa-toned latte.</p>
        <ul class="cs-chips" aria-label="Tasting notes"><li>Smoky</li><li>Chocolatey</li><li>Full-bodied</li></ul>
        <dl>
          <dt>Best for</dt><dd>Deep hojicha latte cravings</dd>
          <dt>Pouch</dt><dd>Dark brown matte with a rust-red wave</dd>
        </dl>
        <p class="cs-pouch-link">🍂 Prefer a lighter roast? See <a href="/2025/12/28/naoki-hojicha-powder-light-vs-dark-roast-comparison.html">Naoki's Classic Roast Hojicha vs a dark roast</a>.</p>
      </div>
    </article>
  </section>

  <!-- Comparison -->
  <section class="cs-info">
    <h2>Side-by-side lineup</h2>
    <div class="cs-table-wrap">
      <table class="cs-table cs-table-jp">
        <thead>
          <tr><td></td><th scope="col">Hatsu 初</th><th scope="col">Roku 六</th><th scope="col">House Roast 焙</th></tr>
        </thead>
        <tbody>
          <tr><th scope="row">Type</th><td>Matcha</td><td>Matcha</td><td>Hojicha</td></tr>
          <tr><th scope="row">Origin</th><td>Uji, Kyoto</td><td>Yame, Fukuoka</td><td>Japan</td></tr>
          <tr><th scope="row">Net weight</th><td>40g (1.4 oz)</td><td>40g (1.4 oz)</td><td>40g (1.4 oz)</td></tr>
          <tr><th scope="row">Flavour</th><td>Unexpectedly roasty, smooth, balanced</td><td>Nutty, creamy, rich microfoam</td><td>Smoky, chocolatey, full-bodied</td></tr>
          <tr><th scope="row">Best for</th><td>Everyday matcha</td><td>Yame fans 🍌</td><td>Hojicha latte cravings</td></tr>
        </tbody>
      </table>
    </div>
  </section>


  <!-- More Naoki reviews -->
  <section class="cs-board cs-board-matcha" id="more-naoki">
    <h2>🍵 More Naoki Matcha reviews</h2>
    <p class="cs-lede">My other Naoki Matcha reviews, newest first.</p>
    <ul class="cs-related">
      <li class="cs-rel-new"><a href="/2026/11/20/naoki-tenth-harvest-matcha-masters-collection-review.html"><span class="cs-rel-date"><span><strong>20</strong><span>Nov 26</span></span></span><span><span class="cs-rel-title">Naoki Tenth Harvest Matcha Review (Masters Collection)<span class="cs-rel-new-tag">Newest</span></span><span class="cs-rel-blurb">A one-time Okumidori × Saemidori release, with only 200 tins for Singapore.</span></span></a></li>
      <li><a href="/2026/05/11/naoki-limited-edition-yame-single-cultivar-matcha-set-review.html"><span class="cs-rel-date"><span><strong>11</strong><span>May 26</span></span></span><span><span class="cs-rel-title">Naoki Limited Edition Yame Single-Cultivar Matcha Set Review</span><span class="cs-rel-blurb">Kirari 31, Okumidori, Seimei & Yabukita in a 4-cultivar blind latte test.</span></span></a></li>
      <li><a href="/2026/03/25/naoki-matcha-barista-pro-blend-home-pop-up-review.html"><span class="cs-rel-date"><span><strong>25</strong><span>Mar 26</span></span></span><span><span class="cs-rel-title">Naoki Matcha Barista Pro Blend Review</span><span class="cs-rel-blurb">The first-harvest Uji blend that holds up in milk and fruit purees at a home pop-up.</span></span></a></li>
      <li><a href="/2025/12/28/naoki-hojicha-powder-light-vs-dark-roast-comparison.html"><span class="cs-rel-date"><span><strong>28</strong><span>Dec 25</span></span></span><span><span class="cs-rel-title">Naoki Hojicha Powder Review: Light vs Dark Roast</span><span class="cs-rel-blurb">Naoki Classic Roast vs Sundays Kuma in an iced hojicha latte.</span></span></a></li>
      <li><a href="/2025/11/23/naoki-organic-matcha-blend-l-plus-review.html"><span class="cs-rel-date"><span><strong>23</strong><span>Nov 25</span></span></span><span><span class="cs-rel-title">Naoki Organic Matcha Blend L+ Review</span><span class="cs-rel-blurb">A ~50kg limited-edition Uji micro-lot, tested as an iced Bonsoy latte.</span></span></a></li>
    </ul>
  </section>

</div>
