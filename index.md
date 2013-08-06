---
layout: page
title: 
---
{% include JB/setup %}

## 最近更新

<ul class="posts">
  {% for post in site.posts %}
    <li>
        <b><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></b>
        <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

