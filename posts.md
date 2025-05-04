---
layout: default
title: Thoughts
permalink: /thoughts/
---

## Thoughts

Here are some of my recent posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span> – {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
