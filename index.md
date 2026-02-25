<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALIEN REVISTA</title>
    <style>
        body {
            background-color: black;
            color: #00ff00;
            font-family: monospace;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }
        h1 {
            color: #ff00ff;
            font-size: 3.2em;
            margin: 0 0 10px 0;
        }
        h2 {
            color: #ff00ff;
        }
        a {
            color: #ff00ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        nav {
            margin-bottom: 50px;
        }
        nav a {
            margin-right: 25px;
            font-size: 1.15em;
        }
        .hero {
            margin-bottom: 70px;
        }
        .entradas {
            max-width: 820px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            margin-bottom: 18px;
            font-size: 1.25em;
        }
    </style>
</head>
<body>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="about.html">About</a>
        <a href="error-404.html">ERROR 404</a>
        <a href="archivo-corrupto.html">Archivo corrupto</a>
        <a href="psicosis-colectiva.html">Psicosis colectiva</a>
        <a href="sin-ismos.html">Sin-ismos</a>
        <a href="sueno-del-androide.html">El sueño del androide</a>---
layout: default
---

<h2>Entradas recientes – Issue #1</h2>

<div class="posts">
  {% for post in site.posts %}
    <div class="post-card">
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p class="date">{{ post.date | date: "%d %B %Y" }}</p>
      <p>{{ post.excerpt }}</p>
      <a href="{{ post.url }}">leer completo</a>
    </div>
  {% endfor %}
</div>
