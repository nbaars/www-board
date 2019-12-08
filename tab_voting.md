---
title: Voting
layout:  null
tab: true
order: 2
tags: board
---

## Board Actions

Following is a reverse chronological list of actions with a vote by the Global Board. For additional processing these motions can be accessed in this repo in the _data/votes.yml file. Historically there have been variations in recording votes, which if needed can be retrieved from historical board minutes.

<hr>

{% for motions in site.data.votes %}
 <p>{{ motions.date }}<br>{{ motions.motion }}. {% if motions.result %}<span style="color:#bb8d04">{{ motions.result }}</span>.{% endif%} {% if motions.vote %} {{ motions.vote }}.{% endif %}</p>
  <hr>
{% endfor %}	

<ul>
{% for motions in site.data.votes %}
 <li>{{ motions.date }}: {{ motions.motion }}. <strong>{{ motions.result }}</strong>. {{ motions.vote }}.</li>
{% endfor %}	
</ul>


## Board Votes as table

{% for motions in site.data.votes %}
 {{ motions.date }} | {{ motions.result }} | {{ motions.motion }}
{% endfor %}	

## Board Votes

 Date          | Result               | Motion        
 ---------------- | ----------------------- | -------------------------------------------------------------------------------- 
 2019-09-25  | Passes: 6-0            |  Motion: beginning January 1, 2020 the Foundation has decided to change the profit splits of the Global AppSec events. The split will be 90% to the Foundation and 10% to the Chapters. The Chapter will have the option to give the funds back to the Foundation or the Community Fund. If there is no current active Chapter in the area the full 100% will be given to the Foundation. Ofer Maor motions, Richard Greenberg seconds 
 2019-09-25  | Passes: 7-0            |  Motion: the Board will have two face to face meetings each calendar year which will be held in conjunction with the Global AppSec events. Ofer Maor motions, Owen Penblebury seconds 

## Board votes #3

| Date          | Result               | Motion        |
| ---------------- | ----------------------- | -------------------------------------------------------------------------------- |
| 2019-09-25  | Passes: 6-0            |  Motion: beginning January 1, 2020 the Foundation has decided to change the profit splits of the Global AppSec events. The split will be 90% to the Foundation and 10% to the Chapters. The Chapter will have the option to give the funds back to the Foundation or the Community Fund. If there is no current active Chapter in the area the full 100% will be given to the Foundation. Ofer Maor motions, Richard Greenberg seconds |
| 2019-09-25  | Passes: 7-0            |  Motion: the Board will have two face to face meetings each calendar year which will be held in conjunction with the Global AppSec events. Ofer Maor motions, Owen Penblebury seconds |
| 2019-09-25  | Passes: 6-1            |  Motion: the Board is to have a 4 hour video conference call in January each year in order to onboard new members, set strategy and assign Board Member roles. Ofer Maor motions, Owen Pendblebury seconds. |
