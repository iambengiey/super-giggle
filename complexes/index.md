---
layout: default
title: Complexes
permalink: /complexes/
---

# Complexes

Select your complex:

<ul class="cards">
  {% for complex in site.data.complexes %}
  <li>
    <strong>{{ complex.name }}</strong> <span class="muted">({{ complex.city }})</span><br>
    <a href="{{ '/c/' | append: complex.slug | append: '/' | relative_url }}">Open tenant page</a>
  </li>
  {% endfor %}
</ul>
