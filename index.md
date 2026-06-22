---
layout: default
title: Home
---

## Welcome to Watchamania

My name is Sam and I like wrestling.

I have been watching all of the Wrestlemanias (Wrestlemaniai?) and writing reviews about them.

I have also been doing some other things. You can find links to them in the sidebar.

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
