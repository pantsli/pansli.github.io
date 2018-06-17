---
layout: default
title: Pantsli's Corner
---

<p><br /><b>My Blog:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<p><br /><b>Contact Information:</b></p>

<blockquote>
欢迎所有朋友加我微信：atong345789
</blockquote>

[oss]:http://en.wikipedia.org/wiki/Open_source
