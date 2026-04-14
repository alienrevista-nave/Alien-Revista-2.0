---
layout: default
---

<h2 style="color:#ff00ff; text-align:center; margin:40px 0 30px;">en contacto con la atmósfera</h2>

<div class="main-grid">
  {% for post in site.posts limit:1 %}
    <div class="post-card">
      <h3 style="color:#ff00ff;">{{ post.title }}</h3>
      
      <div class="excerpt">
        somos creadores de contenido<br>
        y alimento del vacío<br>
        somos materialidad en suspenso
      </div>

      <a href="{{ post.url }}" style="color:#ff00ff; font-size:1.1em;">leer completo →</a>
    </div>
  {% endfor %}

  <div class="sidebar">
    <div class="error-card">
      <h3>ERROR 404</h3>
    </div>
    
    <div class="spotify-card">
      <p style="color:#ff00ff;">Fuera de frecuencia</p>
      <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/57qxI5VqHjOi9sVwA03cWM?utm_source=generator&theme=0" width="100%" height="352" frameborder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </div>
</div>
