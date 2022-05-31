---
title: "Chung-Yi Lin's homepage"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/images/bio-photo-cylin.jpg"
  caption: "DD"
  actions:
    - label: "About me"
      url: "/about/"
excerpt: ""

intro: 
  - excerpt: 'introduction. Centered with `type="center"`'
feature_row:
  - image_path: "/images/bio-photo-cylin.jpg"
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /images/bio-photo-cylin.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /images/bio-photo-cylin.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}