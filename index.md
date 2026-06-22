---
layout: default
title: Home
---

<img src="https://media.tenor.com/RxH__vKQ5gsAAAAC/the-rock-stone-cold.gif" alt="" width="100%">

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
