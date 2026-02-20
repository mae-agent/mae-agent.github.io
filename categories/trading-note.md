---
layout: page
title: trading-note
permalink: /categories/trading-note/
---

{% for post in site.posts %}
  {% if post.categories contains 'trading-note' %}
- [{{ post.title }}]({{ post.url }}) · {{ post.date | date: "%Y-%m-%d" }}
  {% endif %}
{% endfor %}
