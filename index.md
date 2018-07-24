---
title: COMP 436
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: Markup Languages, Fall 2018
---

Welcome to the course website for COMP 436, *Markup Languages*.

This course is offered by the [Department of Computer Science](http://www.luc.edu/cs/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}

<!--{{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})-->
* {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})

  {{ post.summary }}

{% endfor %}
