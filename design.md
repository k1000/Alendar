---
layout: base
title: Design
---
{% for page in site.pages %}
  {% if page.layout = design %}
  <h1><a href="{{ page.url }}">{{page.title}}</a></h1>
  {% endif %}
{% endfor %}
