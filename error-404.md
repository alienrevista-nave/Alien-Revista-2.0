---
layout: default
title: ERROR 404
permalink: /error-404/
---

<h1 style="color:#ff00ff; text-align:center; font-size:3.2em; margin:40px 0; text-shadow: 0 0 15px #ff00ff;">ERROR 404</h1>

<div style="max-width:900px; margin:0 auto;">
  {% for post in site.categories.error-404 %}
    <div class="post-card">
      <h2 style="color:#ff00ff;">{{ post.title }}</h2>
      <div class="content">{{ post.content }}</div>
      <a href="{{ post.url }}" style="color:#ff00ff;">leer completo →</a>
    </div>
  {% endfor %}
</div>
