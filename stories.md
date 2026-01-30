---
layout: page
title: Stories
permalink: /stories/
---

# 🌌 Story Portals

Welcome, traveler. Here are the stories that call you:

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
