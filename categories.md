---
layout: page
title: Categories
permalink: /categories/
---

{% assign cats = site.categories | sort %}
{% for category in cats %}
### {{ category[0] }} ({{ category[1].size }})
- [카테고리 보기](/categories/{{ category[0] | slugify }}/)
{% endfor %}
