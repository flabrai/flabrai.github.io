---
layout: page
title: Seminars
mathjax: true
---

## Organized Seminars

Some of the seminars in which I have been part of the organization

<ul>
{% for seminar in site.seminars %}
  <li>
    <a href="{{ seminar.url | relative_url }}">
      {{ seminar.title }}
    </a>
  </li>
{% endfor %}
</ul>

## Talks on seminars

* Introducción a EDPs en geometría Riemanniana. [Seminario de Geometría Riemanniana 2025, PUC.](https://www.mat.uc.cl/seminarios/slgr.html) [Notas](/Documentos/EDP_GeometriaRiemanniana.pdf).
