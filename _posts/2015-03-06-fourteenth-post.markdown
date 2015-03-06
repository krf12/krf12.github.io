---
layout: post
title:  "Update for Models - Sphere and Cylinder"
date:   2015-03-06 19:38:00
categories: project cloak refractionmaps
---

I have created 4 models, two based on a shell structure and two based on a solid structure. Two of them are cylinder based and two of them are sphere based.
I will include links at the end of this post.

I have had to use the first half of the calculations for all of the models, as it would appear that anything that is out of the range of
0-1, as a certain amount of the ratios/vectors would have been, it reduced it all to 0 vectors. This apparently happens
when the ratio is that of moving from a less dense to a denser material, which is what would be happening on the second half of the sphere.
I am, however, pleased with the results and will now have to move forward to either finding a way around the 0 vector problem or ray-tracing.

My sandbox for the first model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/solidsphere.html)
My sandbox for the second model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/shellsphere.html)
My sandbox for the third model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/solidcylinder.html)
My sandbox for the fourth model can be found here : [Sandbox](http://krf12.github.io/RenderingInvisibility/pages/shellcylinder.html)
