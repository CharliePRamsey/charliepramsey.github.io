---
layout: default
username: Parker's Posts
user_title: Soon to be better formatted musings (i hope)
focus: "#projects"
permalink: /blog/
---
<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>