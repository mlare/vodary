---
layout: default
title: Our forerunners, in ideas and in technologies
---

# {{ page.title }}

<div class="gallery">
	{% for post in site.forerunners %}
  <div class="item">
  <a class="item-inner" href="http://{{ post.homepage }}">
				  {% include forerunners.html %}
			</a>
  </div>
{% endfor %}
	
</div>


<div class="item">
			
		
