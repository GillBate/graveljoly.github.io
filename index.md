---
layout: default
title: Home
---

# Welcome to My Blog

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p style="font-size: small; color: grey;">{{ post.date | date: "%B %d, %Y" }}</p>
  </article>
{% endfor %}
