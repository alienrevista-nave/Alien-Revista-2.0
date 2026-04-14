---
layout: default
---

<h2 style="color:#ff00ff; text-align:center; margin:40px 0 30px;">en contacto con la atmósfera</h2>

<div class="main-grid">

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

      <!-- Extracto corto (solo las 3 líneas) -->
      <div style="text-align:center; font-size:1.15em; line-height:1.6; margin-bottom:30px;">
        somos creadores de contenido<br>
        y alimento del vacío<br>
        somos materialidad en suspenso
      </div>

      <!-- Botón correcto -->
      <a href="{{ post.url }}" style="color:#ff00ff; font-size:1.2em;">leer completo →</a>
    </div>
  {% endfor %}

  <!-- Sidebar -->
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
