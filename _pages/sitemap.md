---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site.

<h2>Pages</h2>
{% for post in {/_pages/about.html, /_pages/cv.html} %}
  {% include archive-single.html %}
{% endfor %}
