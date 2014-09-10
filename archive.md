---
layout: page
title: Lưu trữ
permalink: /archive/
---
<img src="/res/archive.png" width="64" height="64" align="right" alt="archive">

<ul>
{% for post in site.posts %}
  <li>
    {{ post.date | date: "%d/%m/%Y"  }} &mdash; <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
