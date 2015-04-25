---
layout: post
title:  "Update for Models and Test Specification"
date:   2015-04-08 13:48:00
categories: project cloak documentation
---

I have completed the test specification and have decided to not do raytracing for rendering as I do not have the time
available to complete it. Instead I will trace the path of the rays through the model and render them as lines that I can follow.
This will make my testing a lot easier. I will then look at doing some extra models - shapes and effects. I will need to think of what
effects I can create and then write up tests for them in the test specification.

I am sad that I have been unable to achieve the raytracing rendering but that maths involved has been tricky to get right. The normalizing
of the vectors was a problem as the vectors are already normalized after going through the refraction equation according to Snell's law. This meant that removing the normalization apart from the the first run through was correct. However I may need to change the first equation further. According to another paper I read, there is a different equation that is used for the air to cloak change. I have tested this in my Java program and it seems to work but I will implement it in the models to see what it looks like.

I have also updated the models so that they can change between chromatic and invisible using dat.gui. I am happy with my progress over Easter even though I have been unwell and will use the next couple of weeks to finalize the implementation and begin testing.
