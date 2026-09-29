---
layout: post
title: "VE/LA Changi Airport Terminal 1: Bangkok Matcha Cafe Review & Menu Guide"
date: 2026-09-29
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
  .cs-items li { margin: 0; background: #fff; border: 1.5px solid var(--ink); border-radius: 18px; padding: 16px 18px; }
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
  .cs-also { margin: 4px 0 0; font-size: 14px; }
  .cs-also .cs-chips { margin-top: 6px; }
  .cs-board .cs-note { margin-top: 18px; }
  .cs-prices .cs-price { white-space: nowrap; }
  .cs-prices .cs-item small { font-weight: 400; font-size: 13px; color: #6b6550; }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "CafeOrCoffeeShop",
      "name": "VE/LA Changi Airport Terminal 1",
      "description": "Bangkok's famous cafe VE/LA (pronounced Wela) at Changi Airport Terminal 1, serving single-cultivar Japanese matcha, craft lattes, and pastries 24 hours daily.",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "80 Airport Boulevard, #01-K22, Level 1 Arrival Hall West, Terminal 1",
        "addressLocality": "Singapore",
        "postalCode": "819642",
        "addressCountry": "SG"
      },
      "openingHours": "Mo-Su 00:00-24:00",
      "hasMenu": {
        "@type": "Menu",
        "name": "VE/LA Singapore Menu"
      }
    },
    {
      "@type": "VideoObject",
      "name": "VE/LA Changi Airport Terminal 1 Review",
      "description": "Full guide to VE/LA Bangkok's 24-hour cafe at Changi Airport Terminal 1, featuring Sundown vs Sunrise matcha, Ube Vanilla Matcha, and pastries.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/-6Q7zUi7_ts/hqdefault.jpg"
      ],
      "uploadDate": "2026-09-28",
      "contentUrl": "https://www.youtube.com/shorts/-6Q7zUi7_ts",
      "embedUrl": "https://www.youtube.com/embed/-6Q7zUi7_ts"
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

  <!-- Hero: the two matcha grades -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">VE/LA Changi Airport Terminal 1: Full Review & Menu</h1>
      <p class="cs-where">Terminal 1, Arrival Hall West, #01-K22 · Open 24 hours daily</p>
    </div>
    <div class="cs-counters">
      <div class="cs-counter cs-counter-matcha">
        <span class="cs-counter-emoji" aria-hidden="true">🌇</span>
        <strong>Sundown Matcha</strong>
        <span class="cs-from">Specialty grade</span>
      </div>
      <div class="cs-counter cs-counter-banana">
        <span class="cs-counter-emoji" aria-hidden="true">🌅</span>
        <strong>Sunrise Matcha</strong>
        <span class="cs-from">Epicurean grade</span>
      </div>
    </div>
  </header>

  <p>Bangkok's renowned specialty cafe <strong>VE/LA</strong> (pronounced <strong>"Wela" / เวลา</strong>) has officially opened its doors in Singapore at Changi Airport Terminal 1 (#01-K22, Arrival Hall West). Operating <strong>24 hours daily</strong>, it offers a late-night or early-morning matcha stop for travellers and night owls.</p>
  <p>Here is the complete breakdown of their matcha cultivar grades, signature drinks, customisations, and pastries.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video preview</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/Dd1BzqWOCGe/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/Dd1BzqWOCGe/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/-6Q7zUi7_ts"
        title="VE/LA Changi Airport Terminal 1 Review"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://www.tiktok.com/@minionxmatcha/video/7690473646447529237" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/p/Minionxmatcha-61592062657121/" target="_blank" rel="noopener">visit on Facebook</a>
    </p>
  </section>

  <!-- The matcha -->
  <section class="cs-board cs-board-matcha">
    <h2>🍵 The matcha: cultivars & grades</h2>
    <p class="cs-lede">Both matcha tiers feature single-cultivar <strong>Yabukita</strong> sourced directly from <strong>Mie Prefecture, Japan</strong>.</p>

    <ul class="cs-items">
      <li>
        <div class="cs-items-head"><h3>Sundown Matcha</h3><span class="cs-tag">Specialty grade</span></div>
        <p>$25 for a 30g tin</p>
        <ul class="cs-chips" aria-label="Tasting notes">
          <li>Roasted chestnut</li><li>Leafy greens</li><li>Wheat</li>
        </ul>
      </li>
      <li>
        <div class="cs-items-head"><h3>Sunrise Matcha</h3><span class="cs-tag">Epicurean grade</span></div>
        <p>$36 for a 30g tin, or +$1 to upgrade any drink</p>
        <ul class="cs-chips" aria-label="Tasting notes">
          <li>Seaweed umami</li><li>Honey sweetness</li><li>Light florals</li>
        </ul>
      </li>
    </ul>
  </section>

  <!-- Drinks -->
  <section class="cs-board cs-board-banana">
    <h2>🥤 Drink menu & pricing</h2>

    <h3 class="cs-sub">Classics</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Matcha Latte</span><span class="cs-dots"></span><span class="cs-price">$9.00</span></li>
      <li><span class="cs-item">Clear Matcha</span><span class="cs-dots"></span><span class="cs-price">$8.50</span></li>
    </ul>

    <h3 class="cs-sub">Signatures & specials</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Ube Vanilla Matcha</span><span class="cs-dots"></span><span class="cs-price">$9.50</span></li>
    </ul>
    <div class="cs-special">
      <div class="cs-special-head"><h4>Autumn in Bangkok</h4><span class="cs-tag">Seasonal off-menu</span></div>
      <p>In collaboration with Kaew Boutique. Maple and roasted chestnut infused Sundown matcha cream layered over sweet coconut water with young coconut chunks, topped with crispy thongmuan feuilletine and pandan dust.</p>
    </div>

    <h3 class="cs-sub">Customisation options</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Alternative milks <small>(oat, soy, almond)</small></span><span class="cs-dots"></span><span class="cs-price">+$1.00</span></li>
      <li><span class="cs-item">Syrups & flavours</span><span class="cs-dots"></span><span class="cs-price">+$0.50</span></li>
      <li><span class="cs-item">Espresso shot</span><span class="cs-dots"></span><span class="cs-price">+$1 / +$1.50</span></li>
      <li><span class="cs-item">Extra matcha shot</span><span class="cs-dots"></span><span class="cs-price">+$1 / +$1.50</span></li>
      <li><span class="cs-item">Toppings & cold foam</span><span class="cs-dots"></span><span class="cs-price">+$1.00</span></li>
    </ul>

    <p class="cs-note">💬 Check your takeaway cup lid before you sip. Every lid features a cheeky quote!</p>
  </section>

  <!-- Pastries & merch -->
  <section class="cs-board cs-board-matcha">
    <h2>🥐 Pastries & merchandise</h2>

    <h3 class="cs-sub">Pastries</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Matcha Ganache Cruffin</span><span class="cs-dots"></span><span class="cs-price">$6.80</span></li>
    </ul>
    <div class="cs-also">
      Also on the counter:
      <ul class="cs-chips"><li>Chocolate Hazelnut Cruffin</li><li>Artisanal Croissants</li></ul>
    </div>

    <h3 class="cs-sub">Merchandise</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">VE/LA Signature Matcha Chawan (Bowl)</span><span class="cs-dots"></span><span class="cs-price">$26.00</span></li>
    </ul>
    <div class="cs-also">
      Also available:
      <ul class="cs-chips"><li>Classic Bamboo Matcha Whisk (Chasen)</li></ul>
    </div>
  </section>

  <!-- Outlet details -->
  <section class="cs-info">
    <h2>Outlet details</h2>
    <dl>
      <dt>Location</dt>
      <dd>80 Airport Boulevard, #01-K22<br>Level 1 Arrival Hall West, Terminal 1, Changi Airport</dd>
      <dt>Hours</dt>
      <dd>Open 24 hours daily, Monday to Sunday</dd>
      <dt>Getting there</dt>
      <dd>Changi Airport MRT, connected to Jewel & T1 via Skytrain / Mezzanine walkway</dd>
    </dl>
    <a class="cs-map" href="https://www.google.com/maps/search/?api=1&query=VE%2FLA+Changi+Airport+Terminal+1+80+Airport+Boulevard+Singapore+819642" target="_blank" rel="noopener">Open in Google Maps</a>
  </section>

</div>
