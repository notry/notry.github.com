---
layout: page
title: about  leslie
tagline: about me
---
{% include JB/setup %}

我曾经跳进冰冷彻骨的河水中，救起了一个豆蔻少女 是的，是这样的.
日志列表：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

