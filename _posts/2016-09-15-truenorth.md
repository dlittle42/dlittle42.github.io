---
layout: post
title: Truenorthinc.com
tags: [app]
categories: [new, classic]
excerpt: A custom responsive Wordpress theme built for advertising agency True North Inc.
images: [
	truenorth.png, 
	truenorth02.png
]

---

- Information Architecture
- User Experience
- Full Stack Development

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}