---
layout: post
title: Big Air Santa
tags: [app]
categories: [new, classic]
excerpt: An iOS game using the Cocos2D game engine and gyroscope data to trigger snowboarding tricks.

images: [
	santa.png, 
	santa02.png
]
---

- Creative Direction
- Interaction Design
- Obj-C Development

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}