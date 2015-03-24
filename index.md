---
layout: page
title: About
tagline:
---
<ul>
  I am a developer and Computer Science student living just outside of Philadelphia, and this site is a place where I can collocate information about my various projects. 
</ul>
<ul >
    <b><h1>Recent Posts:</b></h1>
    {% for post in site.posts limit 4 %}
    <li>
      <h3><b><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></b></h3> <br> {{post.description}}<br>
      <span>  {{ post.date | date_to_string }}</span> &raquo;<br><br>
    {% endfor %}
</ul>

<a href="archive.html">See all posts</a>



