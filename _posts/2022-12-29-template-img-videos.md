---
layout: post
title: TEMPLATE - images and videos
tags: ["template"]
sticky: false
hidden: false
---

Here's how to embed images and videos in a blog post.

![bend_or]({{ "/assets/img/blog/2018-12-17-mtb/bend_or.jpg" | relative_url }}){:width="70%"}
*Our happy place in Bend, OR*

A second way to do images...

{% include image.html url="/assets/img/blog/2018-12-17-mtb/bend_or.jpg" description="Bend, OR" %}

Here's how to embed a YouTube video

{% include youtube.html id='z13ogR7GSpA' caption="Audi at Spa" %}

Here's more text after the video link