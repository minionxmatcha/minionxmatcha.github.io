---
layout: post
title: "How to Restring a Chasen & Secure a Charm (Zero Knot Method)"
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

  /* How-to additions */
  .cs-board h3.cs-sub:first-of-type { margin-top: 4px; }
  .cs-chips.cs-tools li { background: #fff; }
  .cs-chips .cs-hint { color: #6b6550; font-size: 13px; }
  .cs-frame-wrap { margin: 22px 0 6px; text-align: center; }
  .cs-frame-wrap .cs-yt-frame { margin-top: 0; background: #fff; }
  .cs-watch { display: flex; flex-wrap: wrap; justify-content: center; gap: 8px; margin: 14px 0 4px; }
  .cs .cs-watch a {
    padding: 8px 16px; border-radius: 999px; font-size: 13px; font-weight: 700;
    color: #fff; text-decoration: none; border: 2px solid var(--ink);
  }
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
  .cs-intro-callout { margin: 0 0 28px; padding: 14px 16px; border-radius: 16px; background: var(--foam); font-size: 15px; border: 1.5px dashed var(--matcha); }
  @media (max-width: 520px) {
    .cs-steps > li { padding: 58px 16px 16px; }
    .cs-steps > li::before { top: 12px; }
  }
</style>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "HowTo",
      "name": "How to Restring a Bamboo Matcha Whisk (Chasen) and Attach a Charm",
      "description": "Step-by-step guide to replacing broken chasen thread using embroidery floss and securing a charm using a zero-knot method.",
      "totalTime": "PT15M",
      "supply": [
        { "@type": "HowToSupply", "name": "Embroidery floss (2 strands)" },
        { "@type": "HowToSupply", "name": "Paper sleeve (folded to separate inner tines)" },
        { "@type": "HowToSupply", "name": "Mini charm with jump ring or loop" }
      ],
      "tool": [
        { "@type": "HowToTool", "name": "Utility knife" },
        { "@type": "HowToTool", "name": "Tweezers" },
        { "@type": "HowToTool", "name": "Scissors" }
      ],
      "step": [
        {
          "@type": "HowToStep",
          "name": "Remove Old Thread",
          "text": "Make one careful cut with a utility knife and use tweezers to pull and trim the old thread as you go."
        },
        {
          "@type": "HowToStep",
          "name": "Prepare Floss and Inner Sleeve",
          "text": "Cut the floss to 3 to 4 times the height of your chasen. Separate to use 2 strands. Fold a paper strip into a sleeve to protect and hold the inner core prongs apart."
        },
        {
          "@type": "HowToStep",
          "name": "Weave the Prongs",
          "text": "Loop thread around one prong. Bring the left thread behind the next prong while keeping the right thread taut, alternating prongs around the chasen."
        },
        {
          "@type": "HowToStep",
          "name": "Add Second and Third Rows",
          "text": "Repeat the weave for 2 to 4 rows, keeping each row tight and parallel to the bamboo node."
        },
        {
          "@type": "HowToStep",
          "name": "Secure the Charm (Zero-Knot Technique)",
          "text": "Leave the last prong of each row untouched. Separate dangling threads, pass the left thread through the charm loop ensuring it faces upright, and finish the weave without tying bulky knots."
        }
      ]
    },
    {
      "@type": "VideoObject",
      "name": "Part 1: How to Restring a Chasen",
      "description": "Restringing a Japanese matcha bamboo whisk using embroidery floss and a paper sleeve.",
      "thumbnailUrl": ["https://img.youtube.com/vi/FnJOI3kf1P8/hqdefault.jpg"],
      "uploadDate": "2026-04-11",
      "contentUrl": "https://www.youtube.com/shorts/FnJOI3kf1P8",
      "embedUrl": "https://www.youtube.com/embed/FnJOI3kf1P8"
    },
    {
      "@type": "VideoObject",
      "name": "Part 2: How to Secure a Charm (Zero-Knot Technique)",
      "description": "How to attach a charm to a chasen using a seamless zero-knot technique.",
      "thumbnailUrl": ["https://img.youtube.com/vi/srS_BKo8Ep0/hqdefault.jpg"],
      "uploadDate": "2026-05-30",
      "contentUrl": "https://www.youtube.com/shorts/srS_BKo8Ep0",
      "embedUrl": "https://www.youtube.com/embed/srS_BKo8Ep0"
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

  <!-- Hero: the two parts of the guide -->
  <header class="cs-hero">
    <div class="cs-hero-top">
      <h1 class="cs-title">How to Restring a Chasen & Secure a Charm</h1>
      <p class="cs-where">Two-part DIY guide · About 15 minutes · No knots needed</p>
    </div>
    <div class="cs-counters">
      <a class="cs-counter cs-counter-matcha" href="#part-1" style="text-decoration:none;color:#fff;">
        <span class="cs-counter-emoji" aria-hidden="true">🧵</span>
        <strong>Part 1: Restring the chasen</strong>
        <span class="cs-from">Embroidery floss & a paper sleeve</span>
      </a>
      <a class="cs-counter cs-counter-banana" href="#part-2" style="text-decoration:none;color:var(--ink);">
        <span class="cs-counter-emoji" aria-hidden="true">🔗</span>
        <strong>Part 2: Secure a charm</strong>
        <span class="cs-from">Minion's zero-knot technique</span>
      </a>
    </div>
  </header>

  <p>When the black binding thread on your bamboo matcha whisk (<em>chasen</em>) breaks or unravels, you don't need to throw the whisk away. You can easily restring it at home using embroidery floss and customise it with a charm.</p>

  <p class="cs-intro-callout">Here is the complete two-part walkthrough, using felt paper to explain the mechanics clearly, followed by the <strong>zero-knot technique</strong> to secure a charm.</p>

  <!-- Part 1 -->
  <section class="cs-board cs-board-matcha" id="part-1">
    <h2>🧵 Part 1: How to Restring a Chasen</h2>

    <h3 class="cs-sub">Tools needed</h3>
    <ul class="cs-chips cs-tools">
      <li>New or loose chasen</li>
      <li>Tweezers</li>
      <li>Utility knife & scissors</li>
      <li>Embroidery floss <span class="cs-hint">(about 3–4× your chasen's height)</span></li>
      <li>Small paper strip <span class="cs-hint">(folded into a sleeve)</span></li>
    </ul>

    <div class="cs-frame-wrap">
      <div class="cs-yt-frame">
        <iframe
          src="https://www.youtube.com/embed/FnJOI3kf1P8"
          title="Part 1: How to Restring a Chasen"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen>
        </iframe>
      </div>
      <div class="cs-watch" aria-label="Watch Part 1 on">
        <a class="cs-ig" href="https://www.instagram.com/reel/DW_FCR2E_cu/" target="_blank" rel="noopener">Watch on Instagram</a>
        <a class="cs-tt" href="https://www.tiktok.com/@minionxmatcha/video/7627423918927744277" target="_blank" rel="noopener">Watch on TikTok</a>
        <a class="cs-yt" href="https://youtube.com/shorts/FnJOI3kf1P8" target="_blank" rel="noopener">Watch on YouTube</a>
      </div>
    </div>

    <h3 class="cs-sub">Step-by-step restringing</h3>
    <ol class="cs-steps">
      <li>
        <h4>Remove the old binding</h4>
        <p>Make one careful cut through the old thread using a utility knife. Use tweezers to pull and trim remaining bits cleanly without scoring the bamboo.</p>
      </li>
      <li>
        <h4>Prepare the floss</h4>
        <p>Standard embroidery floss has 6 strands, which is too thick. Separate it and use <strong>2 strands</strong>.</p>
      </li>
      <li>
        <h4>Insert the paper sleeve</h4>
        <p>Fold a small piece of paper into a collar or sleeve and slide it down the centre. This holds the inner prongs safely back and separates them from the outer tines.</p>
      </li>
      <li>
        <h4>Weave the pattern</h4>
        <ul>
          <li>Loop the thread around the first outer prong.</li>
          <li>Bring the left thread behind the next prong while keeping the right thread pinned in place.</li>
          <li>Repeat this alternating movement around the circumference.</li>
        </ul>
      </li>
      <li>
        <h4>Adjust the tension</h4>
        <p>Use tweezers to slide the thread row down so it sits straight and parallel to the bamboo node.</p>
      </li>
      <li>
        <h4>Repeat the rows</h4>
        <p>Repeat the loop for a second, third, or fourth row depending on your preference.</p>
      </li>
    </ol>
  </section>

  <!-- Part 2 -->
  <section class="cs-board cs-board-banana" id="part-2">
    <h2>🔗 Part 2: Secure a Charm (Minion's Zero-Knot Technique)</h2>
    <p class="cs-lede">Adding a metal charm or pendant normally leaves a bulky knot that unravels during whisking. This zero-knot method locks the charm into the weave seamlessly.</p>

    <div class="cs-frame-wrap">
      <div class="cs-yt-frame">
        <iframe
          src="https://www.youtube.com/embed/srS_BKo8Ep0"
          title="Part 2: How to Secure a Charm to a Chasen"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen>
        </iframe>
      </div>
      <div class="cs-watch" aria-label="Watch Part 2 on">
        <a class="cs-ig" href="https://www.instagram.com/reel/DY8q7jdTWrZ/" target="_blank" rel="noopener">Watch on Instagram</a>
        <a class="cs-tt" href="https://www.tiktok.com/@minionxmatcha/video/7645523408406580501" target="_blank" rel="noopener">Watch on TikTok</a>
        <a class="cs-yt" href="https://youtube.com/shorts/srS_BKo8Ep0" target="_blank" rel="noopener">Watch on YouTube</a>
      </div>
    </div>

    <h3 class="cs-sub">Key technique tips</h3>
    <ul class="cs-items">
      <li>
        <div class="cs-items-head"><h3>Choose the right charm</h3></div>
        <p>Look for bracelet charms or jewellery pendants that have an open jump ring or top loop.</p>
      </li>
      <li>
        <div class="cs-items-head"><h3>Keep the last prong untouched</h3></div>
        <p>Leave the final prong of each row naked.</p>
      </li>
      <li>
        <div class="cs-items-head"><h3>Thread the loop</h3></div>
        <p>Separate the two dangling threads and pass all of the left thread through the charm loop.</p>
      </li>
      <li>
        <div class="cs-items-head"><h3>Check the orientation</h3></div>
        <p>Make sure the charm is right-side up before pulling the thread taut.</p>
      </li>
      <li>
        <div class="cs-items-head"><h3>Lock it in</h3></div>
        <p>Continue repeating the weave steps from <a href="#part-1">Part 1</a> (bottom row first, then working upward). The tension of the woven rows locks the charm ring flush against the bamboo without tying any knots.</p>
      </li>
      <li>
        <div class="cs-items-head"><h3>Trim the thread</h3></div>
        <p>Trim the finished ends slightly longer than the bamboo node to allow natural movement without slipping.</p>
      </li>
    </ul>
  </section>

</div>
