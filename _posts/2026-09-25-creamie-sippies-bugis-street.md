---
layout: post
title: "Creamie Sippies Bugis Street: Full Menu, Pricing & Store Guide"
date: 2026-09-25
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
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "FoodEstablishment",
      "name": "Creamie Sippies Bugis Street",
      "description": "Corner takeaway store at Bugis Street Level 2 featuring a Banana Pudding Bar and Mini Matcha Bar.",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "261 Victoria Street, #02-115, Bugis Street Level 2",
        "addressLocality": "Singapore",
        "postalCode": "188067",
        "addressCountry": "SG"
      },
      "openingHours": "Mo-Su 12:00-20:00",
      "hasMenu": {
        "@type": "Menu",
        "name": "Creamie Sippies Bugis Street Menu"
      }
    },
    {
      "@type": "VideoObject",
      "name": "Creamie Sippies at Bugis Street",
      "description": "Quick guide and full menu breakdown for Creamie Sippies at Bugis Street #02-115.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/451B9Z1lQJc/hqdefault.jpg"
      ],
      "uploadDate": "2026-09-23",
      "contentUrl": "https://www.youtube.com/shorts/451B9Z1lQJc",
      "embedUrl": "https://www.youtube.com/embed/451B9Z1lQJc"
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

  <!-- Hero: one stall, two counters -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">Creamie Sippies Bugis Street: Full Menu & Store Guide</h1>
      <p class="cs-where">Bugis Street Level 2, #02-115 · Opened 25 September 2026</p>
    </div>
    <div class="cs-counters">
      <div class="cs-counter cs-counter-banana">
        <span class="cs-counter-emoji" aria-hidden="true">🍌</span>
        <strong>Banana Pudding Bar</strong>
        <span class="cs-from">Scoops from $4.50</span>
      </div>
      <div class="cs-counter cs-counter-matcha">
        <span class="cs-counter-emoji" aria-hidden="true">🍵</span>
        <strong>Mini Matcha Bar</strong>
        <span class="cs-from">Lattes from $5.00</span>
      </div>
    </div>
  </header>

  <p>Creamie Sippies has officially opened a takeaway spot on Level 2 of Bugis Street (#02-115, 261 Victoria Street). It's a compact corner stall with two separate counters: a <strong>Banana Pudding Bar</strong> and a <strong>Mini Matcha Bar</strong>.</p>
  <p>Here is the complete menu, customisation pricing, and outlet details before you go.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video preview</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/DdoJahIOl5y/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/DdoJahIOl5y/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (keeps the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/451B9Z1lQJc"
        title="Creamie Sippies Bugis Street Video Preview"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSb8p6HVk/" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/p/Minionxmatcha-61592062657121/" target="_blank" rel="noopener">visit on Facebook</a>
    </p>
  </section>

  <!-- Banana Pudding Bar -->
  <section class="cs-board cs-board-banana">
    <h2>🍌 Banana Pudding Bar</h2>
    <p class="cs-lede">Pudding scoops come in cups with toppings, or tucked inside a warm waffle taco.</p>

    <ul class="cs-prices">
      <li><span class="cs-item">1 Scoop</span><span class="cs-dots"></span><span class="cs-price">$4.50</span></li>
      <li><span class="cs-item">1 Scoop + 2 Toppings</span><span class="cs-dots"></span><span class="cs-price">$5.90</span></li>
      <li><span class="cs-item">2 Scoops + 3 Toppings</span><span class="cs-dots"></span><span class="cs-price">$6.90</span></li>
      <li><span class="cs-item">Banana Pudding Waffle</span><span class="cs-dots"></span><span class="cs-price">$6.90</span></li>
    </ul>

    <h3 class="cs-sub">Customisation & toppings</h3>

    <div class="cs-group">
      <p class="cs-group-name">Crunches</p>
      <ul class="cs-chips">
        <li>Lotus Biscoff Crumbs</li><li>KitKat Crumble</li><li>Oreo Crumbs</li><li>Rainbow Rice</li><li>Rainbow Sprinkles</li>
      </ul>
    </div>
    <div class="cs-group">
      <p class="cs-group-name">Bites</p>
      <ul class="cs-chips">
        <li>Choco Balls</li><li>Mini Marshmallows</li><li>KitKat Balls</li>
      </ul>
    </div>
    <div class="cs-group">
      <p class="cs-group-name">Sauces & drizzles</p>
      <ul class="cs-chips">
        <li>Lotus Biscoff Sauce</li><li>Choco Sauce</li>
      </ul>
    </div>
  </section>

  <!-- Mini Matcha Bar -->
  <section class="cs-board cs-board-matcha">
    <h2>🍵 Mini Matcha Bar</h2>
    <p class="cs-lede">Bamboo-whisked fresh on the spot.</p>

    <ul class="cs-prices">
      <li><span class="cs-item">Classic Matcha Latte</span><span class="cs-dots"></span><span class="cs-price">$5.00</span></li>
      <li><span class="cs-item">Strawberry Matcha Latte</span><span class="cs-dots"></span><span class="cs-price">$5.90</span></li>
    </ul>

    <p class="cs-note">Other Creamie Sippies outlets, like their <a href="/2026/01/25/creamie-sippies-jewel-changi-airport.html">Jewel Changi Airport flagship</a>, serve the full extended drink and pie menu. This Bugis location has a curated mini matcha bar.</p>
  </section>

  <!-- Store information -->
  <section class="cs-info">
    <h2>Store information</h2>
    <dl>
      <dt>Address</dt>
      <dd>261 Victoria Street, #02-115, Bugis Street Level 2</dd>
      <dt>Hours</dt>
      <dd>Daily, 12:00 PM – 8:00 PM<br>Last order 7:30 PM</dd>
      <dt>Format</dt>
      <dd>Takeaway corner stall, no dine-in seats</dd>
      <dt>Opened</dt>
      <dd>25 September 2026</dd>
    </dl>
    <a class="cs-map" href="https://www.google.com/maps/search/?api=1&query=Bugis+Street+261+Victoria+Street+Singapore+188067" target="_blank" rel="noopener">Open in Google Maps</a>
  </section>

</div>
