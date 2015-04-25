---
layout: post
title:  "Finished Coding!"
date:   2015-04-25 17:57:00
categories: project cloak documentation
---

My coding is pretty much finished now and that is the reason for the lack of project blogs. Had a pretty rough couple of weeks where a firefox update
had broken my project and I was unaware this was the cause for at least a week and a half. Also some issues with stress getting to me as well :/

I have now got 6 separate models that have the ability to show from a single and mutliple viewpoints, chromatic and normal invisibility. There is one
line showing one path, however it cannot have a line width above one due to rendering issues with browsers being unable to work with native opengl.
I was planning to change this to be a pipe but I am unsure if I will have time to do so as it does not seem to be a simple task. I was hoping to put all
the models into one model but three.js does not allow for dynamic geometry changes so I was unable to find a solution to changing between a sphere and a
cylinder and a cone.

One other problem I have encountered is that the cone path is not working as expected. I have attempted to find a surface normal and work from there but
it does seem to work as expected. I am unsure if this is to do with how I am finding future surface normals/intersections or perhaps the refraction does
not work as well for a conical cloak, which is against what the paper I was reading suggested. I suspect it is simply the maths I am using is too simple
a model and it would be better to have taken the structure of the cloak and therefore the permittivity and permeability tensors into account.

These are all things that I will write into my report. Links to my current models can be found on [my home page](http://krf12.github.io/RenderingInvisibility/)
