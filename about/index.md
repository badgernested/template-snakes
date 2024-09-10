---
layout: page
title: About
current: about
cover: 'assets/images/about.jpg'
---

{% if site.data.l10n.lang contains 'en' %}
	{% include_relative en/about.md %}
{% else %}
	{% include_relative fr/about.md %}
{% endif %} 