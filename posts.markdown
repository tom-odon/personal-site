---
layout: page
title: Posts
permalink: /posts/
description: Here's a list of blog posts I've written. 
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% seo %}