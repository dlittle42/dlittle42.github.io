---
layout: post
title: Pushing Daisies

images:

  - url: /images/portfolio620/pushingdaisies.png
    alt: 
    title: 

  - url: /images/portfolio620/pushingdaisies02.png
    alt: 
    title: 
---

This site asks "If you could bring back the dead for 60 seconds, who would it be and what would you ask?".  Answers are collected from ads all over the internet and displayed here in a browsable garden.

- Digital Strategy
- Creative Direction
- User Experience

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}