---
title: Working Group News and Announcements
description: News and announcements related to the foster care playbook.
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

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
	{{ post.content }}
  {% endfor %}
</ul>