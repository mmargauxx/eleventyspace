---
title: 'Blog'
layout: 'layouts/blog.html'
pagination:
  data: collections.blog
  size: 2
permalink: 'blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'
paginationPrevText: 'Newer posts'
paginationNextText: 'Older posts'
paginationAnchor: '#post-list'
custom_css: 'footer {visibility: visible; font-size:0.5rem;}'
---

Interesting web development articles that I've found over the months.
