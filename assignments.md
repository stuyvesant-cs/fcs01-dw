---
layout: page
title: Assignments
permalink: /assignments/
---


Solutions can be found here:
- HTML/CSS: <https://github.com/mks22-dw/dwsource/tree/main/html>
- Python: <>

### Important Notes

All Assignments will be submitted via GitHub classroom. Labs and projects will have their own assignment links, all homeworks should be submitted in the homework repository.
- Period 9 GH Classroom link: <https://classroom.github.com/a/BAYiJG1f>
- Period 10 GH Classroom link: <https://classroom.github.com/a/LGqw6ovx>

If you did not receive credit (see a 0 on jupiter) for an assignment that you completed, [fill out this form](). This includes if you submitted work late for an absence or otherwise. _DO NOT__ fill out this form if the assignment doesn’t appear on jupiter at all.

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
