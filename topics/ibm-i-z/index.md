---
layout: page
title: "IBM i / Z — Legendary Platforms"
subtitle: "The most proven platforms in enterprise IT. RPG, COBOL, Db2 for i, z/OS — and how AI is making them evolvable again."
permalink: /topics/ibm-i-z/
category: ibm-i
category2: ibm-z
---

{% assign ibmi_posts = site.categories['ibm-i'] %}
{% assign ibmz_posts = site.categories['ibm-z'] %}
{% if ibmz_posts %}
  {% assign combined = ibmi_posts | concat: ibmz_posts | sort: 'date' | reverse %}
{% else %}
  {% assign combined = ibmi_posts | sort: 'date' | reverse %}
{% endif %}

{% for post in combined %}
<article style="margin-bottom:2rem;padding-bottom:2rem;border-bottom:1px solid #eee;">
  <p style="font-size:.8rem;color:#888;margin-bottom:.3rem;">
    {{ post.date | date: "%B %-d, %Y" }}
    {% for cat in post.categories %}
      &nbsp;<span style="background:#f0f0f0;padding:.1em .5em;border-radius:3px;font-size:.75rem;">{{ cat | replace: "-", " " | upcase }}</span>
    {% endfor %}
  </p>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 35 }}</p>
  {% if post.repo %}
  <p><a href="{{ post.repo }}" target="_blank" rel="noopener" style="font-family:monospace;font-size:.8rem;">⌥ {{ post.repo | remove: "https://github.com/" }}</a></p>
  {% endif %}
</article>
{% endfor %}
