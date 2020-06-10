---
title: Extended Foster Care
description: Best practices related to extended foster care.
layout: page
sidenav: sidebar
subnav:
  - text: Foster Parent Licensing
    href: /licensing
  - text: Extended Foster Care
    href: /extended-foster-care
  - text: COVID-19
    href: /covid-19
---

{{ page.description }}

COMING SOON

<ul>
  {% assign filtered_posts = site.pages | where: 'topic', 'kinship' %}
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
