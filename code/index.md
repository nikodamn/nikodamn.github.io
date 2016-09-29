---
layout: archive
title: "Check out my trips: "
date: 
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
---
<p>{{ site.time  }}</p>

<h2>Archive.</h2>
{% for post in site.posts %}
<h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
<p><small>{{ post.date | date: "%B %e, %Y" }}</small></p>
<p>Categories:</p>
	{% for cat in post.categories %}
		{{ cat }}
	{% endfor %}
{% endfor %}
