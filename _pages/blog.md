---
layout: home
title: Blog
permalink: /blog
---

<h1>Posts</h1>

{% for post in site.posts %}
<p><a href="{{ post.url }}">{{ post.title }}</a></p>
{% endfor %}