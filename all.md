---
layout: default
title: All
permalink: /all/
---


 
	{% for post in site.posts %}
	** {{post.title}} **
	{{post.content}}
	{% endfor %}


