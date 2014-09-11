---
layout: page
title: Welcome to joey blog 
---
{% include JB/setup %}

**WELCOME**
------

## My Docs

<ul class="posts">
  {% for post in site.posts %}
    <p><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></p>
  {% endfor %}
</ul>


----------
Jia Dong  jiadong2006@gmail.com  

