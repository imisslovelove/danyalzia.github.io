---
layout: page
title: Archive
---

<div id="home">
<h1>Danyal Zia ({{ site.posts | size }} posts)</h1>
<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
</div>