---
layout: base
sitemap:
  priority: 0.7
  changefreq: weekly
  lastmod: 2011-09-29T18:56:19+02:00
---
{% for post in site.posts %}
  {% include post_preview.html %}
{% endfor %}


{% for page in site.pages %}
  <h1>{{ page.title }}</h1>
{% endfor %}
