---
layout: default
title: Home
---

# Benvenuto nella mia pagina

## About

Breve descrizione su di te. [Scopri di più su di me](/about/).

## Portfolio

- [Lavoro 1](link-al-tuo-lavoro1.html)
- [Lavoro 2](link-al-tuo-lavoro2.html)

## Blog

Ultime dal blog:

{% for post in site.posts limit:1 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
