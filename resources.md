---
layout: page
title: Resources
---
A selection of resources created by VTF organizers and fellows.

{% for resource in site.resources %}
## [{{ resource.title }}]({{ resource.resource_url }})
{{ resource.content | markdownify }}
{% endfor %}

