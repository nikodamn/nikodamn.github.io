---
layout: media
permalink: /
title: "Ostatnie wpisy: "
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->