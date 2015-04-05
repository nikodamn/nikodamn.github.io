---
layout: archive
permalink: /
title: "Ostatnie wpisy: "
---

<div class="tiles">
{% for post in site.posts %}

{% if page.categories %}

	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->