---
layout: default
---

<h1>{{ page.name }}</h1>

{% for year in site.years %}
  {% if year.institution == page.institution %}
    <a href="/years/{{ page.institution }}-{{ year.year }}">Class of {{ year.year }}</a>
  {% endif %}
{% endfor %}
