---
layout: default
title: "chrismastel.ca"
---


<div class="post-list">
  {% for post in site.posts %}
    <div class="line-item">
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
    </div>
  {% endfor %}
</div>
