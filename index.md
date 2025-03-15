---
layout: default
title: Home
---

<h2>Welcome to my Jekyll blog hosted on GitHub Pages!</h2>
<p>Here are my latest posts:</p>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
