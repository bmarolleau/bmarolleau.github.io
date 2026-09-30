---
layout: page
title: "Data & Streaming"
subtitle: "Event streaming, CDC, data fabric, watsonx.data — real-time data pipelines from IBM i to the cloud and beyond."
permalink: /topics/data/
category: data-streaming
---

{% assign cat_posts = site.categories['data-streaming'] | sort: 'date' | reverse %}

{% for post in cat_posts %}
<article style="margin-bottom:2rem;padding-bottom:2rem;border-bottom:1px solid #eee;">
  <p style="font-size:.8rem;color:#888;margin-bottom:.3rem;">{{ post.date | date: "%B %-d, %Y" }}</p>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 35 }}</p>
  {% if post.repo %}<p><a href="{{ post.repo }}" target="_blank" rel="noopener" style="font-family:monospace;font-size:.8rem;">⌥ {{ post.repo | remove: "https://github.com/" }}</a></p>{% endif %}
</article>
{% endfor %}
