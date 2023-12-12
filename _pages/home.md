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
  overlay_image: assets/images/eddie-and-little-eddie-banner.jpg
  actions:
    - label: "Learn More"
      url: "/about/"
  #caption: "Photo credit: Eddie Dearden"
excerpt: "We make silly games and films"
intro:
  - excerpt: |
      We make films and games with a homemade feel.

      If you want to get in touch, [chuck us an email](/contact).
feature_row:
  - image_path: assets/images/samoa-joe-making.jpg
    alt: "photo of a stop-motion set"
    excerpt: "<br/>Here be films"
    url: "/films"
    btn_label: "Films"
    btn_class: "btn--primary"
  - image_path: assets/images/games.jpg
    alt: "photo of a commodore 64"
    excerpt: "<br/>Here be games."
    url: "/games"
    btn_label: "Games"
    btn_class: "btn--primary"
  - image_path: assets/images/little-eddie-letters.jpg
    alt: "photo of a puppet covered in letters"
    excerpt: "<br/>Here be blog posts"
    url: "/blog"
    btn_label: "Blog"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
