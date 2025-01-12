---
layout: blog
title: Blog
permalink: /blog
---

<h2 class="blog">Introduction</h2>
<div class="intro">
<p class="blog">
One of my hobbies is engaging with poetry.
Therefore, I plan to make available here some of my analyses, interpretations, and translations of songs that I find interesting.
As I already tried to suggest, we can find a lot of poetry also in popular songs.
Therefore, I do not limit myself to poems published as poetry, but to everything I consider poetical.
</p>
<p class="blog">
Below, I have separated poems and song lyrics in separate categories to have a better overview.
</p>
</div>

<div class="toc">
<div class="column">
<h3 class="blog">Lyrics</h3>
<table>
  <tr>
      <th>Singer</th>
      <th>Title</th>
      <th>Language</th>
      <th>Year</th>
  </tr>
{% assign sorted = site.lyrics | sort: 'songtitle' %}
{% for song in sorted %}
  <tr>
      <td> {{ song.singer}} </td>
      <td><a href="{{ song.url }}"> {{ song.songtitle }}</a></td>
      <td> {{ song.language }} </td>
      <td> {{ song.year }} </td>
  </tr>
{% endfor %}
</table>
</div>

<div class="column">
<h3 class="blog">Poems</h3>
</div>
</div>
