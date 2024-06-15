---
title: Reeves
layout: about
permalink: /reeves.html
# include CollectionBuilder info at bottom
credits: false
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---


{%- assign items = site.data.architects -%}

{% for item in items %}
{% if item.architect contains "Reeves" %}

This is the page for {{ item.name }}.
He was born on {{ item.date }}.

{% endif %}
{% endfor %}
