---
layout: default
title: Home
---

![Stone Cold Steve Austin](https://media.tenor.com/RxH__vKQ5gsAAAAC/the-rock-stone-cold.gif)

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
