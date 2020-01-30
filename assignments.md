---
layout: page
title: Assignments
permalink: /assignments/
---


<ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
          {{ post.content }}
    </li>
  {% endfor %}
</ul>
