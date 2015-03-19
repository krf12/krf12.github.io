---
layout: post
title:  "Update for Models - Refraction Problems"
date:   2015-03-16 17:49:00
categories: project cloak refractionmaps
---

As mentioned in the previous post, I was toying between going on with ray tracing or finding a way around the 0 vector problem. I have decided
to continue with the 0 vector problem as this will provide me a good set of models to test and if it all goes well, I will be able to look at
ray tracing.

I have removed the clamping from the refract method, and this has removed some of the problems I was having, I have also begun using the refraction
indexes properly, as I had been treating them as ratios due to a misunderstanding of the paper. I am still encountering issues on the back half of the
sphere and the lack of debugging tools that print data from GLSL is blocking my progress. I am now looking at either changing the maths using something
close to the ray tracing method and seeing if this is something that would work, or I am looking at doing some form of debugging using the fragment shader.

I have my mid-project demo tomorrow, but I feel confident that I can explain my project and that I am currently on track for my project. I am also looking at
creating a cut away model that will show the gradual changes. I am currently deciding whether to this based on the solid or shell strucutre. If I choose the
solid structure, I will have to created a doughnut shape to account for the gap in between.

My sandbox for the first model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/solidsphere.html)
My sandbox for the second model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/shellsphere.html)
My sandbox for the third model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/solidcylinder.html)
My sandbox for the fourth model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/shellcylinder.html)
My sandbox for the fifth model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/halfspheress.html)
