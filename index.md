---
layout: page
---
{% include JB/setup %}


##My list ---


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date："%Y-%m-%d" }}</span> &raquo; </li>
<a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
  {% endfor %}
</ul>




’end‘


