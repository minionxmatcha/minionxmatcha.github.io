---
layout: post
title: "Naoki Matcha Barista Pro Blend Review: The Ultimate Choice for Lattes & Home Pop-Ups"
date: 2026-03-25
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

  /* Barista Pro pop-up additions */
  .cs-menu { background: var(--ink); color: #fff; border: 2px solid var(--ink); border-radius: 28px; padding: 26px 22px; margin: 0 0 22px; box-shadow: 6px 6px 0 var(--banana); }
  .cs-menu h2 { color: var(--banana); margin-bottom: 4px; }
  .cs-menu .cs-lede { color: #e8e2c8; }
  .cs-menu-list { list-style: none; margin: 0; padding: 0; display: grid; gap: 12px; }
  .cs .cs-menu-list > li { margin: 0; display: grid; grid-template-columns: 54px 1fr; gap: 16px; align-items: center; padding: 14px 16px; border: 1.5px solid rgba(255,210,63,.55); border-radius: 18px; }
  .cs-cupmini { width: 54px; height: 76px; border: 2px solid #fff; border-top: 0; border-radius: 0 0 14px 14px; overflow: hidden; display: flex; flex-direction: column; background: rgba(255,255,255,.08); }
  .cs-cupmini div { flex: 1; border-top: 1px dashed rgba(42,38,22,.35); }
  .cs-cupmini div:first-child { border-top: 0; }
  .cs-menu-name { display: block; font-family: var(--display); font-weight: 800; font-size: 18px; line-height: 1.2; color: var(--banana); margin-bottom: 4px; }
  .cs-menu-list p { margin: 0; font-size: 15px; color: #f3efe0; }
  .cs-menu-num { font-family: var(--body); font-weight: 700; font-size: 12px; color: #d8d2b8; display: block; margin-bottom: 2px; }
  .cs-menu .cs-chips li { background: transparent; color: #fff; border-color: var(--banana); }
  .cs-menu .cs-chips a { color: var(--banana); }
  .cs-menu h3.cs-sub { color: #fff; }
  .cs-hue { display: inline-block; width: 14px; height: 14px; border-radius: 50%; border: 1.5px solid var(--ink); background: #2F7A3A; vertical-align: -2px; margin-right: 6px; }

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
      "name": "Naoki Matcha Barista Pro Blend (First Harvest Ceremonial Grade)",
      "description": "First harvest ceremonial grade Japanese matcha from Uji, Kyoto by Naoki Matcha, specifically formulated to cut through milk and fruit purees in iced matcha lattes and home cafe pop-ups.",
      "image": "https://img.youtube.com/vi/Fd88JIws9kw/hqdefault.jpg",
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
        "reviewBody": "Naoki Matcha's Barista Pro Blend is the ultimate workhorse for hosting a home matcha pop-up. Sourced from first harvest Uji leaves, it whisks effortlessly across back-to-back orders with a vivid emerald layer and delivers enough bold umami structure to shine through rich Bonsoy soy milk, strawberry compote, and mango purees without getting muted."
      }
    },
    {
      "@type": "VideoObject",
      "name": "Minion Matcha Pop-Up Featuring Naoki Matcha Barista Pro Blend",
      "description": "Hosting a home matcha pop-up for friends using Naoki Matcha's Barista Pro Blend from Uji, Kyoto across classic Bonsoy, strawberry, and mango iced matcha lattes.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/Fd88JIws9kw/hqdefault.jpg"
      ],
      "uploadDate": "2026-03-25",
      "contentUrl": "https://www.youtube.com/shorts/Fd88JIws9kw",
      "embedUrl": "https://www.youtube.com/embed/Fd88JIws9kw"
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
      <h1 class="cs-title">Naoki Matcha Barista Pro Blend: The Perfect Choice for Home Pop-Ups & Lattes</h1>
      <p class="cs-where">First-harvest ceremonial grade · Uji, Kyoto · Tested at a home matcha pop-up</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-matcha" href="#why" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">💪</span>
        <strong>Never gets lost</strong>
        <span class="cs-from">Bold enough for milk & fruit purees</span>
      </a>
      <a class="cs-counter cs-counter-banana" href="#menu" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🥤</span>
        <strong>4 drinks, back to back</strong>
        <span class="cs-from">See the pop-up menu</span>
      </a>
    </div>
  </header>

  <p>When you're hosting a home matcha pop-up for friends and whisking four custom drinks back to back, the wrong matcha powder quickly gives you muted, milky drinks. Enter <strong>Naoki Matcha's Barista Pro Blend</strong>, a first-harvest ceremonial grade blend from <strong>Uji, Kyoto</strong> made to hold its ground in lattes and fruit drinks.</p>
  <p>Here's why Barista Pro Blend is my go-to for multi-drink service and daily iced lattes.</p>

  <p class="cs-crosslink cs-crosslink-navy">✨ <strong>Newest Naoki review:</strong> the one-time <a href="/2026/11/20/naoki-tenth-harvest-matcha-masters-collection-review.html">Tenth Harvest Matcha (Masters Collection)</a>, celebrating 10 years of Naoki. Only 200 tins for Singapore.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the home pop-up video</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DWTlspuE1_l/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DWTlspuE1_l/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/Fd88JIws9kw"
        title="Minion Matcha Pop-Up Featuring Naoki Barista Pro Blend"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSp7vHe29/" target="_blank" rel="noopener">Watch on TikTok</a>
    </p>
  </section>

  <!-- Why it works -->
  <section class="cs-board cs-board-matcha" id="why">
    <h2>✅ Why it's the perfect pop-up matcha</h2>

    <div class="cs-special">
      <div class="cs-special-head"><h4>Never gets lost in milk or fruit purees</h4><span class="cs-tag">Bold umami</span></div>
      <p>Delicate single-cultivar matchas meant for straight usucha often disappear the moment you pour them over creamy plant milks or sweet fruit bases. Barista Pro Blend is blended from first-harvest Uji leaves to give a fuller, punchier tea presence. Over Bonsoy, tangy strawberry compote or sweet mango puree, its earthy, roasted-umami backbone stays front and centre.</p>
    </div>

    <div class="cs-special">
      <div class="cs-special-head"><h4>Built for fast, multi-cup workflows</h4><span class="cs-tag">Minimal clumping</span></div>
      <p>When you're whisking four drinks in a row in a spouted chawan, consistency is everything. It wets quickly into a smooth paste and whips up a tight emerald-green microfoam cap in seconds, for clean, café-worthy three-tier layers in custom MXM takeaway cups.</p>
    </div>

    <p class="cs-note">🥛 <strong>Bonsoy fan?</strong> See how Naoki's limited <a href="/2025/11/23/naoki-organic-matcha-blend-l-plus-review.html">Organic Matcha Blend L+</a> pairs with Bonsoy, with zero bitterness.</p>
  </section>

  <!-- Pop-up menu -->
  <section class="cs-menu" id="menu">
    <h2>🥤 The 4-drink home pop-up menu</h2>
    <p class="cs-lede">All made with Barista Pro Blend.</p>
    <ol class="cs-menu-list">
      <li>
        <div class="cs-cupmini" aria-hidden="true"><div style="background:#4F8A3A;"></div><div style="background:#F3EAD6;"></div><div style="background:#F3EAD6;"></div></div>
        <div><span class="cs-menu-num">No. 1</span><span class="cs-menu-name">Classic Iced Bonsoy Matcha Latte</span><p>Whisked matcha floated over ice and creamy Bonsoy, letting the pure Uji umami and subtle nuttiness shine.</p></div>
      </li>
      <li>
        <div class="cs-cupmini" aria-hidden="true"><div style="background:#4F8A3A;"></div><div style="background:#FBF6EA;"></div><div style="background:#C9283E;"></div></div>
        <div><span class="cs-menu-num">No. 2</span><span class="cs-menu-name">Iced Strawberry Matcha Latte</span><p>Ruby-red strawberry compote, cold milk and a bold matcha cap that balances out the berry sweetness.</p></div>
      </li>
      <li>
        <div class="cs-cupmini" aria-hidden="true"><div style="background:#4F8A3A;"></div><div style="background:#FBF6EA;"></div><div style="background:#F5B22E;"></div></div>
        <div><span class="cs-menu-num">No. 3</span><span class="cs-menu-name">Iced Mango Matcha Latte</span><p>Sweet tropical mango puree at the base, milk in the middle and earthy Uji matcha on top.</p></div>
      </li>
      <li>
        <div class="cs-cupmini" aria-hidden="true"><div style="background:#4F8A3A;"></div><div style="background:#4F8A3A;"></div><div style="background:#4F8A3A;"></div></div>
        <div><span class="cs-menu-num">No. 4</span><span class="cs-menu-name">Signature Iced Matcha</span><p>Completing the four-cup flight.</p></div>
      </li>
    </ol>

    <h3 class="cs-sub">On the side</h3>
    <ul class="cs-chips">
      <li>Two-tone matcha seashell madeleines by <a href="https://www.instagram.com/shesells.seashells.sg" target="_blank" rel="noopener">@shesells.seashells.sg</a></li>
      <li>Kimbap</li>
      <li>Tteokbokki</li>
    </ul>
  </section>

  <!-- Specs -->
  <section class="cs-info">
    <h2>Barista Pro Blend at a glance</h2>
    <dl>
      <dt>Brand & blend</dt>
      <dd>Naoki Fine Japanese Matcha, Barista Pro Blend</dd>
      <dt>Origin & harvest</dt>
      <dd>Uji, Kyoto, Japan<br>First-harvest ceremonial grade</dd>
      <dt>Colour</dt>
      <dd><span class="cs-hue" aria-hidden="true"></span>Deep, vibrant emerald green, dry and whisked</dd>
      <dt>In lattes</dt>
      <dd>Bold umami and structured body that cuts through rich milks and sweet fruit purees</dd>
      <dt>Workflow</dt>
      <dd>Disperses quickly with minimal clumping, for fast back-to-back whisking</dd>
    </dl>
  </section>


  <!-- More Naoki reviews -->
  <section class="cs-board cs-board-matcha" id="more-naoki">
    <h2>🍵 More Naoki Matcha reviews</h2>
    <p class="cs-lede">My other Naoki Matcha reviews, newest first.</p>
    <ul class="cs-related">
      <li class="cs-rel-new"><a href="/2026/11/20/naoki-tenth-harvest-matcha-masters-collection-review.html"><span class="cs-rel-date"><span><strong>20</strong><span>Nov 26</span></span></span><span><span class="cs-rel-title">Naoki Tenth Harvest Matcha Review (Masters Collection)<span class="cs-rel-new-tag">Newest</span></span><span class="cs-rel-blurb">A one-time Okumidori × Saemidori release, with only 200 tins for Singapore.</span></span></a></li>
      <li><a href="/2026/05/11/naoki-limited-edition-yame-single-cultivar-matcha-set-review.html"><span class="cs-rel-date"><span><strong>11</strong><span>May 26</span></span></span><span><span class="cs-rel-title">Naoki Limited Edition Yame Single-Cultivar Matcha Set Review</span><span class="cs-rel-blurb">Kirari 31, Okumidori, Seimei & Yabukita in a 4-cultivar blind latte test.</span></span></a></li>
      <li><a href="/2026/04/26/naoki-matcha-japan-hatsu-roku-house-roast-hojicha-review.html"><span class="cs-rel-date"><span><strong>26</strong><span>Apr 26</span></span></span><span><span class="cs-rel-title">Naoki Matcha Japan Series: Hatsu, Roku & House Roast Hojicha</span><span class="cs-rel-blurb">Uji vs Yame matcha, plus a smoky, chocolatey hojicha.</span></span></a></li>
      <li><a href="/2025/12/28/naoki-hojicha-powder-light-vs-dark-roast-comparison.html"><span class="cs-rel-date"><span><strong>28</strong><span>Dec 25</span></span></span><span><span class="cs-rel-title">Naoki Hojicha Powder Review: Light vs Dark Roast</span><span class="cs-rel-blurb">Naoki Classic Roast vs Sundays Kuma in an iced hojicha latte.</span></span></a></li>
      <li><a href="/2025/11/23/naoki-organic-matcha-blend-l-plus-review.html"><span class="cs-rel-date"><span><strong>23</strong><span>Nov 25</span></span></span><span><span class="cs-rel-title">Naoki Organic Matcha Blend L+ Review</span><span class="cs-rel-blurb">A ~50kg limited-edition Uji micro-lot, tested as an iced Bonsoy latte.</span></span></a></li>
    </ul>
  </section>

</div>
