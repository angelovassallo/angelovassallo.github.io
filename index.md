---
layout: default
title: Home
---

# Angelo Vassallo Personal Site

## About

Ciao. Sono Angelo, 23 anni Bergamo.
Amo scrivere codice e studio Ingegneria informatica all'UniBG.
[Scopri di più su di me](/about/).

## Portfolio

Niente per ora...

## Blog

Ultime dal blog:

{% for post in site.posts limit:1 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
