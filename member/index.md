---
layout: default
work: true
main: true
title: Members
description: 데이터리안 멤버를 소개합니다
project-header: true
header-img: img/about.jpg
---

<ul class="catalogue">
{% assign sorted = site.pages | sort: 'order' | reverse %}
{% for page in sorted %}
{% if page.member == true %}
aaaaaa
{% include member-list.html %}
{% endif %}
{% endfor %}

</ul>