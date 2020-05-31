---
layout: default
title: Members
description: 데이터리안 멤버를 소개합니다
main: true
project-header: true
header-img: img/about.jpg
---

<ul class="catalogue">
{% assign sorted = site.pages | sort: 'order' | reverse %}
{% for page in sorted %}
{% if page.member == true %}
{% include member-list.html %}
{% endif %}
{% endfor %}

</ul>