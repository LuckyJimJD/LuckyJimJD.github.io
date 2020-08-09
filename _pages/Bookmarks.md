---
layout: page
permalink: /Bookmarks/
title: Bookmarks
---

{% for bookmark in site.data.bookmarks %}

	<div class="bookmarks">
		<div class="thumbnail">
			<a href="https://{{ bookmark.url }}">
			<span>
			<h1>{{ bookmark.title }}</h1>
			</span>
			</a>
		</div>
	</div>

{% endfor %}


