---
layout: page
title: Blog Posts
permalink: /blog/
---

<font face="Courier">
{% for post in site.posts %}{{ post.date | date: "%Y-%m-%d" }} <a href="{{ post.url }}">{{ post.title }}</a><br>
{% endfor %}
</font>