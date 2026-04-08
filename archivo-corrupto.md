---
layout: default
title: Archivo corrupto
permalink: /archivo-corrupto/
---

<h1 style="color:#ff00ff; text-align:center; font-size:3em; margin:40px 0;">Archivo corrupto</h1>

{% for post in site.categories.archivo-corrupto %}
  <div class="post-card">
    <h2 style="color:#ff00ff;">{{ post.title }}</h2>
    <div class="content">{{ post.content }}</div>
    <a href="{{ post.url }}" style="color:#ff00ff;">leer completo →</a>
  </div>
{% endfor %}
