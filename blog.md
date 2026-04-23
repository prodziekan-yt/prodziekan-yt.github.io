---
layout: default
title: blog
---

# [blogowisko]

Wszystkie wpisy:

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%d.%m.%Y" }}</span> 
      <a class="post-link" href="{{ post.url | relative_url }}"> > {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
