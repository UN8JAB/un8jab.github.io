---
layout: home
title: "Главная"
---

Добро пожаловать в мой блог! ✨  
Здесь будут заметки о радиолюбительстве, микроконтроллерах и программировании.

<h2>Последние посты</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
