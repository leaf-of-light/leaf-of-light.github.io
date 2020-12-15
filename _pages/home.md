---
layout: splash
permalink: /
hidden: true
# reference: https://mmistakes.github.io/minimal-mistakes/docs/layouts/#headers
header:
  overlay_image: /assets/images/home-header.jpg
  overlay_color: "#5e616c"
  overlay_filter: 0.05 # same as adding an opacity of 0.5 to a black background
  image_description: "Together we make the earth better."
  caption: "[building your own website](/building-website/)"
  actions:
    - label: "了解更多"
      url: "/about/"
excerpt: >
  Welcome to Leaf of Light<br />
  <small>Together, We make the earth better.</small>
# reference: https://mmistakes.github.io/minimal-mistakes/docs/helpers/#feature-row
feature_row:
  - image_path: /assets/images/home-feature-lifes.jpg
    alt: "地球上的生命"
    title: "地球上的生命"
    excerpt: "在地球上美丽的生命"
    url: "/lifes-on-the-earth/"
    btn_class: "btn--inverse"
    btn_label: "详细信息"
  - image_path: /assets/images/home-feature-environment.jpg
    alt: "我们的环境"
    title: "我们的环境"
    excerpt: "地球当前的环境"
    url: "/environment/"
    btn_class: "btn--inverse"
    btn_label: "详细信息"
  - image_path: /assets/images/home-feature-actions.jpg
    alt: "我能做什么"
    title: "我能做什么"
    excerpt: "日常生活中我能做什么"
    url: "/actions/"
    btn_class: "btn--inverse"
    btn_label: "详细信息"
---

{% include feature_row %}
