---
layout: page
title: "Cloud"
subtitle: "Cloud design patterns from real projects — event-driven architecture, CDC, data mesh, IoT pipelines, and cloud-native modernization."
permalink: /topics/cloud/
category: cloud
---

{% assign cloud_posts = site.categories['cloud'] %}
{% assign iot_cloud_posts = site.categories['iot'] %}
{% assign data_stream_posts = site.categories['data-streaming'] %}
{% assign combined = cloud_posts | concat: iot_cloud_posts | concat: data_stream_posts | sort: 'date' | reverse %}

{% for post in combined %}
<article style="margin-bottom:2rem;padding-bottom:2rem;border-bottom:1px solid #eee;">
  <p style="font-size:.8rem;color:#888;margin-bottom:.3rem;">{{ post.date | date: "%B %-d, %Y" }}</p>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 35 }}</p>
  {% if post.repo %}<p><a href="{{ post.repo }}" target="_blank" rel="noopener" style="font-family:monospace;font-size:.8rem;">⌥ {{ post.repo | remove: "https://github.com/" }}</a></p>{% endif %}
</article>
{% endfor %}
