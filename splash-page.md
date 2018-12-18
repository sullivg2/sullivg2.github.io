---
title: "Geoff Sullivan"
layout: home
permalink: /splash-page/
author_profile: true
header:
  overlay_filter: "0.6"
  overlay_image: assets/images/risq2.jpg
  actions:
  caption: #"Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "The Business of Technology & The Technology of Business"
feature_row:
  - image_path: assets/images/BROM-CB.jpg
    image_caption: #"Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 1"
    title: "About Geoff"
    excerpt: "Bio, work experience, & expertise"
    url: "https://geoffsullivan.net/about"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/BROMLEY-LTOWN.png
    alt: "placeholder image 2"
    title: "Advisory"
    excerpt: "Technoloy & go-to-market advisory services."
    url: "https://geoffsullivan.net/advisory"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/BROM-CB.jpg
    title: "Blog"
    excerpt: "Writings about the business of technology and the technology of business"
    url: "https://geoffsullivan.net/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row %}

<div class="archive">
  <h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

  {% for post in paginator.posts %}
      {% include archive-single.html %}
  {% endfor %}

  {% include paginator.html %}
</div>
