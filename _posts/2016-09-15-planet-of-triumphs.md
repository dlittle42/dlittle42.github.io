---
layout: post
title: Planet of Triumphs
tags: [site, app]
categories: [new, classic]
excerpt: A community celebrating and supporting all of the successes that members achieve at Planet Fitness.
images: [
	ptrumps02.png, 
	ptrumps03.png,
	ptrumps04.png,
	ptrumps05.png
]
media: https:/planetoftriumphs.com
---

- Creative Direction
- Information Architecture
- Prototyping
- User Experience

 {% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

First Image Caption

{% assign image = page.images[1] %}
{% include image.html image=image %}

Second Image Caption

{% assign image = page.images[2] %}
{% include image.html image=image %}

Third Image Caption

{% assign image = page.images[3] %}
{% include image.html image=image %}

Fourth Image Caption