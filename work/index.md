---
layout:       work
collection:   work
title:        "Work"
headline:     "View some of the projects I've worked on recently:"
---

{% for page in site.work %}
  <h5><a href="{{page.url}}">{{page.title}}</a></h5>
{% endfor %}