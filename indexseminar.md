---
layout: page
title: Seminars
---

## Organized Seminars

prueba 1 olakase

<ul>
{% for seminar in site.seminars %}
  <li>
    <a href="{{ seminar.url | relative_url }}">
      {{ seminar.title }}
    </a>
  </li>
{% endfor %}
</ul>
