---
layout: post
title: Planet of Triumphs
tags: [site, app]
categories: [new, classic]
excerpt: A community celebrating and supporting all of the successes that members achieve at Planet Fitness.
images: [
	ptrumps01.png, 
	ptrumps01.png
]

---

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