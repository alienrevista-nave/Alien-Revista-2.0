---
layout: default
---

<div class="header">
  <div class="logo">👽 ALIEN</div>
  <div class="nav">
    <a href="#">ERROR 404</a>
    <a href="#">Archivo corrupto</a>
    <a href="#">Psicosis colectiva</a>
    <a href="#">Sin-ismos</a>
    <a href="#">El sueño del androide</a>
  </div>
</div>

<h2 style="color:#ff00ff; text-align:center; margin:40px 0 30px;">Entradas recientes – Issue #1</h2>

{% for post in site.posts limit:1 %}
  <div class="post-card">
    <h3>{{ post.title }}</h3>
    <p class="meta">{{ post.date | date: "%d %B %Y" }} — {{ post.category }}</p>
    <div class="content">{{ post.content }}</div>
    <a href="{{ post.url }}" class="leer">leer completo</a>
  </div>
{% endfor %}
