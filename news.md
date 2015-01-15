---
layout: post
title: News
permalink: /news/
---


<ul>
	  
	{% for post in site.posts %}
	    
    	<h1 class="post.title">{{ post.title }}  </h1> <h4> {{ post.date | | date_to_string }}</h4>

    	{{ post.content }}
	
		<br><br><hr> 

	{% endfor %}


</ul>