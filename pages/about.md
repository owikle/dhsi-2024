---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{%- assign items = site.data[site.metadata] -%}



{% include feature/jumbotron.html objectid="psychiana030" %} 

{% include feature/nav-menu.html sections="About Psychiana;About the Collection" %}

## About Psychiana

{% include feature/image.html objectid="psychiana008;psychiana040;psychiana036;psychiana032" width="75" %}

My demo collection

- one
- two
- three

## About the Collection

More information goes here!

{% include feature/image.html objectid="psychiana048" width="75" %}
