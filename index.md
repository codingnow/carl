---
layout: page
---
{% include JB/setup %}


##My list ---

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; </li>
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
<!--<div id="blog_index">
	<div class="posts">
	   {% for post in site.posts %}
	   <div class="post_item">
		 <div class="date">{{ post.date | date_to_string }}</div> 
	     <div class="post_title"><a href="{{ BASE_PATH }}{{ post.url }}"> {{ post.title }}</a></div>
	   </div>			<!-- \post_item -->
	   {% endfor %}
	</div>			<!-- \posts -->
</div> -->



