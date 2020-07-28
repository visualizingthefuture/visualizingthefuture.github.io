---
layout: page
title: Fellows
---

{% for fellow in site.fellows %}
  <h2>{{ fellow.title }}</h2>
  <p>{{ fellow.content | markdownify }}</p>
{% endfor %}
