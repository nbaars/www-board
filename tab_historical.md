---
title: Historical
layout:  null
tab: true
order: 1
tags: board
---

## Historical Meetings

{% assign pages = site.pages | sort: 'date' | reverse | limit: 1000 %}
<ul>
{% for page in pages %}
 {% if page.path contains 'historical/' %}
 <li><a href='/www-board{{ page.url }}'>{{ page.title }}</a></li>
 {% endif %}
{% endfor %}
</ul>

## Minutes
(New and historical ported from wiki.owasp.org)
{% assign pages = site.pages | sort: 'date' | reverse | limit: 1000 %}
<ul>
{% for page in pages %}
 {% if page.path contains 'minutes/' %}
 <li><a href='/www-board{{ page.url }}'>{{ page.title }}</a></li>
 {% endif %}
{% endfor %}
</ul>
