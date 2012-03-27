---
layout: page
title: Ihaveu Team
tagline: 
---
{% include JB/setup %}

创作是一件开心的事情，沉浸只是因为纯粹的灵感。我希望自己的生命能够时常充满灵感，而文字就是这些愉快时光曾经存在过的证明。


<h4>最近发布的文章</h4>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

