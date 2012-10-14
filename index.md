---
layout: page
title: 蛋几宁施，个必踢米!
tagline: 是“但尽人事，各凭天命”的意思啦
---
{% include JB/setup %}

## 文章列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
