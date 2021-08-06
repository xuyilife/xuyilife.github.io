感情咨询、意见反馈请 [留言💬](https://github.com/xuyilife/xuyilife.github.io/issues/new)

## 我们👫

{% for page in site.pages %}
<ul>
  {% if page.dir == "/we/" %}
  {% assign title = page.name | split: ".md" | first %}
  <li> <a href="{{ page.url | relative_url }}">{{ title }}</a> </li>
  {% endif %}
</ul>
{% endfor %}

## 她👧

{% for page in site.pages %}
<ul>
  {% if page.dir == "/she/" %}
  {% assign title = page.name | split: ".md" | first %}
  <li> <a href="{{ page.url | relative_url }}">{{ title }}</a> </li>
  {% endif %}
</ul>
{% endfor %}

## 他👦

{% for page in site.pages %}
<ul>
  {% if page.dir == "/he/" %}
  {% assign title = page.name | split: ".md" | first %}
  <li> <a href="{{ page.url | relative_url }}">{{ title }}</a> </li>
  {% endif %}
</ul>
{% endfor %}
