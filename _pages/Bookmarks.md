---
layout: page_no_foot
permalink: /Bookmarks/
title: Bookmarks
---

{% for bookmark in site.data.bookmarks %}

<div class="bookmark">
<div class="thumbnail">
<a href="https://{{ bookmark.url }}">
<span>
<h4>{{ bookmark.title }}</h4>
</span>
</a>
</div>
</div>

{% endfor %}