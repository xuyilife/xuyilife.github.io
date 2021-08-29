---
layout: page
title: 月记
---

# 2021

<ul>
{% for page in site.pages reverse %}
  {% if page.dir == "/posts/timeline/2021/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>

感情咨询、意见反馈请 [留言💬](https://github.com/xuyilife/xuyilife.github.io/issues/new)
