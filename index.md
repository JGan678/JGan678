---
title: Home
---

## Index

<ul>
  {% for page in site.pages %}
  {% if page.title %}
  <li>
    <a href="{{ page.url }}">{{ page.title }}</a>
  </li>
  {% endif %}
  {% endfor %}
</ul>

## Links

- Email  
  <jgan@xii.tv>

- Twitter  
  <https://twitter.com/jgan678>

- GitHub  
  <https://github.com/jgan678>
