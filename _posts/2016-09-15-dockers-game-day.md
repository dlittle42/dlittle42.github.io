---
layout: post
title: Dockers Game Day
tags: [ad]

images:

  - url: /images/portfolio620/dockers.png
    alt: 
    title: 

  - url: /images/portfolio620/dockers02.png
    alt: 
    title: 
---

Create or record your own Game Day Gram featuring your favorite team's talking pants.

- Creative Direction
- Interaction Design
- Front-end Development

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}