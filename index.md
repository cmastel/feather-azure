---
layout: default
title: "chrismastel.ca"
---


<div class="post-list">
  <ul>
    {% for post in site.posts %}
      <li class="line-item">
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span>{{ post.date | date: "%Y-%m-%d" }}</span>
      </li>
    {% endfor %}
  </ul>
</div>
