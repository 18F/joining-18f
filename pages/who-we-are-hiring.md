---
title: Who are we hiring?
layout: default
permalink: /who-we-are-hiring/
---
We're looking for candidates who are passionate about our mission, with top-notch software development, design, content, and operations skills to match. Below you will find a list of our current job openings. 

## Do I have to be a citizen to work at 18F? 

If you can legally work in the U.S. then you are eligible to work for 18F. You do not have to be a U.S. citizen, but our agency is unable to sponsor visas, so you must already be able to work in the U.S. 

## Where are we hiring?

Everywhere in the United States! If you have no experience working on remote teams or are applying for a role that requires in-person interactions with clients, we'll ask you to work out of our San Francisco or D.C. office. However, the majority of our team is distributed across the country in places like Chicago, New York, Raleigh, Tuscon, Austin, Dayton, Philadelphia, Santa Barbara, Seattle, and Portland.

## Open positions

<h3>Consulting</h3>
<ul>
{% assign positions = site.positions | where:"team","consulting" %}
{% for position in positions %}
    <li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>

<h3>Delivery</h3>
<ul>
{% assign positions = site.positions | where:"team","delivery" %}
{% for position in positions %}
    <li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>

<h3>Design</h3>
<ul>
{% assign positions = site.positions | where:"team","design" %}
{% for position in positions %}
    <li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>

<h3>DevOps</h3>
<ul>
{% assign positions = site.positions | where:"team","devops" %}
{% for position in positions %}
    <li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>


<h3>Engineering</h3>
<ul>
{% assign positions = site.positions | where:"team","engineering" %}
{% for position in positions %}
    <li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>

<h3>Outreach</h3>
<ul>
{% assign positions = site.positions | where:"team","outreach" %}
{% for position in positions %}
    <li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>

<h3>Other</h3>
<ul>
{% assign positions = site.positions | where:"team","other" %}
{% for position in positions %}
    <li><a href="{{site.baseurl}}{{ position.url }}">{{ position.title }}</a></li>
{% endfor %}
</ul>