
---
layout: default
title: El sueño del androide
permalink: /sueno-del-androide/
---

<h1 style="color:#ff00ff; text-align:center; font-size:3em; margin:40px 0;">El sueño del androide</h1>

<div style="max-width:900px; margin:0 auto;">
  {% for post in site.categories.sueno-del-androide %}
    <div class="post-card">
      <h2 style="color:#ff00ff;">{{ post.title }}</h2>
      <div class="content">{{ post.content }}</div>
      <a href="{{ post.url }}" style="color:#ff00ff;">leer completo →</a>
    </div>
  {% endfor %}
</div>
