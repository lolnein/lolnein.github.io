---
layout: post
title: Archive
---

{% for post in site.posts %}| {{ post.date | date:'%Y-%m-%d' }} | <a href="{{ post.url }}">{{ post.title }}</a> |


{% for image in site.static_files %}
  {% if image.path contains 'thumbs' %}
    {% if file.name contains post.title %}
        
    {% endunless %}
  {% endif %}

{% endfor %}