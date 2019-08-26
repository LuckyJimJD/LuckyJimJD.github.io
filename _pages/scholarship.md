---
layout: page
permalink: /scholarship/
title: Scholarship
---
<!-- Recent Publications -->
### Recent Publications
<ul>
{% for publication in site.data.publications %}
<li><a href="https://luckyjimjd.github.io/assets/pdf/{{ publication.pdf }}" target="_blank">{{ publication.title }}</a>, {{ publication.volume }} {{ publication.journal }} {{ publication.page }} ({{ publication.date }})</li>
{% endfor %}
</ul>

<!-- Work in Progress -->
### Work in Progress
<ul>
{% for project in site.data.projects %}
<li>
<a href="{{ project.osf }}">{{ project.title }}</a>
</li>
{% endfor %}
</ul>



