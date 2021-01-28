---
title: 'Portfolio'
layout: 'layouts/page.html'
custom_css: 'footer {visibility: hidden; font-size:0.5rem; position:absolute;bottom:2rem;} main {margin-top: 5%;}'
---

My personal portfolio.

### A small selection
<div class="grid">
{% for item in collections.featuredWork %}
  <a href="{{ item.url }}">
    <img src="{{ item.data.image }}" alt="{{ item.data.summary }}"/>
  </a>
{% endfor %}
</div>
