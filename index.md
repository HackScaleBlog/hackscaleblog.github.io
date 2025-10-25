---
layout: default
title: "HackScale Blog"
---

<div class="hero">
  <h1>⚡ HackScale Blog</h1>
  <p>Cybersecurity tutorials, red teaming, and ethical hacking writeups.</p>
</div>

<div class="posts">
  <h2>Latest Posts</h2>
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <small>{{ post.date | date: "%b %d, %Y" }}</small>
      </li>
    {% endfor %}
  </ul>
</div>
