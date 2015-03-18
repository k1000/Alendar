---
layout: base
title: Design
---
{% for page in site.pages %}
  {% if page.layout == "design" %}
  {% includes "design_preview.html" %}
  {% endif %}
{% endfor %}
