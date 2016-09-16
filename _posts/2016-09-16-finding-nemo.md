---
layout: post
title: Finding Nemo
tags: [ad]

images:

  - url: /images/portfolio620/nemo.png
    alt: 
    title: 

  - url: /images/portfolio620/nemo02.png
    alt: 
    title: 
---

An early synchronized roadbloack ad on Yahoo.com for the DVD release of Finding Nemo.

- Creative Direction
- Interaction Design
- Flash Development

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}