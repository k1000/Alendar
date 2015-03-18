---
layout: base
title: Design
---
{% for page in site.pages %}
  {% if page.layout == 'design' %}
  <h2><a href="{{ page.url }}">{{ page.title }}</a></h2>
  {% endif %}
{% endfor %}

