---
layout: default
title: Home
---

<!-- Blog title -->
<h1>blog test: might or might not post articles eventually</h1>

<!-- Section heading -->
<h3>Posts</h3>

<!-- List of posts -->
{% for post in site.posts %}
  <article>
    <p style="font-size: small; color: grey;">{{ post.date | date: "%B %d, %Y" }}</p>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  </article>
{% endfor %}
