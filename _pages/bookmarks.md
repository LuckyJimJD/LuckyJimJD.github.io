---
layout: page
permalink: /bookmarks/
title: Bookmarks

---


{% for bookmark in site.data.bookmarks %}

<div class="project ">
<div class="thumbnail">
<a href="{{ site.url }}/{{ bookmark.url }}">
<span>
<h1>{{ bookmark.title }}</h1>
</span>
</a>
</div>
</div>

{% endfor %}



