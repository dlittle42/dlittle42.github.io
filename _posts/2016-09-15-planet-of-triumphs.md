---
layout: post
title: Planet of Triumphs

images:

  - url: /images/portfolio620/ptrumps01.png
    alt: 
    title: 

  - url: /images/jekyll-logo.png
    alt: 
    title: 
---

A community celebrating and supporting all of the successes that members achieve at Planet Fitness.

- Creative Direction
- Information Architecture
- Prototyping
- User Experience

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}