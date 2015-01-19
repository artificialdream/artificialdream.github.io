---
layout: post
title: News
permalink: /news/
---


<ul>
	  
	{% for post in site.posts %}

	    
    	<a href="{{ post.url }}"><h1 class="post.title">{{ post.title }}  </h1>read more</a> <h4> {{ post.date | | date_to_string }}</h4>

    	 <article>{{ post.excerpt }}</article> 
	
		<hr> 
		
	{% endfor %}


</ul>