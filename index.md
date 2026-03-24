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

<div class="main-grid">
  <!-- Columna izquierda: post con Reel arriba -->
  {% for post in site.posts limit:1 %}
    <div class="post-card">
      {{ post.content }}
    </div>
  {% endfor %}

  <!-- Columna derecha: sidebar -->
  <div class="sidebar">
    <div class="error-card">
      <h3>ERROR 404</h3>
      <!-- Aquí después ponés tu imagen grande de la alien hostess -->
    </div>
    
    <div class="spotify-card">
      <p style="color:#ff00ff;">Fuera de frecuencia</p>
      <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/57qxI5VqHjOi9sVwA03cWM?utm_source=generator&theme=0" width="100%" height="352" frameborder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </div>
</div>
