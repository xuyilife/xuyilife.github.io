---
layout: page
title: SHE
---

<ul>
{% for page in site.pages %}
  {% if page.dir == "/posts/she/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>
