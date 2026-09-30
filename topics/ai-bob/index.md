---
layout: page
title: "IBM Bob"
subtitle: "Agentic AI coding assistant — enablement, On-Premises, and what it means for enterprise engineering."
permalink: /topics/ai-bob/
category: ai-bob
---

{% assign cat_posts = site.categories['ai-bob'] %}

{% for post in cat_posts %}
<article style="margin-bottom:2rem;padding-bottom:2rem;border-bottom:1px solid #eee;">
  <p style="font-size:.8rem;color:#888;margin-bottom:.3rem;">{{ post.date | date: "%B %-d, %Y" }}</p>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 35 }}</p>
  {% if post.repo %}<p><a href="{{ post.repo }}" target="_blank" rel="noopener" style="font-family:monospace;font-size:.8rem;">⌥ {{ post.repo | remove: "https://github.com/" }}</a></p>{% endif %}
</article>
{% endfor %}
