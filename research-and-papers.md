---
title: Research and Papers
layout: page
---

{% for paper in site.papers %}
[{{ paper.title }}]({{ paper.url }})

_{{ paper.summary }}_
{% endfor %}
