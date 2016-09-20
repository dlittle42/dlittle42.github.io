---
layout: post
title: Swarovski Rewards
tags: [app]
tags: [app]
categories: [new, classic]
excerpt: A loyalty rewards app for Swarovski helping customers track and earn points.
images: [
	swarovski.png, 
	swarovski02.gif
]
---

- Digital Strategy
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