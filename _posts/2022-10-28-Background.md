---
layout: post
title:  "Background 1"
date:   2022-10-28 8:31:39 -0500
categories: lab update
---

First things first, the reason the background is so late is because I didn't have it done on Thursday, and I am
currently at an event out of state from Thursday to Monday, so I probably still won't have it done until
Tuesday at the latest. No worries though everything else is going pretty well.

Now to talk about my project progress a little bit. I've completely finished the 3d render engine
for my project. I can correctly import an obj file and a texture and render it onto the screen
in the correct place keeping all the transformations consistent and there is a first person
camera that is controlled by mouse movement. Now for the bad part, it seems to be extremely
inefficient at drawing to the screen, the current helper library I'm using (sdl2) to just get a screen
working and being able to draw to it seems to be very slow at scale of drawing individual pixels to
the screen, which means I'm going to import all of my sdl2 stuff into opengl because it seems to
be a lot more popular and efficient. Hopefully that doesn't take too long because I'm not using
sdl2 that much but I'll find out how much of a hassle this is soon.

![where we left off]({{site.baseurl}}/images/based.png)
