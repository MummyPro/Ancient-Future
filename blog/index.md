---
layout: default
title: Story Portals
---

<h1>🌀 Future Memories</h1>
<p>Every story is a doorway — waiting for you to knock.</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
