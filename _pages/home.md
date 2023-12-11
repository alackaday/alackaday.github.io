---
title: "Alackaday Productions"
layout: splash
permalink: /
redirect_from:
  - /home/
date: 2023-12-10T00:00:00-00:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/bio-photo.jpg
  actions:
    - label: "Learn More"
      url: "/about/"
  caption: "Photo credit: Edward Dearden"
excerpt: "We make silly games and films"
intro:
  - excerpt: |
      We make silly games and films.
      Have a look around and enjoy your stay!
feature_row:
  - image_path: /assets/images/bio-photo.jpg
    alt: "placeholder image 1"
    excerpt: "<br/>Here be films"
    url: "/films"
    btn_label: "Films"
    btn_class: "btn--primary"
  - image_path: /assets/images/bio-photo.jpg
    alt: "placeholder image 2"
    excerpt: "<br/>Here be games."
    url: "/games"
    btn_label: "Games"
    btn_class: "btn--primary"
  - image_path: /assets/images/bio-photo.jpg
    excerpt: "<br/>Here's some stuff I've done that's not research"
    url: "/blog"
    btn_label: "Blog"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
