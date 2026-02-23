---
layout: blog
title: Blog
description: Here be writings
permalink: /blog
---

Here be writings. Mostly mundane, sometimes fanciful.

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>