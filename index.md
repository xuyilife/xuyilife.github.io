感情咨询、意见反馈请 [留言💬](https://github.com/xuyilife/xuyilife.github.io/issues/new)

## 我们👫

<ul>
{% for page in site.pages %}
  {% if page.dir == "/we/" %}
  {% assign title = page.name | split: ".md" | first %}
    <li> <a href="{{ page.url | relative_url }}">{{ title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>

## 她👧

<ul>
{% for page in site.pages %}
  {% if page.dir == "/she/" %}
  {% assign title = page.name | split: ".md" | first %}
    <li> <a href="{{ page.url | relative_url }}">{{ title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>

## 他👦

<ul>
{% for page in site.pages %}
  {% if page.dir == "/he/" %}
  {% assign title = page.name | split: ".md" | first %}
    <li> <a href="{{ page.url | relative_url }}">{{ title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>
