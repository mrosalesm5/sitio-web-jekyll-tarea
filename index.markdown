---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# ¡Hola Mundo!

Bienvenido a mi sitio con Jekyll.

![Imagen destacada](/images/thumb-up.jpg)

## Últimos posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d-%m-%Y" }}
    </li>
  {% endfor %}
</ul>