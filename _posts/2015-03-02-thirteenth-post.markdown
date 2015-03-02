---
layout: post
title:  "Update for Model"
date:   2015-02-26 19:38:00
categories: project cloak refractionmaps
---

I have managed to create a correct effect on one half of a sphere in that it seems to follow a reasonable distortion of
the refraction map. I used a fresnel shader and adapted it to restrict it to refract, not reflecting, and adding my calculations for the refraction vector at each stage. I am having some trouble when the refraction is meant to turn back
towards the outside of the sphere. Instead of a similar distortion to the other side, I am getting barely any distortion at all.

I will have to work through this tomorrow and see if there is perhaps something wrong with my calculations. I am also
thinking of doing this with the shell structure. This might help me figure out the refractions as I can do it step by step.

My sandbox for the first model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/sandbox.html)
