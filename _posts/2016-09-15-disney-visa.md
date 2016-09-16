---
layout: post
title: Disney Visa Card Website

images:

  - url: /images/portfolio620/dvisa.png
    alt: 
    title: 

  - url: /images/portfolio620/dvisa02.png
    alt: 
    title: 
---

A full responsive redesign built with Wordpress, featuring behavior-based content tailored to cardmember profiles. 

- User Experience
- Information Architecture
- Wordpress Development
- Order Fulfillment API Integration
- User-Generated Content Submission

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}