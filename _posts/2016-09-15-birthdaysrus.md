---
layout: post
title: Birthdays &ldquo;R&rdquo; Us

images:

  - url: /images/portfolio620/tru.png
    alt: 
    title: 

  - url: /images/portfolio620/tru02.png
    alt: 
    title: 
---

An interactive playland for kids and informational website for parents promoting Geoffrey's Birthday Club at Toys &ldquo;R&rdquo; Us.

- Creative Direction
- User Experience
- Flash Development
- Animation

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}