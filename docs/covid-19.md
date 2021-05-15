---
title: COVID-19 Information
description: Promising practices related to child welfare and coronavirus.
layout: page
sidenav: sidebar
subnav:
  - text: Foster Parent Licensing
    href: /licensing
  - text: Background Checks
    href: /background-checks
  - text: Extended Foster Care
    href: /extended-foster-care
  - text: Family Finding
    href: /family-finding
  - text: Inquiry Management
    href: /inquiries
  - text: License Renewals
    href: /renewals
  - text: Recruitment
    href: /recruitment
  - text: Retention
    href: /retention
  - text: COVID-19
    href: /covid-19
---

Find promising practices related to child welfare and coronavirus on our sister site, the [Think of Us COVID-19 Child Welfare Command Center](https://thinkofus.gitbook.io/command-center/resources/agencies).

<ul>
  {% assign filtered_posts = site.pages | where: 'topic', 'covid-19' %}
  {% for post in filtered_posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
	{{ post.description }}
	<p>
	<b>Who can do this?</b> {{ post.audience }}<br />
	<b>Cost:</b> {{ post.cost }}<br />
	<b>Timeframe:</b> {{ post.timeframe }}<br />
	<b>Difficulty:</b> {{ post.difficulty }}<br />
	</p>
  {% endfor %}
</ul>
