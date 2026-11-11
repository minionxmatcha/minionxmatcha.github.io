---
layout: post
title: "Unboxing 72 Minions Mini Stackable Blind Boxes: Hunting the 0.23% Secret Bob"
date: 2026-11-11
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

  /* EIEN additions */
  .cs-counters-3 { grid-template-columns: repeat(3, 1fr); }
  .cs-counter-moment { background: #C9CF6B; color: var(--ink); }
  .cs-counter-still { background: #5E9E34; color: #fff; }
  .cs-counter-eve { background: #1E5A2E; color: #fff; }
  .cs-counters-3 .cs-counter strong { font-size: 22px; }
  .cs-scale { display: grid; grid-template-columns: repeat(3, 1fr); border: 2px solid var(--ink); border-radius: 18px; overflow: hidden; margin: 0 0 6px; }
  .cs-scale div { padding: 26px 12px 12px; font-size: 13px; }
  .cs-scale div + div { border-left: 2px solid var(--ink); }
  .cs-scale strong { display: block; font-family: var(--display); font-weight: 800; font-size: 18px; }
  .cs-scale-arrow { display: flex; justify-content: space-between; font-size: 12px; font-weight: 700; color: #6b6550; margin: 0 2px 16px; }
  .cs-blend-head { display: flex; align-items: center; gap: 12px; margin-bottom: 8px; }
  .cs-dot { flex: none; width: 34px; height: 34px; border-radius: 50%; border: 2px solid var(--ink); }
  .cs-blend-head h4 { font-family: var(--display); font-weight: 800; font-size: 20px; line-height: 1.1; margin: 0; }
  .cs-blend-head .cs-special-price { margin-left: auto; }
  .cs-shops { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 18px; }
  .cs-shops .cs-map { margin-top: 0; }
  .cs-blend-head small { display: block; font-family: var(--body); font-weight: 400; font-size: 13px; color: #6b6550; }
  .cs-special .cs-blend-tags { display: flex; flex-wrap: wrap; gap: 6px; margin: 0 0 10px; }
  .cs-special dl { margin: 10px 0 0; display: grid; grid-template-columns: 110px 1fr; gap: 6px 12px; font-size: 15px; }
  .cs-special dt { font-weight: 700; font-size: 13px; color: #6b6550; padding-top: 2px; }
  .cs-special dd { margin: 0; }
  .cs-table-blends thead th:nth-child(2) { background: #C9CF6B; color: var(--ink); }
  .cs-table-blends thead th:nth-child(3) { background: #1E5A2E; color: #fff; }
  .cs-table-blends thead th:nth-child(4) { background: #5E9E34; color: #fff; }
  .cs-table-blends td { background: #fff !important; font-size: 14px; }
  .cs-table-blends tbody th { width: 22%; }
  @media (max-width: 600px) {
    .cs-counters-3 { grid-template-columns: 1fr; }
    .cs-counters-3 .cs-counter + .cs-counter { border-left: 0; border-top: 2px solid var(--ink); }
    .cs-special dl { grid-template-columns: 1fr; gap: 0; }
    .cs-special dd { margin-bottom: 8px; }
    .cs-table-blends th, .cs-table-blends td { padding: 8px 6px; font-size: 12px !important; overflow-wrap: anywhere; }
    .cs-table-blends thead th { font-size: 13px; }
    .cs-table-blends tbody th { width: 70px; overflow-wrap: normal; font-size: 11px !important; }
    .cs-info { padding: 22px 14px; }
  }

  /* EIEN Part 2 additions */
  .cs-verdict { display: inline-block; font-size: 12px; font-weight: 700; padding: 3px 10px; border-radius: 999px; border: 1.5px solid var(--ink); white-space: nowrap; }
  .cs-pass { background: var(--foam); color: var(--matcha-deep); }
  .cs-fail { background: #F6D3C4; color: #8A2E12; }
  .cs-counters-3 .cs-counter .cs-results { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 8px; }
  .cs-counters-3 .cs-counter .cs-verdict { border-color: currentColor; }
  .cs-table-blends td .cs-verdict { font-size: 11px; padding: 2px 8px; }
  .cs-vs-fail { background: #FBE7DE; }
  .cs-round-head .cs-dot { width: 22px; height: 22px; display: inline-block; vertical-align: -5px; margin-right: 8px; }
  .cs-vs .cs-verdict { margin-left: 6px; vertical-align: 2px; }
  .cs-info .cs-note { margin-top: 14px; }

  /* Minions blind box additions */
  .cs-special .cs-tag-row { display: flex; flex-wrap: wrap; gap: 6px; margin: 0 0 8px; }
  .cs-special .cs-special-price small { font-family: var(--body); font-weight: 400; font-size: 13px; color: #6b6550; }
  .cs-special-secret .cs-chips li { background: #fff; color: var(--ink); }
  .cs-counter-crystal { background: var(--banana); color: var(--ink); }
  .cs-counter-jelly { background: var(--matcha); color: #fff; }
  .cs-counter-secret { background: var(--ink); color: var(--banana); }
  .cs-counter-secret span.cs-from { color: #fff; }
  .cs-jackpot { position: relative; border: 2px solid var(--ink); border-radius: 22px; background: var(--ink); color: #fff; padding: 22px 22px 20px; margin: 0 0 30px; box-shadow: 6px 6px 0 var(--banana); }
  .cs-jackpot-label { display: inline-block; font-size: 12px; font-weight: 700; padding: 3px 10px; border-radius: 999px; background: var(--banana); color: var(--ink); margin-bottom: 10px; }
  .cs-jackpot h2 { color: var(--banana); margin: 0 0 6px; }
  .cs-jackpot p { margin: 0; font-size: 15px; }
  .cs-jackpot-stats { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin-top: 16px; }
  .cs-jackpot-stats div { border: 1.5px solid rgba(255,210,63,.6); border-radius: 14px; padding: 10px 12px; }
  .cs-jackpot-stats strong { display: block; font-family: var(--display); font-weight: 800; font-size: 22px; color: var(--banana); line-height: 1.1; }
  .cs-jackpot-stats span { font-size: 12px; }
  .cs-tier-cn { font-family: var(--body); font-weight: 400; font-size: 13px; color: #6b6550; margin-left: 4px; }
  .cs-special-secret { background: var(--ink); color: #fff; }
  .cs-special-secret h4 { color: var(--banana); }
  .cs-special-secret .cs-tier-cn { color: #d8d2b8; }
  .cs-special-secret .cs-tag { background: var(--banana); color: var(--ink); }
  @media (max-width: 600px) { .cs-jackpot-stats { grid-template-columns: 1fr; } }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Product",
      "name": "Kayou Minions Mini Stackable Colorful Rainbow Series (小黄人 mini 叠叠乐 缤纷彩虹系列)",
      "description": "Collectible mini translucent Minions blind bags by Kayou featuring 26 designs across Crystal Glitter, Gradient Jelly, and 0.23% Secret Bob editions.",
      "image": "https://img.youtube.com/vi/07VM6SBn2mM/hqdefault.jpg",
      "brand": {
        "@type": "Brand",
        "name": "Kayou (卡游)"
      },
      "review": {
        "@type": "Review",
        "author": {
          "@type": "Person",
          "name": "minionxmatcha"
        },
        "reviewBody": "Unboxed 72 blind packs from the Kayou Minions Mini Stackable Colorful Rainbow Series, successfully pulling the 0.23% Secret Bob with Tim figure. The translucent Crystal Glitter and Gradient Jelly finishes illuminate vividly when displayed on an LED spotlight cube."
      }
    },
    {
      "@type": "VideoObject",
      "name": "72 Minions Blind Box Unboxing: Hunting the 0.23% Secret Bob",
      "description": "Unboxing 72 Kayou Minions Mini Stackable Colorful Rainbow Series blind bags in search of the ultra-rare 0.23% Secret Bob figure.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/07VM6SBn2mM/hqdefault.jpg"
      ],
      "uploadDate": "2026-11-11",
      "contentUrl": "https://www.youtube.com/shorts/07VM6SBn2mM",
      "embedUrl": "https://www.youtube.com/embed/07VM6SBn2mM"
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

  <!-- Hero: the three rarity tiers -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">Unboxing 72 Minions Blind Boxes: Chasing the 0.23% Secret Bob</h1>
      <p class="cs-where">Kayou 小黄人 mini 叠叠乐 缤纷彩虹系列 · 26 designs · 3 tiers</p>
    </div>
    <div class="cs-counters cs-counters-3">
      <a class="cs-counter cs-counter-crystal" href="#tiers" style="text-decoration:none;color:var(--ink);">
        <strong>Crystal Glitter</strong>
        <span class="cs-from">12 designs · 6.96% each</span>
      </a>
      <a class="cs-counter cs-counter-jelly" href="#tiers" style="text-decoration:none;color:#fff;">
        <strong>Gradient Jelly</strong>
        <span class="cs-from">12 designs · 1.36–1.56% each</span>
      </a>
      <a class="cs-counter cs-counter-secret" href="#tiers" style="text-decoration:none;color:var(--banana);">
        <strong>Secret Bob</strong>
        <span class="cs-from">2 designs · 0.23% each</span>
      </a>
    </div>
  </header>

  <p>With <strong>72 Minions blind bags</strong> on the table, only one target truly mattered: the ultra-rare <strong>0.23% Secret Bob</strong> from the <strong>Kayou Minions Mini Stackable Colorful Rainbow Series (小黄人 mini 叠叠乐 缤纷彩虹系列)</strong>.</p>
  <p>The series has 26 collectible designs across three translucent finishes. Here is the complete pull rate breakdown, checklist results and LED spotlight showcase.</p>

  <!-- The pull -->
  <section class="cs-jackpot">
    <span class="cs-jackpot-label">🎉 Pulled!</span>
    <h2>Secret Bob-B with Tim the Bear</h2>
    <p>The golden-amber translucent chase figure, pulled straight from the batch of 72.</p>
    <div class="cs-jackpot-stats">
      <div><strong>0.23%</strong><span>Official pull rate</span></div>
      <div><strong>1 in 435</strong><span>Odds per pack</span></div>
      <div><strong>~15%</strong><span>Chance of pulling it in 72 packs</span></div>
    </div>
  </section>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the 72-pack unboxing</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DfmQ_V3uRNZ/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DfmQ_V3uRNZ/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/07VM6SBn2mM"
        title="72 Minions Blind Box Unboxing"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSpaKpdhn/" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/share/r/1E6DEchnpB/" target="_blank" rel="noopener">watch on Facebook</a>
    </p>
  </section>

  <!-- Tiers -->
  <section class="cs-board cs-board-banana" id="tiers">
    <h2>🎲 Series breakdown & official pull rates</h2>
    <p class="cs-lede">26 figures in total, split into three rarity tiers.</p>

    <div class="cs-special">
      <div class="cs-special-head"><h4>Crystal Glitter <span class="cs-tier-cn">亮晶晶炫彩款</span></h4><span class="cs-special-price">6.96% <small>each</small></span></div>
      <div class="cs-tag-row"><span class="cs-tag">12 figures</span></div>
      <p>Clear acrylic infused with fine sparkle glitter.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Gradient Jelly <span class="cs-tier-cn">果冻渐变款</span></h4><span class="cs-special-price">1.36–1.56% <small>each</small></span></div>
      <div class="cs-tag-row"><span class="cs-tag">12 figures</span></div>
      <p>Two-tone translucent jelly gradient.</p>
    </div>
    <div class="cs-special cs-special-secret">
      <div class="cs-special-head"><h4>Secret Edition <span class="cs-tier-cn">隐藏萌趣款</span></h4><span class="cs-special-price">0.23% <small style="color:#d8d2b8;">each</small></span></div>
      <div class="cs-tag-row"><span class="cs-tag">2 figures</span></div>
      <ul class="cs-chips" aria-label="Secret figures"><li>Bob-A · pink-yellow gradient</li><li>Bob-B with Tim · golden amber</li></ul>
    </div>
  </section>

  <!-- Results -->
  <section class="cs-board cs-board-matcha">
    <h2>🔦 The pull results & spotlight showcase</h2>
    <ol class="cs-steps">
      <li>
        <h4>Checklist sweep</h4>
        <p>Tearing through all 72 blind packs steadily filled out the collector's sheet across both the Crystal Glitter and Gradient Jelly lineups.</p>
      </li>
      <li>
        <h4>Manifesting the 0.23% Secret Bob</h4>
        <p>Against 1-in-435 odds per pack, the chase figure, <strong>Secret Bob-B holding Tim the Bear</strong> in a golden-amber translucent finish, came straight out of the batch.</p>
      </li>
      <li>
        <h4>LED light cube & stacking test</h4>
        <p>The whole series is moulded from translucent resin, so placing the figures on an illuminated LED cube turns them into glowing desk ornaments. True to their 叠叠乐 (stacking game) name, the flat-top silhouettes stack into towers, right up until gravity takes over.</p>
      </li>
    </ol>
  </section>

</div>
