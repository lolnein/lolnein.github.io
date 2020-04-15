---
layout: post
title: Archive
---

{% for post in site.posts %}| {{ post.date | date:'%Y-%m-%d' }} | <img src="/thumbs/{{ post.comic }}" onerror="this.src='/assets/black.png';"/> | <a href="{{ post.url }}">{{ post.title }}</a> |
{% endfor %}
