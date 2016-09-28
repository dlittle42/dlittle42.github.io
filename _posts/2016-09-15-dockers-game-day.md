---
layout: post
title: Dockers Game Day
tags: [ad]
categories: [new, classic]
excerpt: Create or record your own Game Day Gram featuring your favorite team's talking pants.
images: [
	dockers.png, 
	dockers02.png,
	dockers03.png
]
media: none
---

- Creative Direction
- Interaction Design
- Front-end Development

{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

First Image Caption

{% assign image = page.images[1] %}
{% include image.html image=image %}

Second Image Caption

{% assign image = page.images[2] %}
{% include image.html image=image %}

Third Image Caption