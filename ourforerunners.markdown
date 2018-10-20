---
layout: default
title: Our forerunners, in ideas and in technologies
resume: Science and knowledge is an activity that requires collaboration and persistense. Éditions Vodary Paris are only able to produce quality publishing material because we receive input of quality. Clever ideas and technology protocols are precious. We are grateful to everyone who contributes to form our intellectual environment, in disperse or direct manner, first of all to the next entities
keywords: Éditions Vodary Paris
author: 
---

# {{ page.title }}

 {{ page.resume }}:

<div class="gallery">
	{% for post in site.forerunners %}
  <div class="item">
  <a class="item-inner" href="http://{{ post.homepage }}">
				  {% include forerunners.html %}
			</a>
  </div>
{% endfor %}
	
</div>			
		
