---
layout: post
title: Disney Visa Card Website
tags: [site]
categories: [new, classic]
excerpt: A full responsive redesign built with Wordpress, featuring behavior-based content tailored to cardmember profiles.
images: [
	dvisa.png, 
	dvisa02.png
]

---
 

- User Experience
- Information Architecture
- Wordpress Development
- Order Fulfillment API Integration
- User-Generated Content Submission

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}