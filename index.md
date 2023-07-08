---
title: Book title
---

# Read so far

...

<ul>
  {% for post in site.posts %}
    <li>
      <a href="books{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
