---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title: We are the Class of...
---

{% for institution in site.institutions %}
<a href="/institutions/{{ institution.institution }}">{{ institution.name }}</a><br/>
{% endfor %}
