---

layout: col-sidebar
title: Global Board

---

The OWASP Foundation Global Board is comprised of seven elected members who serve for two-year terms. Each Fall, membership votes to elect new leadership for the Foundation. Generally our Board meets monthly and meetings are open to the public. The Global Board sets the strategic direction of the Foundation, its policies, and sets governance and leadership roles. 

## Upcoming Meetings
{% assign pages = site.pages | sort: 'date' | limit: 12 %}
<ul>
{% for page in pages %}
 {% if page.path contains 'meetings/' %}
 <li><a href='/www-board{{ page.url }}'>{{ page.title }}</a>{% if page.date %}, {{ page.date }}{% endif %}</li>
 {% endif %}
{% endfor %}
</ul>

## Typical Board Meeting Agenda

#### Call to Order
The first order of business is for the chair to announce the call to order, along with the time. The secretary enters the time of the call to order in the minutes. After the meeting is called to order, the board chair may make welcoming remarks, ask for introductions, or read the organization’s mission and vision statements.

#### Changes to the Agenda
The second order of business is for the chair to ask for changes to the agenda. Additions and deletions to the agenda will be made at this time. Having no changes, the agenda moves to approving the prior meeting’s minutes.

#### Approval of Minutes
The third item on the agenda should list “Approval of Minutes” along with the date of the most recent meeting. In most cases, board members should have received a copy of the minutes prior to the meeting. If they have not contacted the secretary prior to the meeting with corrections or changes to the minutes, they have to opportunity to make them during this item on the agenda.

Board members have an ethical and legal responsibility to make sure that the recording of the minutes accurately reflect the board’s business.

#### Reports
The fourth item on the agenda is the reports. This first report should be a report from the Executive Director. This report should include a review of operations and projects. The Executive Director should give board members on overview of the business outlook including positive and negative trends, major initiatives, business updates, and other aspects of the business.

Following the Executive Director report, the Finance Director gives a report. Board members should make an effort to understand the financial reports so that they can identify potential financial threats. Understanding financial reports may also generate discussion about potential opportunities.

Subsequent reports may be given by committee chairs.

#### Old Business
Items should include past business items that are unresolved, need further discussion, or require a board vote. Items may be tabled or referred to committee for further exploration.

#### New Business
Board members should have a discussion about new business items and identify a plan to take action. This may include tabling them, delaying action to a future date, or referring them to a committee.

#### Comments, Announcements, and Other Business
At this point in the agenda, members may make announcements, such as offering congratulations or condolences, or make other special announcements. Any other business may be brought up at this time, for example, items that may need to be added to the next meeting’s agenda.

#### Adjournment
This is a formal closing of the meeting by the board chair. He should state the time that the meeting closed, so that the secretary may including it in the board minutes. The date of the next meeting should follow the adjournment item, so that board members will be reminded to put it on their calendars.

For more information about the Roberts Rules of Order see this [Cheat Sheet](http://www.umecra.com/BylawsAndRules/Roberts%20Rules%20Handout.pdf)


Pictured above is the Global Board Class of 2019. From left to right: [Martin Knobloch, Chair](mailto:martin.knobloch@owasp.org), [Sherif Mansour, Treasurer](mailto:sherif.mansour@owasp.org), [Owen Pendlebury, Vice Chair](mailto:owen.pendlebury@owasp.org), [Richard Greenberg, Member at Large](mailto:richard.greenberg@owasp.org), [Gary Robinson, Member at Large](mailto:gary.robinson@owasp.org), [Ofer Maor, Secretary](mailto:ofer.maor@owasp.org), [Chengxi Wang, Member at Large](mailto:chengxi.wang@owasp.org)
