---
layout: page
title: Assignments
permalink: /assignments/
---


<ul>
  {% for post in site.posts %}
    <li>
        <a class="assignment_link" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
          {{ post.content }}
      <hr>
    </li>
  {% endfor %}
</ul>
