---
layout: base
title: Design
---
{% for page in site.pages %}
  {% if page.layout == 'design' %}
  {% include design_preview.html %}
  {% endif %}
{% endfor %}
