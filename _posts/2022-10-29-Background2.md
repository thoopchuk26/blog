---
layout: post
title:  "Background 2"
date:   2022-10-29 8:31:39 -0500
categories: lab update
---

Reasoning for not having the assignment is the exact same so I'll just jump into talking more about the project.

My next step after getting the render engine working efficiently, is to start procedurally
generating my block objects and start culling inside triangles to not be rendered because
that's exclusively a bad thing to do. Once I get that basic stuff done, I probably need to
setup some kind of chunk structure to hold chunks of block data in order to start doing culling at chunk distances
too far away to keep it running smoothly. I'll hope to get that stuff done by around middle of November, it shouldn't
be too hard conceptually but making it run smoothly is definitely something I have to keep in mind when building my project
out like this.

![model]({{site.baseurl}}/images/rotate.gif)
