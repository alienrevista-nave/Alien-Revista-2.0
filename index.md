---
layout: default
---

<div class="top-bar">
  <div class="logo">👽 ALIEN</div>
  <div class="nav-buttons">
    <a href="#">ERROR 404</a>
    <a href="#">Archivo corrupto</a>
    <a href="#">Psicosis colectiva</a>
    <a href="#">Sin-ismos</a>
    <a href="#">El sueño del androide</a>
  </div>
</div>

<div class="main-grid">
  <!-- izquierda: entrada grande estilo IG -->
  <div class="left-post">
    {% for post in site.posts limit:1 %}
      <div class="post-card">
        <h2>{{ post.title }}</h2>
        <p class="meta">{{ post.date | date: "%d %B %Y" }} — {{ post.category }}</p>
        <div class="post-content">{{ post.content }}</div>
        <a href="{{ post.url }}" class="leer-mas">leer completo</a>
      </div>
    {% endfor %}
  </div>

  <!-- derecha: sidebar -->
  <div class="right-column">
    <div class="error-card">
      <h3>ERROR 404</h3>
      <!-- acá después ponés tu imagen grande -->
    </div>
    
    <div class="spotify-card">
      <p>Fuera de frecuencia</p>
      <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/57qxI5VqHjOi9sVwA03cWM?utm_source=generator&theme=0" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </div>
</div>
