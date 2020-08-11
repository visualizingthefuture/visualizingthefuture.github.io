---
layout: page
title: Resources
---

{% for resource in site.resources %}
**{{ resource.title }}**
{{ resource.content | markdownify }}
{% endfor %}

