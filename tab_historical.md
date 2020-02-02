---
title: Historical
layout:  null
tab: true
order: 1
tags: board
---

As part of our recent website migration, we have been migrating old Board content to this site. If you're looking for historical agendas or minutes not found below please visit the [Historical Wiki](https://wiki.owasp.org/index.php/Board#tab=Historical_Meeting_Archive).

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
