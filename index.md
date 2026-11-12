---
layout: default
title: Minion x Matcha — All Guides & Reviews
---

# Welcome to Minion x Matcha

Explore all matcha reviews, cafe menus, and event guides in one place:

<ul>
  {% for post in site.posts %}
    <li>
      <span style="color: #666; font-size: 0.9em;">{{ post.date | date: "%d %b %Y" }}</span> — 
      <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a>
      {% if post.excerpt %}
        <p>{{ post.excerpt | strip_html | truncatewords: 25 }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>
