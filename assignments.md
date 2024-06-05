---
layout: page
title: Assignments
permalink: /assignments/
---


Solutions can be found here:
- HTML/CSS: <https://github.com/mks22-dw/dwsource/tree/main/html>
- Python: <https://github.com/mks22-dw/dwsource/tree/main/python>
- Python Server-Side CGI Programs: <https://github.com/mks22-dw/dwsource/tree/main/python_web>

### Important Notes

All Assignments will be submitted via GitHub classroom. Labs and projects will have their own assignment links, all homeworks should be submitted in the homework repository.
- Period 9 GH Classroom link: <https://classroom.github.com/a/BAYiJG1f>
- Period 10 GH Classroom link: <https://classroom.github.com/a/LGqw6ovx>

### UPDATE for Wesnesday 6/5
If you did not receive credit (see a 0 on jupiter) for an assignment that you completed, or believe your grade is incorrect, [fill out this form](https://forms.gle/nivnrRh5vguJG5fT8). This includes if you submitted work late for an absence or otherwise. __DO NOT__ fill out this form if the assignment doesn't appear on jupiter at all. Submit separate forms for each assignment you would like me to re-evaluate.
- You must provide an explantion if you believe your grade is incorrect (instead of a 0).
- You are not gauranteed to get credit or a changed grade.
- You must fill out the above form by __10:00am MONDAY 6/10__ in order to have your work looked at.
  - Submissions to the form after this deadline will not be considered.

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
