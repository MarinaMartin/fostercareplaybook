---
title: Working Group News and Announcements
description: News and announcements related to the foster care playbook.
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

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
	{{ post.content }}
  {% endfor %}
</ul>