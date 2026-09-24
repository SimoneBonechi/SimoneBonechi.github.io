---
layout: archive
title: "Downloads"
permalink: /downloads/
author_profile: true
---

{% include base_path %}

## Text Segmentation Annotations
{% for post in site.downloads_text %}
  {% include archive-single.html %}
{% endfor %}

## Skin Lesion Segmentation Annotations
{% for post in site.downloads_skin_lesion %}
  {% include archive-single.html %}
{% endfor %}
