---
layout: default
title: Plays Sorted by Topic
---
<h1>Topics</h1>

<ul>
  {% for topic in site.topics %}
    <li>
      <h2>{{ topic.name }}</h2>
      <p>{{ topic.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>