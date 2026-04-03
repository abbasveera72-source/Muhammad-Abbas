---
layout: default
title: Blog
---

# Blog

<ul>
{% for post in site.posts %}
  <li>{{ post.title }}</li>
{% endfor %}
</ul>
