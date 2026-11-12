---
layout: default
title: "minionxmatcha — Matcha Reviews, Cafe Guides & Tea Directory"
---

<!-- TOP BRAND & SOCIAL PROFILE BANNER -->
<div style="background: #ffffff; border: 1px solid #eaeaea; border-radius: 14px; padding: 18px 20px; margin: 10px auto 25px auto; max-width: 580px; box-shadow: 0 4px 14px rgba(0,0,0,0.04); text-align: center; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;">
  <div style="font-size: 20px; font-weight: 700; color: #1a1a1a; letter-spacing: -0.3px; margin-bottom: 4px;">
    🍵 minionxmatcha
  </div>
  <p style="margin: 0 0 14px 0; font-size: 13px; color: #666; line-height: 1.4;">
    Matcha reviews, cafe walkthroughs & tea guides in Singapore.
  </p>
  <div style="display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; align-items: center;">
    <a href="https://www.instagram.com/minionxmatcha" target="_blank" rel="noopener" style="display: inline-flex; align-items: center; padding: 7px 14px; background: #E1306C; color: #ffffff; font-size: 12px; font-weight: 600; text-decoration: none; border-radius: 20px; box-shadow: 0 2px 6px rgba(225,48,108,0.25);">
      Instagram
    </a>
    <a href="https://www.tiktok.com/@minionxmatcha" target="_blank" rel="noopener" style="display: inline-flex; align-items: center; padding: 7px 14px; background: #000000; color: #ffffff; font-size: 12px; font-weight: 600; text-decoration: none; border-radius: 20px; box-shadow: 0 2px 6px rgba(0,0,0,0.2);">
      TikTok
    </a>
    <a href="https://www.facebook.com/p/Minionxmatcha-61592062657121/" target="_blank" rel="noopener" style="display: inline-flex; align-items: center; padding: 7px 14px; background: #1877F2; color: #ffffff; font-size: 12px; font-weight: 600; text-decoration: none; border-radius: 20px; box-shadow: 0 2px 6px rgba(24,119,242,0.25);">
      Facebook
    </a>
    <a href="https://www.youtube.com/@minionxmatcha" target="_blank" rel="noopener" style="display: inline-flex; align-items: center; padding: 7px 14px; background: #FF0000; color: #ffffff; font-size: 12px; font-weight: 600; text-decoration: none; border-radius: 20px; box-shadow: 0 2px 6px rgba(255,0,0,0.2);">
      YouTube
    </a>
  </div>
</div>

# All Reviews & Guides

<ul style="list-style: none; padding: 0; max-width: 680px; margin: 20px auto; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;">
  {% for post in site.posts %}
    <li style="margin-bottom: 14px; padding: 14px 18px; background: #ffffff; border: 1px solid #eaeaea; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.02);">
      <span style="display: block; font-size: 12px; color: #888; margin-bottom: 4px;">
        {{ post.date | date: "%d %b %Y" }}
      </span>
      <a href="{{ post.url | relative_url }}" style="font-size: 16px; font-weight: 600; color: #1a1a1a; text-decoration: none;">
        {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>
