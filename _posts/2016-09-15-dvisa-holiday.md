---
layout: post
title: Disney Visa Holiday Favorites

images:

  - url: /images/portfolio620/dvisa-holiday.png
    alt: 
    title: 

  - url: /images/portfolio620/dvisa-holiday02.png
    alt: 
    title: 
---

As a showcase of all of the rewards the Disney Visa Card has to offer, this site allowed you to search rewards and create a holiday wish list.

- Creative Direction
- User Experience
- Front-end Development

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}