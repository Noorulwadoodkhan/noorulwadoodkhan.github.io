---
layout: default
title: Blog
---

<h1>Blog</h1>

{% for post in site.posts %}
  <div style="margin-bottom: 2.5em;">
    <p style="color: #999; font-size: 0.9em; margin-bottom: 0.2em;">
      {{ post.date | date: "%B %d, %Y" }}
    </p>
    <h2 style="margin-top: 0; font-size: 1.5em;">
      <a href="{{ post.url }}" style="text-decoration: none; color: black;">
        {{ post.title }}
      </a>
    </h2>
  </div>
{% endfor %}

