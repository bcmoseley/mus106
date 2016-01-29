---
layout: archive
permalink: /
title:
---
<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
	{% assign date = post.date %}
	{% include post-detail.html %}
</div>


