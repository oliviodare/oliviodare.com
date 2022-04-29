---
layout: default
title: blog | oliviodare
description: Max Bautista Perpinyà's blog
style:  type2page
pageID: blog-page
---


## Blog, Latest Posts
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    <li>{{ post.excerpt }}</li>
  {% endfor %}
</ul>
