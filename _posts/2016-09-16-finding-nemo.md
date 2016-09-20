---
layout: post
title: Finding Nemo
tags: [ad]
tags: [app]
categories: [new, classic]
excerpt: An early synchronized roadbloack ad on Yahoo.com for the DVD release of Finding Nemo.
images: [
	nemo.png, 
	nemo02.png
]

---

- Creative Direction
- Interaction Design
- Flash Development

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}