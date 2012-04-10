---
layout: page
title: Projects
tagline: A list of all the projects I can post publicly
group: navigation
---
{% include JB/setup %}

<h2>All Projects</h2>
<ul>
	{% assign pages_list = site.pages %}
	{% assign group = 'project' %}
	{% include JB/pages_list %}
</ul>