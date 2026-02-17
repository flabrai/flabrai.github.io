---
layout: page
title: Seminars
---

## Organized Seminars

<ul>
{% for seminar in site.seminars %}
  <li>
    <a href="{{ seminar.url | relative_url }}">
      {{ seminar.title }}
    </a>
  </li>
{% endfor %}
</ul>
