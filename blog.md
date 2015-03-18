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


<hr>

{% for page in site.pages %}

  <url>
    <loc>{{ site.baseurl }}{{ page.url }}</loc>
    <lastmod>{{ page.sitemap.lastmod | date_to_xmlschema }}</lastmod>
    <changefreq>{{ page.sitemap.changefreq }}</changefreq>
    <priority>{{ page.sitemap.priority }}</priority>
  </url>
{% endfor %}
