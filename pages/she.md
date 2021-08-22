---
layout: page
title: She
---

<ul>
{% for page in site.pages %}
  {% if page.dir == "/posts/she/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>

感情咨询、意见反馈请 [留言💬](https://github.com/xuyilife/xuyilife.github.io/issues/new)