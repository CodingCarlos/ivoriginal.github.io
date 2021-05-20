---
layout: default
title: Blog
permalink: /blog/
---

This is a placeholder, so you can add a beautiful heading text, image or whatever you want.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
