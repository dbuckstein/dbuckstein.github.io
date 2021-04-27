---
permalink: /blog/
---

[Home](../)

[Projects](/projects/)

[About](/about/)

# Blog

This page is where the blog posts live.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
