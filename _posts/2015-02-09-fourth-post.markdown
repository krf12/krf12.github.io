---
layout: post
title:  "Polarization Research and Refracting Sphere"
date:   2015-02-09 17:18:00
categories: project refraction polarization
---

I have created a more realistic skybox so that the transparency is more easily tested. I was finding that on a solid colour
skybox I was having trouble determining whether the the sphere was actually transparent or just a flat colour.

With the realistic skybox, I used a cube map from [Humus](http://www.humus.name/index.php?page=Textures&ID=50) which says that it has a creative commons license so I believe this is allowed to be used within my project. I have also created a refracting sphere by using three.js refraction map creation tools. I believe this is not how I will be creating the actual invisibility sphere, but it is a start to understanding what a transparent refracting sphere might look like.

I have also looked a little bit into polarization, including how polarization can be created via refraction. While it only occurs in one natural material - Iceland Spar crystal - this occurs because the light is split in two when refracted through the crystal. As this is something that might occur when light goes through the cloak, to split the light around the object in the middle, it might be that polarization is something that might need to be considered.

My next plan is to look at ray tracing or to look at how to create refraction without using a refraction map. This way I might be able to see how I might plug a formula into the refraction.

The current link to the latest version is : [Version One](http://krf12.github.io/RenderingInvisibility/pages/version1.html)
