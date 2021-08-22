---
layout: page
title: HE
---

<ul>
{% for page in site.pages %}
  {% if page.dir == "/posts/he/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>
