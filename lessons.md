---
layout: page
title: Lessons
permalink: /lessons/
---

#### Note: These lessons will "play" like they are slide shows in class. Clicking will move you to the next slide.

{%- for lesson in site.data.lessons %}
 * {{ lesson.date }}: [{{ lesson.name }}]({{ lesson.link }}){:target="_blank"}
 {%- endfor -%}
