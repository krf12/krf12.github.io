---
layout: post
title:  "Update to Ray Tracing and new idea for model"
date:   2015-02-26 19:38:00
categories: project raytracing design cloak refractionmaps
---

Since I last posted I have had my meeting with my supervisor. We have talked more about a slightly hacky way to get a model working
without ray tracing first. This could be useful for showing an invisibility cloak and having something to compare to when the raytracer works.

The idea is to create a solid sphere and to texture the outside of the sphere with the skybox map and then work out what distortions would happen
after refraction and create a new map from this to place on the outside of an inner sphere. On the inside on the inner sphere, there would
be the normal skybox map that relates to what a person would see from inside the sphere. This will require using some image processing to affect
the map and then replace the map on the sphere. I have currently created a structure that would work in sandbox and after apply the skybox texture
will move to the next version.

The ray tracer is still problematic. I am having a hard time understanding the algorithm enough to implement it and a lot of the algorithms I find
have barely any explanation. I am going to try to get the three.js raytracing renderer working again and if that fails then I'm going to have a look
at the C++ tutorial I found, work though it in C++ as I know the language and hopefully I will understand the algorithm enough to use it in webgl.
