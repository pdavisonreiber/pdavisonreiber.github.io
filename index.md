---
layout: page
title: Peter Davison-Reiber
---
Welcome to my website. I'm a teacher of Mathematics and Computer Science living and working in London.

## Tutoring
- I offer online tutoring in mathematics. [See here](/tutoring) for more details.

## Apps
- I make an app called [Kwicket](https://kwicket.app) for easy cricket scoring.
- I make an app called [Grader+](http://davisonreiber.com/graderplus/) for easy counting of marks on exams.

## Recent Blog Posts
<div class="monospace">
{% for post in site.posts limit:3 %}{{ post.date | date: "%Y-%m-%d" }} <a href="{{ post.url }}">{{ post.title }}</a><br>
{% endfor %}
</div>