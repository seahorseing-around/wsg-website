---
title: "12/14th Westside Scout Group"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/beach.jpg
  actions:
    - label: "Join Us!"
      url: "/join"
  caption: "Scout section at Summer camp on the Isle of Wight"
excerpt: {{site.description}}
intro: 
  - excerpt: "{{site.description}}"
feature_row:
  - image_path: assets/images/beavers.jpg
    alt: "Beaver Section"
    title: "Beavers"
    excerpt: "6-8 yrs"
    url: "/beavers"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/mud-swing.jpg
    #image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "Cub Scouts"
    title: "Cubs"
    excerpt: "8-10 yrs"
    url: "/cubs"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/surf.jpg
    #image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "Scouts"
    title: "Scouts"
    excerpt: "10-14 yrs"
    url: "/scouts"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}