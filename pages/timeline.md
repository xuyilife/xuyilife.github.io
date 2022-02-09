---
layout: page
title: 月记
---

# 2022

<ul>
{% assign pages = site.pages | reverse %}
{% for page in pages %}
  {% if page.dir == "/posts/timeline/2022/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>

# 2021

<ul>
{% assign pages = site.pages | reverse %}
{% for page in pages %}
  {% if page.dir == "/posts/timeline/2021/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>

感情咨询、意见反馈请 [留言💬](https://github.com/xuyilife/xuyilife.github.io/issues/new)
