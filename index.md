---
layout: default
---

# My Story Collection 📖

Here are all my stories, with the newest ones first.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

