---
layout: archive
title: "Kartki z podróży: "
date: 
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
---

<div class="tiles">

{% for post in site.posts %}

{% if page.categories="Podróże" %}

	<a href="{{ post.url }}">
    <h2>{{ post.title }} &mdash; {{ post.date | date_to_string }}</h2>
  </a>
{% endfor %}


</div><!-- /.tiles -->