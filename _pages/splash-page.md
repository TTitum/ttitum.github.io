---
title: "Splash Page"
layout: splash
permalink: /splash-page/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/vlts-colors-unsplash.jpg
  actions:
    - label: "Buy Code & Deposit"
      url: "https://github.com/mmistakes/minimal-mistakes/"
    - label: "Return Code & Withdraw"
      url: "/news/index.html"
    - label: "Check Code Status"
      url: "/contact/index.html"  
      caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."

{% if page.header.actions %}
  <p>
  {% for action in page.header.actions %}
    <a href="{{ action.url }}" class="btn btn--light-outline btn--large">{{ action.label }}</a>
  {% endfor %}
{% endif %}
---

