![xuyi](img/she.jpg)

{% assign posts_by_year = site.posts | group_by_exp:"post", "post.date | date: '%Y' " %}
{% for group in posts_by_year %}

<h3>{{ group.name }}</h3>
<ul>
  {% for post in group.items %}
    <li><div style="width:60px; float:left;">{{ post.date | date: "%b %-d" }}</div> <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
{% endfor %}
