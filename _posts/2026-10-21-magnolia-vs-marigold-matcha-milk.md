---
layout: post
title: "Magnolia Matcha Flavoured Milk vs Marigold HL Select Matcha Latte: Showdown Review"
date: 2026-10-21
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
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Product",
      "name": "F&N Magnolia Matcha Flavoured Milk",
      "description": "Matcha flavoured milk made with fresh milk and matcha green tea powder. 8.5g protein and 25.8g total sugars per 250ml serving, Nutri-Grade C.",
      "image": "https://img.youtube.com/vi/fUSKfXO77RQ/hqdefault.jpg",
      "brand": { "@type": "Brand", "name": "F&N Magnolia" },
      "offers": { "@type": "Offer", "price": "3.40", "priceCurrency": "SGD", "availability": "https://schema.org/InStock" }
    },
    {
      "@type": "Product",
      "name": "Marigold HL Select Matcha Latte",
      "description": "High calcium, high protein, 99% fat-free matcha milk with 9 vitamins. 10.5g protein and 22.5g total sugars per 250ml serving, Nutri-Grade B. 946ml.",
      "image": "https://img.youtube.com/vi/fUSKfXO77RQ/hqdefault.jpg",
      "brand": { "@type": "Brand", "name": "Marigold" },
      "offers": { "@type": "Offer", "price": "3.95", "priceCurrency": "SGD", "availability": "https://schema.org/InStock" }
    },
    {
      "@type": "VideoObject",
      "name": "Magnolia Matcha Flavoured Milk vs Marigold HL Select Matcha Latte",
      "description": "A 4-round showdown comparing F&N Magnolia Matcha Flavoured Milk and Marigold HL Select Matcha Latte on price, colour, protein, sweetness, Nutri-Grade and milk base.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/fUSKfXO77RQ/hqdefault.jpg"
      ],
      "uploadDate": "2026-10-21",
      "contentUrl": "https://www.youtube.com/shorts/fUSKfXO77RQ",
      "embedUrl": "https://www.youtube.com/embed/fUSKfXO77RQ"
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

  <!-- Hero: the two contenders -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">Magnolia vs Marigold: Matcha Milk Showdown</h1>
      <p class="cs-where">F&N Magnolia Matcha Flavoured Milk vs Marigold HL Select Matcha Latte · 4 rounds</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-banana" href="#showdown" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🥛</span>
        <strong>F&N Magnolia</strong>
        <span class="cs-from">$3.40 · Made with fresh milk · Nutri-Grade C</span>
      </a>
      <a class="cs-counter cs-counter-matcha" href="#showdown" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">💪</span>
        <strong>Marigold HL Select</strong>
        <span class="cs-from">$3.95 · 10.5g protein per serve · Nutri-Grade B</span>
      </a>
    </div>
  </header>

  <p>F&N Magnolia has just launched its new <strong>Matcha Flavoured Milk</strong>, so I put it in the ring against the existing <strong>Marigold HL Select Matcha Latte</strong> in a fighting-game-style showdown.</p>
  <p>Here is the round-by-round breakdown covering price, colour, protein, sweetness and milk base, plus the full nutrition labels side by side and which one to pick for your needs.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the showdown</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DeuHOjCu3lL/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DeuHOjCu3lL/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/fUSKfXO77RQ"
        title="Magnolia Matcha Flavoured Milk vs Marigold HL Select Matcha Latte"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSgDJnQVN/" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/share/r/14tUXmA4n6k/" target="_blank" rel="noopener">watch on Facebook</a>
    </p>
  </section>

  <!-- Showdown -->
  <section class="cs-board cs-board-matcha" id="showdown">
    <h2>🥊 The 4-round showdown</h2>

    <div class="cs-round">
      <div class="cs-round-head"><span>Round 1</span><h3>Price</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-std"><strong>F&N Magnolia <span class="cs-win">Winner</span></strong><span class="cs-big">$3.40</span><p>The more affordable pick.</p></div>
        <div class="cs-vs-sas"><strong>Marigold HL Select</strong><span class="cs-big">$3.95</span><p>55 cents more.</p></div>
      </div>
    </div>

    <div class="cs-round">
      <div class="cs-round-head"><span>Round 2</span><h3>Colour & appearance</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-std"><strong>F&N Magnolia</strong><p>Pale, milky pastel green.</p></div>
        <div class="cs-vs-sas"><strong>Marigold HL Select</strong><p>Noticeably greener. Blanka would approve.</p></div>
      </div>
    </div>

    <div class="cs-round">
      <div class="cs-round-head"><span>Round 3</span><h3>Protein (per 250ml serving)</h3></div>
      <div class="cs-vs">
        <div class="cs-vs-std"><strong>F&N Magnolia</strong><span class="cs-big">8.5g</span><p>1.5 servings give at least 10g protein a day.</p></div>
        <div class="cs-vs-sas"><strong>Marigold HL Select <span class="cs-win">Winner</span></strong><span class="cs-big">10.5g</span><p>2 servings give at least 20g protein a day, making it Ken's ideal post-workout pick.</p></div>
      </div>
    </div>

    <div class="cs-round">
      <div class="cs-round-head"><span>Final round</span><h3>Taste, sweetness & milk quality</h3></div>
      <div class="cs-round-note">🍵 <strong>Matcha:</strong> both use real matcha powder plus flavouring.</div>
      <div class="cs-round-sub">Sweetness & Nutri-Grade (per 100ml)</div>
      <div class="cs-vs">
        <div class="cs-vs-std"><strong>F&N Magnolia</strong><span class="cs-big">Grade C</span><p>Noticeably sweeter. 10.3g total sugars, including 4.5g added sugar.</p></div>
        <div class="cs-vs-sas"><strong>Marigold HL Select <span class="cs-win">Better grade</span></strong><span class="cs-big">Grade B</span><p>Less sweet. 9.0g total sugars, including 3.5g added sugar.</p></div>
      </div>
      <div class="cs-round-sub">Milk base & mouthfeel</div>
      <div class="cs-vs">
        <div class="cs-vs-std"><strong>F&N Magnolia <span class="cs-win">Winner</span></strong><p>Made with fresh milk (plus milk solids), with 1.8g fat per 100ml. Richer and creamier, and it wins on mouthfeel.</p></div>
        <div class="cs-vs-sas"><strong>Marigold HL Select</strong><p>Made from milk solids, no fresh milk. 99% fat-free at 0.6g fat per 100ml, so it's lighter in the mouth.</p></div>
      </div>
    </div>
  </section>

  <!-- Nutrition -->
  <section class="cs-info" id="nutrition">
    <h2>Nutrition labels side by side</h2>
    <p class="cs-lede">Per 250ml serving (1 glass). Both cartons hold about 4 servings.</p>
    <div class="cs-table-wrap">
      <table class="cs-table">
        <thead>
          <tr><td></td><th scope="col">F&N Magnolia</th><th scope="col">Marigold HL Select</th></tr>
        </thead>
        <tbody>
          <tr><th scope="row">Price</th><td>$3.40</td><td>$3.95</td></tr>
          <tr><th scope="row">Nutri-Grade</th><td>C</td><td>B</td></tr>
          <tr><th scope="row">Energy</th><td>180 kcal</td><td>156 kcal</td></tr>
          <tr><th scope="row">Protein</th><td>8.5g</td><td>10.5g</td></tr>
          <tr><th scope="row">Total fat</th><td>4.5g</td><td>1.5g</td></tr>
          <tr><th scope="row">Saturated fat</th><td>3.5g</td><td>1.0g</td></tr>
          <tr><th scope="row">Total sugars</th><td>25.8g</td><td>22.5g</td></tr>
          <tr><th scope="row">Added sugar</th><td>11.3g</td><td>8.8g</td></tr>
          <tr><th scope="row">Lactose</th><td>14.5g</td><td>13.8g</td></tr>
          <tr><th scope="row">Dietary fibre</th><td>1.5g</td><td>0g</td></tr>
          <tr><th scope="row">Sodium</th><td>95mg</td><td>138mg</td></tr>
          <tr><th scope="row">Calcium</th><td>290mg</td><td>500mg</td></tr>
          <tr><th scope="row">Added vitamins</th><td>None</td><td>9 (A, B1, B3, B5, B6, C, D3, E, K1)</td></tr>
          <tr><th scope="row">Milk base</th><td>Fresh milk + milk solids</td><td>Milk solids</td></tr>
          <tr><th scope="row">Colour</th><td>Pale pastel green</td><td>Greener</td></tr>
        </tbody>
      </table>
    </div>
  </section>

  <!-- Ingredients -->
  <section class="cs-board cs-board-banana">
    <h2>📋 Ingredients</h2>
    <div class="cs-special">
      <div class="cs-special-head"><h4>F&N Magnolia Matcha Flavoured Milk</h4></div>
      <p class="cs-ingredients">Water, fresh milk, milk solids, sucrose, matcha green tea powder, emulsifier, stabilisers, flavouring.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Marigold HL Select Matcha Latte</h4></div>
      <p class="cs-ingredients">Water, milk solids, sucrose, matcha powder, calcium carbonate, emulsifier, flavouring, stabiliser, potassium carbonate, di-sodium phosphate, vitamin C, vitamin E, nicotinamide, calcium-D-pantothenate, vitamin B6, vitamin B1, vitamin A palmitate, vitamin K1 and vitamin D3.</p>
    </div>
    <p class="cs-note">Magnolia is pasteurised and homogenised. Shake well, keep refrigerated at 2°C to 4°C, and finish within 3 days of opening.</p>
  </section>

  <!-- Verdict -->
  <section class="cs-board cs-board-matcha">
    <h2>🏆 Verdict: which should you pick?</h2>
    <div class="cs-picks">
      <div class="cs-pick cs-pick-magnolia">
        <h3>Pick F&N Magnolia if you want…</h3>
        <ul>
          <li>A drink made with fresh milk</li>
          <li>A richer, creamier texture</li>
          <li>A sweeter profile</li>
          <li>The lower price ($3.40 vs $3.95)</li>
        </ul>
      </div>
      <div class="cs-pick cs-pick-marigold">
        <h3>Pick Marigold HL Select if you want…</h3>
        <ul>
          <li>More protein (10.5g per serve)</li>
          <li>Less sugar and a Nutri-Grade B</li>
          <li>Lower fat (99% fat-free)</li>
          <li>More calcium plus 9 added vitamins</li>
          <li>A greener matcha look</li>
        </ul>
      </div>
    </div>
  </section>

</div>
