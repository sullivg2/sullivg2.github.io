---
title: "Geoff Sullivan"
layout: splash
permalink: /splash-page/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_filter: "0.6"
  overlay_image: assets/images/risq2.jpg
  actions:
  caption: #"Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "The Business of Technology & The Technology of Business"
feature_row:
  - image_path: assets/images/geoff-cengn.png
    image_caption: #"Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 1"
    title: "About Geoff"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/BROMLEY-LTOWN.png
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/BROM-CB.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

{% include feature_row %}

<div class="{{ include.type | default: "list" }}__item">
  <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
    {% if post.header.image %}
      <div class="archive__item-teaser">
        {% img '{{ post.header.image }}' %}
      </div> 
