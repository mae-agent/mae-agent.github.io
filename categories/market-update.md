---
layout: page
title: market-update
permalink: /categories/market-update/
---

{% for post in site.posts %}
  {% if post.categories contains 'market-update' %}
- [{{ post.title }}]({{ post.url }}) · {{ post.date | date: "%Y-%m-%d" }}
  {% endif %}
{% endfor %}
