---
layout: post
title: Werewolf Yourself
tags: [app]
categories: [new, classic]
excerpt: A Facebook application for ABC Family which allowed you to make your picture into a werewolf and send to your friends.
images: [
	werewolf.png, 
	werewolf02.png
]

---

- Creative Direction
- User Experience
- Flash Development
- Facebook Integration

Post body begin, and first image not in excerpt
{% assign image = page.images[0] %} <-- first element of the array is zero
{% include image.html image=image %}

Some more text blah !
{% assign image = page.images[1] %}
{% include image.html image=image %}