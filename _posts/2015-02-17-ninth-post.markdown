---
layout: post
title:  "Ray Tracing progress and Design Spec"
date:   2015-02-17 18:34:00
categories: project raytracing design
---

I have two things to discuss in the post today, my progress with ray tracing and the beginnings of my design specfication.

I had found a good three.js ray tracing renderer example yesterday and attempted to integrate it with my current project.
Unfortunately, under the duress of the apparent intensiveness of the model I had built so far, the ray tracer proceeded to
crash my graphics driver....

Thus I have reverted those changes made and am planning on looking into building a simple ray tracer, one that doesn't deal
with reflection and refraction at first, and build from there. I have found a good starting point in a WebGL book I found on Primo
and am intending to use the example provided and update it to use three.js. I have looked into the refract function of the shader language
and as far as I can tell, it is used to return a vector based on two vectors and the refraction ratio. This is probably used in building a
ray tracer in the shader code, or it could be used to work out the refraction of the materials. I will have to look into this a little more.

Today I have chosen to start working on my first promised deliverable : The design specification. As I have been working on research and
prototyping, it seemed like a good time to start working on a formal design. So far I have written the introfucation and the assumptions and
considerations I have needed to make for this project.

I shall continue working on both the above tomorrow and am eager to show off my project on the 3rd March to the group, as I am hoping it will
give me some confidence that I am working towards the right goal.
