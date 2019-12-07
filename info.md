### General Info
The OWASP Global Board typically meets over video-conference on the third Tuesday of each month. Upcoming meetings are listed and hyperlinked below.

### Upcoming Meetings
{% assign pages = site.pages | sort: 'date' | limit: 6 %}
<ul>
{% for page in pages %}
 {% if page.path contains 'meetings/' %}
 <li><a href='/www-board{{ page.url }}'>{{ page.title }}</a></li>
 {% endif %}
{% endfor %}
</ul>

### Officers
* [Martin Knobloch, Chair](mailto:martin.knobloch@owasp.org)
* [Owen Pendlebury, Vice Chair](mailto:owen.pendlebury@owasp.org)
* [Sherif Mansour, Treasurer](mailto:sherif.mansour@owasp.org)
* [Ofer Maor, Secretary](mailto:ofer.maor@owasp.org)

### Members at Large
* [Richard Greenberg](mailto:richard.greenberg@owasp.org)
* [Gary Robinson](mailto:gary.robinson@owasp.org)
* [Chengxi Wang](mailto:chengxi.wang@owasp.org)


