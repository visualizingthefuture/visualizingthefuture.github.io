---
layout: page
title: Projects
---

{% for project in site.projects %}
## [{{ project.title }}]({{ project.proposal_url }})
Fellow(s): **{{ project.fellows }}**
{{ project.content | markdownify }}
{% endfor %}
