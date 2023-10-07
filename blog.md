---
layout: default
title: Blog
---

# Blog

Ecco gli ultimi post:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
