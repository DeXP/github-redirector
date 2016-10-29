---
title: All Links
---
{% for static_file in site.pages %}
	<a href="{{ static_file.url }}">{{ static_file.url }}</a><br/>
{% endfor %}
