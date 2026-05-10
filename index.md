---
layout: default
---

<div class="main-grid">
  <!-- POST PRINCIPAL -->
  {% for post in site.posts limit:1 %}
    <div class="post-card">
      <!-- Reel -->
      <div style="max-width: 540px; margin: 0 auto 25px; border: 3px solid #00ff00; border-radius: 8px; overflow: hidden;">
        <iframe
          src="https://www.instagram.com/reel/DWP91WnAYQ5/embed"
          width="100%"
          height="750"
          frameborder="0"
          scrolling="no"
          allowtransparency="true"
          style="max-width:100%; display:block;">
        </iframe>
      </div>

      <!-- Extracto corto -->
      <div style="text-align:center; font-size:1.15em; line-height:1.6; margin-bottom:35px; color:#00ff00;">
        somos creadores de contenido<br>
        y alimento del vacío<br>
        somos materialidad en suspenso
      </div>

      <div style="text-align:center;">
        <a href="{{ post.url }}" class="leer-btn">
          leer completo →
        </a>
      </div>
    </div>
  {% endfor %}

  <!-- BARRA LATERAL -->
  <div class="sidebar">
    <div class="error-card">
      <h3>ERROR 404</h3>
      <p style="color:#00ff88; font-size:0.95em;">Última publicación</p>
    </div>
   
    <div class="spotify-card">
      <p style="color:#ff00ff; margin-bottom:10px;">Fuera de frecuencia</p>
      <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/57qxI5VqHjOi9sVwA03cWM?utm_source=generator&theme=0" width="100%" height="352" frameborder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </div>
</div>
