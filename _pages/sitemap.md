---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

This page provides a complete index of the website.

## Main Pages

- [Home]({{ base_path }}/)
- [Research]({{ base_path }}/research/)
- [Publications]({{ base_path }}/publications/)
- [Teaching]({{ base_path }}/teaching/)
- [Awards & Honors]({{ base_path }}/award/)
- [Curriculum Vitae]({{ base_path }}/cv/)
- [Contact]({{ base_path }}/contact/)

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Teaching

{% for post in site.teaching %}
  {% include archive-single.html %}
{% endfor %}

## Portfolio

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

## Blog Posts

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
