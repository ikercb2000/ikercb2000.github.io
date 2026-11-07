---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include build-version.html %}

Explore the main sections of this website.

<ul>
  <li><a href="{{ '/' | relative_url }}?v={{ build_version }}">Home</a></li>
  {% for link in site.data.navigation.main %}
  <li>
    <a href="{% if link.url contains 'http' %}{{ link.url }}{% else %}{{ link.url | relative_url }}?v={{ build_version }}{% endif %}">{{ link.title | escape }}</a>
    {% if link.url == '/research/' %}
    <ul>
      <li><a href="{{ '/research/' | relative_url }}?v={{ build_version }}#publications">Publications</a></li>
      <li><a href="{{ '/research/' | relative_url }}?v={{ build_version }}#talks">Talks &amp; presentations</a></li>
      <li><a href="{{ '/research/' | relative_url }}?v={{ build_version }}#other-projects">Other projects</a></li>
    </ul>
    {% endif %}
  </li>
  {% endfor %}
</ul>
