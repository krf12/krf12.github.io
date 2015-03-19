---
layout: post
title:  "Update for Models - Problem Solved! Maybe..."
date:   2015-03-19 19:39:00
categories: project cloak refractionmaps
---

I have found the problem that was causing the refraction to not completely work! Because I was normalizing the vectors, I was losing
information each time I normalized the vector. However this is making me think that maybe by calculation is off because I believe the
papers suggest that the vectors need to be normalized. I will have to recheck, but otherwise it looks like I have made some progress!

I am extremely interested in making sure I can get the raytracing done now after my mid-project demo as my second marker made a good point
about the results being easier to test if I can follow the path of the ray with my eyes. I might still be able to with my current models
but this is something I am looking into. I have begun doing my test specification so I can think about the kind of tests I will do on a
raytracing model and what kinds of tests I can do on a distorted texture map model.
