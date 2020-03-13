---
layout: default
title: Blog
permalink: /blog/
---
<nav>
  <a href="/">Home</a>
  <a href="/about/">About</a>
  <a href="/blog/"><strong>Blog</strong></a>
</nav>
<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
    {% endfor %}
</ul>
