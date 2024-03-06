---
layout: post
title: TEMPLATE
tags:
  - ["template"]
sticky: false
hidden: false
---

Here's how to link to an external site:
- [Reddit](https://reddit.com)
- [Airbag](https://airbagindustries.com)

Here's how to embed an image in a blog post:

![bend_or]({{ "/assets/img/blog/2018-12-17-mtb/bend_or.jpg" | relative_url }}){:width="100%"}
*Our happy place in Bend, OR*


Here's a second way to embed an image:
{% include image.html url="/assets/img/blog/2018-12-17-mtb/bend_or.jpg" description="Bend, OR" %}


Here's how to embed a YouTube video:
{% include youtube.html id='z13ogR7GSpA' caption="Audi at Spa" %}


Here's how to link to a different post:
[streaks]({{ site.baseurl }}{% post_url 2023-01-15-streaks %})