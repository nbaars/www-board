### General Info
The OWASP Global Board typically meets over video-conference on the third Tuesday of each month. Upcoming meetings are listed below.

### Upcoming Meetings
{% assign pages = site.pages | sort: 'date' | limit: 6 %}
<ul>
{% for page in pages %}
 {% if page.path contains 'meetings/' %}
 <li><a href='/www-board{{ page.url }}'>{{ page.title }}</a></li>
 {% endif %}
{% endfor %}
</ul>
