---
layout: default
title: Home
---

## Welcome to Watchamania

My name is Sam and I like wrestling.

I am going to watch all of the Wrestlemanias and write reviews about them.

You can also find links to some other things I have done in the sidebar.

<img src="https://media.tenor.com/RxH__vKQ5gsAAAAC/the-rock-stone-cold.gif" alt="" width="100%" class="rainbow-border">

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
