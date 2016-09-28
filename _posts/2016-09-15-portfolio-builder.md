---
layout: post
title: Portfolio Builder
tags: [app]
categories: [new, classic]
excerpt: A web application allowing anyone at True North Inc to find past projects in the portfolio database and easily assemble a showcase site for presentations.
images: [
	portfoliobuilder.png, 
	portfoliobuilder01.gif,
	portfolio02.png,
	portfoliobuilder.gif
]
media: https://vimeo.com/89986672
---

- Creative Direction
- User Experience
- Information Architecture

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