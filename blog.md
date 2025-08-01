---
layout: page
title: Blog
permalink: /blog/
---

<h2>My Blog</h2>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%b %d, %Y" }}</li>
  {% endfor %}
</ul>
