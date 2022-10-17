---
layout: default
title: Home
permalink: /
nav_order: 1
---

# Groton Bible Chapel Tech Help Documents

Welcome to the GBC Tech Help Docs page. Use the menu on the left side (or top right if on mobile) to navigate the sections/pages. Please note this is to help as a reminder of how to do things and ***does not*** replace in-person training. If you need to be trained to run tech please reach out to Zachary for assistance.

## General
This section covers topics not specific to any area or location such as downloading a YouTube video.
<ul>
{% for page in site.pages %}
  {% if page.parent == 'General' %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

## Basic Guides
This has a basic guide and troubleshooting for working within certain rooms.

## Media, Sound, Lighting, Video
This section is for the more advanced topics that the scheduled tech team would need.

## Issues/Questions
If you have any issues and/or questions please reach out to Zachary for assistance.
