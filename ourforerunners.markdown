---
layout: default
title: Our forerunners, in ideas and technology — Éditions Vodary, publisher in Paris
---

<div class="gallery">
	{% for post in site.pages %}
	        {% if post.layout == "forerunner" %}
			post.title
		{% endif %}
		<div class="item">
			<a class="item-inner" href="{{ post.url }}">
				  {% include forerunners.html %}
			</a>
		</div>
	{% endfor %}
</div>


