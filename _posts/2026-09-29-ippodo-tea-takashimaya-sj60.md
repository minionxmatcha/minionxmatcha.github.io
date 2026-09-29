---
layout: post
title: "Ippodo Tea Takashimaya SJ60: Full Matcha Price List, Teaware & Booth Guide"
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
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Event",
      "name": "Takashimaya SJ60 Japan Fair - Ippodo Tea Pop-Up",
      "description": "Ippodo Tea Kyoto returns to Singapore for Takashimaya's SJ60 Japan Fair at B2 Takashimaya Square.",
      "startDate": "2026-09-29",
      "endDate": "2026-10-11",
      "eventAttendanceMode": "https://schema.org/OfflineEventAttendanceMode",
      "eventStatus": "https://schema.org/EventScheduled",
      "location": {
        "@type": "Place",
        "name": "Takashimaya Square, Basement 2, Ngee Ann City",
        "address": {
          "@type": "PostalAddress",
          "streetAddress": "391 Orchard Road, Basement 2",
          "addressLocality": "Singapore",
          "postalCode": "238873",
          "addressCountry": "SG"
        }
      }
    },
    {
      "@type": "VideoObject",
      "name": "Ippodo Tea Takashimaya SJ60 Japan Fair Guide",
      "description": "Full price list breakdown of Ippodo Tea Kyoto boxed matcha, value bags, limited teaware, and matcha booths at Takashimaya B2.",
      "thumbnailUrl": [
        "https://img.youtube.com/vi/E1BdAVABwr8/hqdefault.jpg"
      ],
      "uploadDate": "2026-09-29",
      "contentUrl": "https://www.youtube.com/shorts/E1BdAVABwr8",
      "embedUrl": "https://www.youtube.com/embed/E1BdAVABwr8"
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
      <h1 class="cs-title">Ippodo Tea at Takashimaya SJ60: Complete Price List & Guide</h1>
      <p class="cs-where">Takashimaya Square B2 · 29 Sep – 11 Oct 2026 · 10am – 9:30pm daily</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-matcha" href="#ippodo" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">🍵</span>
        <strong>Ippodo Tea Kyoto</strong>
        <span class="cs-from">Matcha tins from $15</span>
      </a>
      <a class="cs-counter cs-counter-banana" href="#other-booths" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🏮</span>
        <strong>Other matcha booths</strong>
        <span class="cs-from">matcha an & TOP QUALI-TEA KYOTO</span>
      </a>
    </div>
  </header>

  <p>Kyoto's historic tea purveyor <strong>Ippodo Tea (一保堂茶舗)</strong> has returned to Singapore for the <strong>Takashimaya SJ60 Japan Event</strong> at Takashimaya Square, Basement 2.</p>
  <p>Running from <strong>29 September to 11 October 2026</strong>, the pop-up features rare Kyoto-exclusive tins, bulk value bags, teaware in very limited quantities, and one-cup teabag packs alongside other Japanese matcha specialty booths.</p>

  <!-- Video -->
  <section class="cs-video">
    <h2>Watch the video walkthrough</h2>

    <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/reel/Dd3ZK6VOx3q/" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:20px; box-shadow:0 0 0 2px #2A2616; margin: 0 auto; max-width: 360px; min-width: 280px; padding: 0; width: 100%;"></blockquote>
    <script async src="//www.instagram.com/embed.js"></script>

    <a class="cs-btn" href="https://www.instagram.com/reel/Dd3ZK6VOx3q/" target="_blank" rel="noopener">Follow & watch on Instagram</a>

    <!-- YouTube Shorts embed (preserves the Google video search badge) -->
    <p class="cs-alt">Prefer YouTube? Watch the Short here:</p>
    <div class="cs-yt-frame">
      <iframe
        src="https://www.youtube.com/embed/E1BdAVABwr8"
        title="Ippodo Tea Takashimaya SJ60 Video Guide"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>

    <p class="cs-more">
      <a href="https://vt.tiktok.com/ZSbkCpcUC/" target="_blank" rel="noopener">Watch on TikTok</a>
      &nbsp;or&nbsp;
      <a href="https://www.facebook.com/share/r/1DXAjfJ1FR/" target="_blank" rel="noopener">watch on Facebook</a>
    </p>
  </section>

  <!-- Ippodo matcha -->
  <section class="cs-board cs-board-matcha" id="ippodo">
    <h2>🍵 Ippodo Tea: matcha price list</h2>

    <h3 class="cs-sub">Boxed matcha (20g tins & boxes)</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Wakaki-shiro <small class="cs-jp">若き白</small></span><span class="cs-dots"></span><span class="cs-price">$15</span></li>
      <li><span class="cs-item">Ikuyo-no-mukashi <small class="cs-jp">幾世の昔</small></span><span class="cs-dots"></span><span class="cs-price">$25</span></li>
      <li><span class="cs-item">Sayaka-no-mukashi <small class="cs-jp">明昔</small></span><span class="cs-dots"></span><span class="cs-price">$45</span></li>
      <li><span class="cs-item">Kyogoku-no-mukashi <small class="cs-jp">京極の昔</small> <span class="cs-tag">Rare Kyoto main store exclusive</span></span><span class="cs-dots"></span><span class="cs-price">$60</span></li>
      <li><span class="cs-item">Ummon-no-mukashi <small class="cs-jp">雲門の昔</small> <span class="cs-tag">Highest ceremonial grade</span></span><span class="cs-dots"></span><span class="cs-price">$70</span></li>
      <li><span class="cs-item">Kuon <small class="cs-jp">久遠</small></span><span class="cs-dots"></span><span class="cs-price">$130</span></li>
    </ul>

    <h3 class="cs-sub">Value bags (100g)</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Ikuyo-no-mukashi <small class="cs-jp">幾世の昔</small></span><span class="cs-dots"></span><span class="cs-price">$100</span></li>
      <li><span class="cs-item">Sayaka-no-mukashi <small class="cs-jp">明昔</small></span><span class="cs-dots"></span><span class="cs-price">$190</span></li>
      <li><span class="cs-item">Hojicha powder</span><span class="cs-dots"></span><span class="cs-price">$50</span></li>
    </ul>
  </section>

  <!-- Ippodo teaware & teabags -->
  <section class="cs-board cs-board-banana">
    <h2>🫖 Ippodo Tea: teaware & teabags</h2>

    <h3 class="cs-sub">Utensils & teaware</h3>
    <span class="cs-limited">Extremely limited</span>
    <ul class="cs-prices">
      <li><span class="cs-item">Ippodo Travel Flask <small class="cs-jp">(pink / small)</small></span><span class="cs-dots"></span><span class="cs-price">$48</span></li>
      <li><span class="cs-item">Ippodo Travel Bottle <small class="cs-jp">(large, flip/straw lid)</small></span><span class="cs-dots"></span><span class="cs-price">$78</span></li>
      <li><span class="cs-item">Glass Teapot <span class="cs-tag">Only 2 pieces</span></span><span class="cs-dots"></span><span class="cs-price">$55</span></li>
    </ul>

    <h3 class="cs-sub">One-cup teabags (12 bags per box)</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Hojicha <small class="cs-jp">ほうじ茶</small></span><span class="cs-dots"></span><span class="cs-price">$15</span></li>
      <li><span class="cs-item">Sencha <small class="cs-jp">煎茶</small></span><span class="cs-dots"></span><span class="cs-price">$15</span></li>
      <li><span class="cs-item">Gyokuro <small class="cs-jp">玉露</small></span><span class="cs-dots"></span><span class="cs-price">$22</span></li>
      <li><span class="cs-item">Assorted set <small class="cs-jp">(mix of all 3)</small></span><span class="cs-dots"></span><span class="cs-price">$20</span></li>
    </ul>

    <h3 class="cs-sub">One-pot teabags</h3>
    <ul class="cs-prices">
      <li><span class="cs-item">Mugicha <small class="cs-jp">(barley tea)</small></span><span class="cs-dots"></span><span class="cs-price">$15</span></li>
      <li><span class="cs-item">Kuki Hojicha <small class="cs-jp">(stem roasted tea)</small></span><span class="cs-dots"></span><span class="cs-price">$22</span></li>
      <li><span class="cs-item">Genmaicha <small class="cs-jp">(brown rice green tea)</small></span><span class="cs-dots"></span><span class="cs-price">$22</span></li>
      <li><span class="cs-item">Gyokuro <small class="cs-jp">(shaded green tea)</small></span><span class="cs-dots"></span><span class="cs-price">$33</span></li>
    </ul>
  </section>

  <!-- Other booths -->
  <section class="cs-board cs-board-matcha" id="other-booths">
    <h2>🏮 Other matcha booths at SJ60</h2>
    <ul class="cs-items">
      <li>
        <div class="cs-items-head"><h3>matcha an <small class="cs-jp">まっちゃあん</small></h3></div>
        <p class="cs-mini-head">Matcha tins</p>
        <ul class="cs-prices">
          <li><span class="cs-item">Ise Matcha <small class="cs-jp">伊勢抹茶 · 20g</small></span><span class="cs-dots"></span><span class="cs-price">$25</span></li>
          <li><span class="cs-item">Uji Matcha <small class="cs-jp">宇治抹茶 · 30g</small></span></li>
        </ul>
        <p class="cs-mini-head">Freshly prepared drinks</p>
        <ul class="cs-prices">
          <li><span class="cs-item">Uji Matcha Latte</span><span class="cs-dots"></span><span class="cs-price">$10</span></li>
          <li><span class="cs-item">Uji Matcha Sparkling</span><span class="cs-dots"></span><span class="cs-price">$10</span></li>
          <li><span class="cs-item">Rooibos Tea</span><span class="cs-dots"></span><span class="cs-price">$8</span></li>
        </ul>
        <p>Thick-cut bakery items, including their signature oversized Matcha Pistachio cookies.</p>
      </li>
      <li>
        <div class="cs-items-head"><h3>TOP QUALI-TEA KYOTO</h3><span class="cs-tag">Kyoga</span></div>

        <p class="cs-mini-head">Matcha & hojicha</p>
        <ul class="cs-prices">
          <li><span class="cs-item">Hojicha <small class="cs-jp">30g</small></span><span class="cs-dots"></span><span class="cs-price">$22.90</span></li>
          <li><span class="cs-item">Suiko Matcha <small class="cs-jp">30g</small></span><span class="cs-dots"></span><span class="cs-price">$29.90</span></li>
          <li><span class="cs-item">Kyoga Matcha <small class="cs-jp">30g</small></span><span class="cs-dots"></span><span class="cs-price">$56.90</span></li>
          <li><span class="cs-item">The Signature Set <small class="cs-jp">(all 3 above)</small></span><span class="cs-dots"></span><span class="cs-price">$99.90</span></li>
          <li><span class="cs-item">Suiko Matcha <small class="cs-jp">100g</small></span><span class="cs-dots"></span><span class="cs-price">$79.90</span></li>
        </ul>

        <p class="cs-mini-head">Sweets & bakes</p>
        <ul class="cs-prices">
          <li><span class="cs-item">Hojicha / Matcha Tiramisu <small class="cs-jp">(non-alcoholic)</small></span><span class="cs-dots"></span><span class="cs-price">$9.90</span></li>
          <li><span class="cs-item">Kyoto Yuzu Jelly</span><span class="cs-dots"></span><span class="cs-price">$5.90</span></li>
          <li><span class="cs-item">Hojicha / Matcha / Butter Choco Chip Cookie</span><span class="cs-dots"></span><span class="cs-price">$3.90</span></li>
        </ul>

        <div class="cs-promo">
          <div class="cs-promo-head">
            <span class="cs-promo-badge">🍁 Autumn special offer</span>
            <span class="cs-promo-sub">Free gift worth up to $29.90</span>
          </div>
          <ol class="cs-tiers">
            <li><span class="cs-spend">Spend $25+</span><span class="cs-gift">Free Kyoto Yuzu Jelly <small>(worth $5.90)</small></span></li>
            <li><span class="cs-spend">Spend $40+</span><span class="cs-gift">Free Tiramisu <small>(worth $9.90)</small></span></li>
            <li><span class="cs-spend">Spend $80+</span><span class="cs-gift">Choose one: free Suiko Matcha <small>(worth $29.90)</small> or Hojicha powder <small>(worth $22.90)</small></span></li>
          </ol>
        </div>
      </li>
    </ul>
  </section>

  <!-- Event details -->
  <section class="cs-info">
    <h2>Event details</h2>
    <dl>
      <dt>Event</dt>
      <dd>SJ60 Japan Fair, celebrating 60 years of Singapore-Japan diplomatic relations</dd>
      <dt>Dates</dt>
      <dd>29 September – 11 October 2026</dd>
      <dt>Location</dt>
      <dd>Takashimaya Square, Basement 2 (B2)<br>Ngee Ann City, Orchard Road</dd>
      <dt>Hours</dt>
      <dd>10:00 AM – 9:30 PM daily</dd>
    </dl>
    <a class="cs-map" href="https://www.google.com/maps/search/?api=1&query=Takashimaya+Square+Ngee+Ann+City+391+Orchard+Road+Singapore+238873" target="_blank" rel="noopener">Open in Google Maps</a>
  </section>

</div>
