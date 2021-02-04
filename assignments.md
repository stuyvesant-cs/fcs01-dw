---
layout: page
title: Assignments
permalink: /assignments/
---

#### Submit all assignments here: <http://bert.stuy.edu/jdyrland/spring2021/pages.py>
<hr>

<ul>
  {% for post in site.posts %}
    <li>
        <a class="assignment_link" href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
          {{ post.excerpt }}
      <hr>
    </li>
  {% endfor %}
</ul>
