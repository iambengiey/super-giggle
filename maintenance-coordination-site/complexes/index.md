---
layout: default
title: Complexes
permalink: /complexes/
---

# Choose your complex

<p class="muted">Use your own complex page to submit maintenance requests.</p>

<ul class="cards">
  {% for complex in site.data.complexes %}
  <li>
    <h2>{{ complex.name }}</h2>
    <p class="muted">{{ complex.city }}</p>
    <p><a class="button" href="{{ '/c/' | append: complex.slug | append: '/' | relative_url }}">Open tenant page</a></p>
  </li>
  {% endfor %}
</ul>
