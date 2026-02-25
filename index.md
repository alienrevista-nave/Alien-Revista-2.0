---
layout: default
---

<div style="max-width: 900px; margin: 0 auto; padding: 20px;">
  <h2 style="color: #ff00ff; text-align: center;">Entradas recientes – Issue #1</h2>

  {% for post in site.posts %}
    <div style="background: rgba(0,255,0,0.05); border: 1px solid #00ff00; padding: 20px; margin-bottom: 30px; border-radius: 4px;">
      <h3 style="color: #ff00ff;"><a href="{{ post.url }}" style="color: #ff00ff; text-decoration: none;">{{ post.title }}</a></h3>
      <p style="color: #00ff88;">{{ post.date | date: "%d %B %Y" }} – {{ post.category }}</p>
      <div style="color: #00ff00;">{{ post.excerpt | strip_html | truncate: 200 }}</div>
      <a href="{{ post.url }}" style="color: #ff00ff;">leer completo</a>
    </div>
  {% endfor %}
</div>
