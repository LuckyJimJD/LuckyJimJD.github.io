---
layout: page
permalink: /teaching/
title: Teaching
---

{% for course in site.data.courses %}

<div class="project ">
<div class="thumbnail">
<a href="{{ site.url }}/{{ course.url }}">
<img class="thumbnail" src="{{ site.baseurl }}/assets/img/teaching/{{ course.thumbnail }}" alt="{{ course.title }}" size="100%" />
<span>
<h1>{{ course.title }}</h1>
</span>
</a>
</div>
</div>

{% endfor %}

