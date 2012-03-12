---
layout: page
title: 陳細文 blog
tagline: Supporting tagline
header: 陳細文 blog
description: 陳細文 blog
---

談風中月，說杯中茶。如有雷同，純屬巧合。

#### incoming
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>