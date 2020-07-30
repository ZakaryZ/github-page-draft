---
layout: archive
permalink: /blog/
title: "Blog Posts by Tags"
author_profile: true
header:
  teaser: /images/background0.JPG
  overlay_image: /images/background0.JPG
  overlay_filter: 0.5
---

{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
