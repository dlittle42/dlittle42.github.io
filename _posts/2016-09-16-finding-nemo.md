---
layout: post
title: Finding Nemo
tags: [ad]
tags: [app]
categories: [new, classic]
excerpt: An early synchronized roadbloack ad on Yahoo.com for the DVD release of Finding Nemo.
images: [
	nemo.png, 
	nemo02.png,
	nemo.gif
]
media: http://supercomputingmachine.com/work/nemo/
---

- Creative Direction
- Interaction Design
- Flash Development

{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

First Image Caption

{% assign image = page.images[1] %}
{% include image.html image=image %}

Second Image Caption

{% assign image = page.images[2] %}
{% include image.html image=image %}

Third Image Caption