---
layout: default
title: ERROR 404
permalink: /error-404/
---

<h1 style="color:#ff00ff; text-align:center; font-size:3.2em; margin:40px 0; text-shadow: 0 0 15px #ff00ff;">ERROR 404</h1>

<div style="max-width:900px; margin:0 auto;">
  {% for post in site.categories.error-404 %}
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

      <a href="{{ post.url }}" style="color:#ff00ff; font-size:1.2em;">leer completo →</a>
    </div>
  {% endfor %}
</div>
