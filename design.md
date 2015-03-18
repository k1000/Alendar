---
layout: base
sitemap:
  priority: 0.7
  changefreq: weekly
  lastmod: 2011-09-29T18:56:19+02:00
---
{% for page in site.pages %}
  <h1><a href="{{ page.url }}">{{page.title}}</a></h1>
{% endfor %}
