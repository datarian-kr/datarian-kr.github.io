---
layout: default
title: {% member.name %}
description: {% member.name%}의 모든 글
main: true
project-header: false
header-img:
---

<ul class="catalogue">
{% assign sorted = site.pages | sort: 'order' | reverse %}
{% for page in sorted %}
{% if page.blog == true %}
	{% if page.author == member.name %}
		{% include post-list.html %}
	{% endif %}
{% endif %}
{% endfor %}
</ul>
