---
layout: page
permalink: /Work/
title: Work
---

{% for class in site.data.classes %}

<div class="project ">
<div class="thumbnail">
<a href="https://{{ class.url }}">
<span>
<h1>{{ class.title }}</h1>
</span>
</a>
</div>
</div>

{% endfor %}

