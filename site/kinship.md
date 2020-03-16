---
title: Kinship Plays
description: Best practices related to kinship.
layout: page
sidenav: sidebar
subnav:
  - text: COVID-19
    href: /covid-19
  - text: Kinship
    href: /kinship
  - text: Foster Parent Licensing
    href: /licensing
  - text: Extended Foster Care
    href: /extended-foster-care
---

{{ page.description }}

COMING SOON - This is the workgroup topic for April.

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