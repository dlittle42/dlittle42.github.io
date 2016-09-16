---
layout: post
title: Portfolio Builder
tags: [app]

images:

  - url: /images/portfolio620/portfoliobuilder.png
    alt: 
    title: 

  - url: /images/portfolio620/portfoliobuilder02.gif
    alt: 
    title: 
---

A web application allowing anyone at True North Inc to find past projects in the portfolio database and easily assemble a showcase site for presentations.

- Creative Direction
- User Experience
- Information Architecture

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}