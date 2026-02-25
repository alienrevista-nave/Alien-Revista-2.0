---
layout: default
---

<div class="header">
  <div class="logo">
    <span class="alien">👽</span> ALIEN
  </div>
  <div class="nav">
    <a href="#">ERROR 404</a>
    <a href="#">Archivo corrupto</a>
    <a href="#">Psicosis colectiva</a>
    <a href="#">Sin-ismos</a>
    <a href="#">El sueño del androide</a>
    <a href="#">Fuera de frecuencia</a>
  </div>
</div>

<div class="main-grid">
  <!-- izquierda - entrada grande -->
  <div class="post-main">
    {% for post in site.posts limit:1 %}
      <div class="post-card-big">
        <h2>{{ post.title }}</h2>
        <p class="meta">{{ post.date | date: "%d %B %Y" }} – {{ post.category }}</p>
        <div class="content">{{ post.content }}</div>
        <a href="{{ post.url }}" class="leer">leer completo</a>
      </div>
    {% endfor %}
  </div>

  <!-- derecha - sidebar -->
  <div class="sidebar">
    <div class="error-box">
      <h3>ERROR 404</h3>
      <!-- acá después ponés tu imagen -->
    </div>
    
    <div class="spotify-box">
      <p>Fuera de frecuencia</p>
      <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/57qxI5VqHjOi9sVwA03cWM?utm_source=generator&theme=0" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </div>
</div>
