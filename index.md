---
layout: default
title: Home
permalink: /
nav_order: 1
---

# Groton Bible Chapel Tech Help Documents

Welcome to the GBC Tech Help Docs page. Use the menu on the left side (or top right if on mobile) to navigate the sections/pages. Please note this is to help as a reminder of how to do things and ***does not*** replace in-person training. If you need to be trained to run tech please reach out to Zachary for assistance.

## General
This section covers topics not specific to any area or location.
<ul>
{% for page in site.pages %}
  {% if page.parent == 'General' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

## Basic Guides
This has a basic guide for working within certain rooms.
<ul>
{% for page in site.pages %}
  {% if page.parent == 'Basic Guides' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

## Troubleshooting
This has common issues and fixes for them
<ul>
{% for page in site.pages %}
  {% if page.parent == 'Troubleshooting' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

## Media, Sound, Lighting, Video
This section is for the more advanced topics.
#### Media
<ul>
{% for page in site.pages %}
  {% if page.parent == 'Media' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
#### Sound
<ul>
{% for page in site.pages %}
  {% if page.parent == 'Sound' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
#### Lighting
<ul>
{% for page in site.pages %}
  {% if page.parent == 'Lighting' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
#### Video
<ul>
{% for page in site.pages %}
  {% if page.parent == 'Video' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
#### Tech Team
<ul>
{% for page in site.pages %}
  {% if page.parent == 'Tech Team' %}
    <li><a href="/tech-help-docs/{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

## Issues/Questions
If you have any issues and/or questions please reach out to Zachary for assistance.
