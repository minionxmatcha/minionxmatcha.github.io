---
layout: post
title: "KOKO KAWANE: Full Menu, Matcha Cultivar Prices, Cakes & Free Keychain GWP"
date: 2026-10-04
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
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "CafeOrCoffeeShop",
      "name": "KOKO KAWANE",
      "description": "Specialty Japanese tea cafe featuring single-origin freshly milled matcha from Kawane, Shizuoka, alongside artisanal entremets and roasted hojicha.",
      "image": "https://img.youtube.com/vi/V50bSCr9Ykc/hqdefault.jpg",
      "servesCuisine": ["Matcha", "Japanese Tea", "Desserts"],
      "priceRange": "$$",
      "hasMenu": {
        "@type": "Menu",
        "name": "KOKO KAWANE Full Menu"
      }
    },
    {
      "@type": "VideoObject",
      "name": "Koko Kawane Full Menu and Price Breakdown",
      "description": "Complete breakdown of KOKO KAWANE's stone micro-milled matcha lattes, usucha flights, hojicha varieties, cake cross-sections, and the free mystery box keychain promotion.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/V50bSCr9Ykc/hqdefault.jpg"
      ],
      "uploadDate": "2026-10-04",
      "contentUrl": "https://www.youtube.com/shorts/V50bSCr9Ykc",
      "embedUrl": "https://www.youtube.com/embed/V50bSCr9Ykc"
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
      <h1 class="cs-title">KOKO KAWANE: Full Menu & Price Guide</h1>
      <p class="cs-where">Single-origin matcha from Kawane, Shizuoka · Stone-milled on site</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-matcha" href="#matcha" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">🍵</span>
        <strong>Matcha & hojicha</strong>
        <span class="cs-from">Lattes from $8.50</span>
      </a>
      <a class="cs-counter cs-counter-banana" href="#cakes" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🍰</span>
        <strong>Cakes & pairings</strong>
        <span class="cs-from">Cakes from $10</span>
      </a>
    </div>
  </header>

  <p><strong>KOKO KAWANE</strong> spotlights premium tea harvests from the mountainous Kawane region in Shizuoka, Japan. Its signature feature is an on-site <strong>stone micro-mill</strong>, grinding freshly harvested single-origin tencha into matcha daily.</p>
  <p>Here is the complete menu breakdown covering their matcha lattes, usucha flights, cake flavours, roasted hojicha, retail powder tins, and their current gift-with-purchase promotion.</p>

  <p class="cs-crosslink">🎁 <strong>Free keychain:</strong> spend $25 or more in a single receipt for a Matcha Club Mystery Box Keychain. <a href="#keychain">See the collectibles</a>.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video walkthrough</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DeDk_eou1pq/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DeDk_eou1pq/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/V50bSCr9Ykc"
        title="Koko Kawane Full Menu and Price Breakdown"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSbHRXNrm/" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/share/r/1DX8fyYYnu/" target="_blank" rel="noopener">watch on Facebook</a>
    </p>
  </section>

  <!-- Matcha -->
  <section class="cs-board cs-board-matcha" id="matcha">
    <h2>🍵 Matcha</h2>

    <h3 class="cs-sub">The fresh micro-mill experience</h3>
    <div class="cs-mill">
      <div class="cs-mill-head"><h4>Fresh-mill upgrade</h4><span class="cs-special-price">+$1</span></div>
      <p>Okumidori single origin <small>(first flush, 2026 harvest, 一番茶)</small>. Add to any drink. Ground directly on the stone mill counter in small micro-batches to preserve aroma and prevent oxidation.</p>
    </div>

    <h3 class="cs-sub">Matcha lattes (3 flavour profiles)</h3>
    <div class="cs-special">
      <div class="cs-special-head"><h4>House Blend <small class="cs-jp">特製合組</small></h4><span class="cs-special-price">$8.50</span></div>
      <p>Balanced.</p>
      <ul class="cs-chips" aria-label="Flavour profile"><li>Moderate umami</li><li>Moderate bitterness</li><li>Light–medium body</li></ul>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Okumidori <small class="cs-jp">おくみどり</small></h4><span class="cs-special-price">$12.50</span></div>
      <p>Savoury and rich.</p>
      <ul class="cs-chips" aria-label="Flavour profile"><li>High umami</li><li>Low bitterness</li><li>Heavy, velvety body</li></ul>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Soemon Blend <small class="cs-jp">想右衛門</small></h4><span class="cs-special-price">$13.50</span></div>
      <p>Silky and deep.</p>
      <ul class="cs-chips" aria-label="Flavour profile"><li>Low umami</li><li>Clean bitterness</li><li>Robust body</li></ul>
    </div>

    <h3 class="cs-sub">Pure usucha (thin tea)</h3>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Tsuyuhikari <small class="cs-jp">つゆひかり</small></h4><span class="cs-tag">Hot or iced</span><span class="cs-special-price">$7.00</span></div>
      <p>Gentle and floral.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Okumidori <small class="cs-jp">おくみどり</small></h4><span class="cs-tag">Hot or iced</span><span class="cs-special-price">$7.00</span></div>
      <p>Bold, savoury and punchy.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Usucha Flight</h4><span class="cs-tag">Hot only</span><span class="cs-special-price">$17.00</span></div>
      <p>Three side-by-side bowls of Tsuyuhikari, Soemon and Okumidori.</p>
    </div>

    <p class="cs-note">Soemon is exclusive to the flight and latte. It is not sold as a standalone single cup.</p>
  </section>

  <!-- Cakes -->
  <section class="cs-board cs-board-banana" id="cakes">
    <h2>🍰 Artisanal cakes & tea pairings</h2>

    <h3 class="cs-sub">Matcha cakes</h3>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Midoba <small class="cs-jp">翠葉</small></h4><span class="cs-special-price">$10.00</span></div>
      <p>Matcha with a raspberry core.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Akane <small class="cs-jp">茜空</small></h4><span class="cs-special-price">$12.00</span></div>
      <p>Matcha with a sweet mango insert.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Hisui <small class="cs-jp">翡翠</small></h4><span class="cs-special-price">$14.00</span></div>
      <p>Geometric multifaceted green gem filled with matcha and strawberry.</p>
    </div>

    <h3 class="cs-sub">Hojicha cakes</h3>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Kohaku <small class="cs-jp">琥珀</small></h4><span class="cs-special-price">$10.00</span></div>
      <p>Roasted hojicha with passionfruit.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Kirizakura <small class="cs-jp">霧桜</small></h4><span class="cs-special-price">$12.00</span></div>
      <p>Roasted hojicha with peach.</p>
    </div>

    <h3 class="cs-sub">Ochagashi (cake & tea pairing sets)</h3>
    <p class="cs-lede">Save money compared to ordering à la carte.</p>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Gentle Pairing</h4><span class="cs-tag">Save $4</span><span class="cs-special-price">$15.00</span></div>
      <p>Tsuyuhikari usucha + Akane (matcha & mango).</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Bold Pairing</h4><span class="cs-tag">Save $2</span><span class="cs-special-price">$15.00</span></div>
      <p>Okumidori usucha + Kohaku (hojicha & passionfruit).</p>
    </div>
  </section>

  <!-- Hojicha -->
  <section class="cs-board cs-board-matcha">
    <h2>🍂 Hojicha (3 preparation styles)</h2>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Hojicha Latte</h4><span class="cs-special-price">$8.00</span></div>
      <p>Medium roast combining stems and leaves for a creamy, well-rounded cup.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Karigane Hojicha</h4><span class="cs-tag">Stem</span><span class="cs-special-price">$7.00</span></div>
      <p>Roasted stem tea with a lighter body and natural sweetness.</p>
    </div>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Kasuga Hojicha</h4><span class="cs-tag">Leaf</span><span class="cs-special-price">$7.00</span></div>
      <p>Roasted leaf tea with a richer, deeper, toastier aroma.</p>
    </div>
  </section>

  <!-- Retail tins -->
  <section class="cs-board cs-board-banana">
    <h2>🥫 Retail tea tins (50g each)</h2>
    <ul class="cs-prices">
      <li><span class="cs-item">Tsuyuhikari <small class="cs-jp">50g</small></span><span class="cs-dots"></span><span class="cs-price">$45.00</span></li>
      <li><span class="cs-item">Soemon <small class="cs-jp">50g</small></span><span class="cs-dots"></span><span class="cs-price">$40.00</span></li>
      <li><span class="cs-item">Okumidori <small class="cs-jp">50g</small></span><span class="cs-dots"></span><span class="cs-price">$45.00</span></li>
      <li><span class="cs-item">Complete Matcha Trio Set <small class="cs-jp">3 × 50g</small></span><span class="cs-dots"></span><span class="cs-price">$115.00</span></li>
      <li><span class="cs-item">Hojicha Powder Tin <small class="cs-jp">50g</small></span><span class="cs-dots"></span><span class="cs-price">$20.00</span></li>
    </ul>
  </section>

  <!-- Keychain GWP -->
  <section class="cs-promo cs-promo-dark" id="keychain" style="margin-bottom: 30px;">
    <div class="cs-promo-head">
      <span class="cs-promo-badge">🎁 Free Matcha Club Mystery Box Keychain</span>
      <span class="cs-promo-sub">Spend $25+ in a single receipt · While stocks last</span>
    </div>
    <div class="cs-promo-body">
      <p>Spend <strong>$25.00 or more in a single receipt</strong> to receive one free Matcha Club Mystery Box Keychain. The blind box series has three collectibles:</p>
    </div>
    <ul class="cs-collect">
      <li><span class="cs-collect-emoji" aria-hidden="true">🎋</span><strong>The Chasen</strong><span>Miniature bamboo whisk</span></li>
      <li><span class="cs-collect-emoji" aria-hidden="true">🫙</span><strong>The Chakan</strong><span>Miniature tea caddy</span></li>
      <li class="cs-secret"><span class="cs-collect-emoji" aria-hidden="true">❓</span><strong>Secret Chawan</strong><span>Miniature matcha bowl with a tiny whisk inside</span></li>
    </ul>
  </section>

</div>
