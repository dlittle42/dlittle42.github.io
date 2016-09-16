---
layout: post
title: Testing images

images:

  - url: /images/first-post.png
    alt: Cypripedium Calceolum
    title: Cypripedium Calceolum

  - url: /images/jekyll-logo.png
    alt: Hello bumblebee !
    title: Hello bumblebee !
---

Intro here yo ! <-- THIS IS THE EXCERPT

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}