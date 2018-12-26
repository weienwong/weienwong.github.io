---
layout: default
---

# Welcome to Wei-En's World

This is my personal site where I will showcase my projects
You can find my resume <a href="/resume">here</a>  

# About Me

Born and raised in Toronto, Canada. Lives in San Diego, California. 
Software Engineer by day, tinkerer by night!

# Some Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# More Coming Soon!
