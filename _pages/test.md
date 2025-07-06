---
layout: single
title: "Site Test"
permalink: /test/
---

# Site Navigation Test

This page is to test if Jekyll is working correctly.

## Navigation Links

- [Home](/)
- [About](/about/)
- [Research](/research/)
- [Projects](/projects/)
- [Publications](/publications/)
- [Contact](/contact/)

## Test Buttons

<a href="/research/" class="btn btn--primary">Go to Research</a>
<a href="/projects/" class="btn btn--success">Go to Projects</a>
<a href="/contact/" class="btn btn--info">Go to Contact</a>

## Site Variables

- Site Title: {{ site.title }}
- Site URL: {{ site.url }}
- Current Date: {{ site.time | date: "%Y-%m-%d" }}

## Pages List

{% for page in site.pages %}
- [{{ page.title }}]({{ page.url }})
{% endfor %}
