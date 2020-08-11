---
layout: page
title: Resources
---
A selection of resources created by VTF organizers and fellows. Coming soon!

{% for resource in site.resources %}
**{{ resource.title }}**
{{ resource.content | markdownify }}
{% endfor %}

