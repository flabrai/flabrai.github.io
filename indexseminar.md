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

## Talks and posters

* Introducción a EDPs en geometría Riemanniana. [Seminario de Geometría Riemanniana 2025, PUC.](https://www.mat.uc.cl/seminarios/slgr.html) [Notas](/Documentos/EDP_GeometriaRiemanniana.pdf).
* Sobre la dimensión del conjunto de observabilidad para la ecuación de calor. [Notas](/Documentos/SeminarioProblemasAbiertos.pdf).
* Stabilization of waves on exterior domains with boundary feedback - [IPPHYS 2026](https://eventos.cmm.uchile.cl/ipphys2026/index.html). [Poster](/Documentos/Poster_Ondas_Dominio_Exterior-2.pdf).
* Stabilization of waves on exterior domains with boundary feedback - [Jornada Matemática de la Zona Sur 2026](https://ciencias.ubiobio.cl/jmzs).
* Ecuación de Laplace y desigualdad de Harnack . Club de EDP, Instituto de Matemática y Computación, PUC. [Notas](/Documentos/ClupEDP_LaplaceHarnack.pdf)
