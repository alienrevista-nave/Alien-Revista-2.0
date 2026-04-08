---
layout: default
title: ERROR 404
permalink: /error-404/
---

<h1 style="color:#ff00ff; text-align:center; font-size:3em; margin:30px 0; text-shadow: 0 0 10px #ff00ff;">ERROR 404</h1>

<p style="text-align:center; color:#00ff88; font-size:1.3em; margin-bottom:40px;">en contacto con la atmósfera</p>

<div style="max-width:900px; margin:0 auto;">
  {% for post in site.categories.ERROR-404 %}
    <div class="post-card">
      <h2 style="color:#ff00ff;">{{ post.title }}</h2>
      <div class="content">{{ post.content }}</div>
      <a href="{{ post.url }}" style="color:#ff00ff;">leer completo →</a>
    </div>
  {% endfor %}
</div>

<style>
  .post-card {
    background: rgba(255, 0, 0, 0.03);
    border: 2px solid #ff00ff;
    padding: 30px;
    margin-bottom: 40px;
    border-radius: 4px;
    box-shadow: 0 0 15px rgba(255, 0, 255, 0.2);
  }
</style>
