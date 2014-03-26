---
layout: page
title: 欢迎大家来到一只柯楠的主页
tagline: Supporting tagline
---
{% include JB/setup %}
##精彩内容即将开始哦。。。


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



