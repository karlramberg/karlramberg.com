---
layout: default
title: programming.
category: programming
permalink: /programming/
---

{% raw %}
{% for post in site.posts %}
  {% if post.categories contains 'programming' %}
	<div class="post">
		<h3 class="title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
	</div>
  {% endif %}
{% endfor %}
{% endraw %}
