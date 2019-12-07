### Upcoming Meetings
{% assign pages = site.pages | sort: 'date' | limit: 3 %}
<ul>
{% for page in pages %}
 {% if page.path contains 'meetings/' %}
 <li><a href='/www-board{{ page.url }}'>{{ page.title }}</a>{% if page.date %}, {{ page.date }}{% endif %}</li>
 {% endif %}
{% endfor %}
</ul>

### Members
* [Martin Knobloch, Chair](mailto:martin.knobloch@owasp.org)
* [Owen Pendlebury, Vice Chair](mailto:owen.pendlebury@owasp.org)
* [Sherif Mansour, Treasurer](mailto:sherif.mansour@owasp.org)
* [Ofer Maor, Secretary](mailto:ofer.maor@owasp.org)
* [Richard Greenberg, Member at Large](mailto:richard.greenberg@owasp.org)
* [Gary Robinson, Member at Large](mailto:gary.robinson@owasp.org)
* [Chengxi Wang, Member at Large](mailto:chengxi.wang@owasp.org)


