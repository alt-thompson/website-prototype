---
layout: default
title: People
---
<h1>people</h1>

<ul>
  {% for person in site.people %}
    <li>
      <h2>{{ person.name }}</h2>
      <h3>{{ person.position }}</h3>
      <p>{{ person.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>