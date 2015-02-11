---
layout: post
title:  "Rereading Papers - Metamaterials (Unwell)"
date:   2015-02-11 16:14:00
categories: project papers
---

I will be covering one paper in this post.

The original paper given to me was D. Schurig, J. J. Mock, B. J. Justice, S. a Cummer, J. B. Pendry, a F. Starr, and D. R. Smith, “Metamaterial electromagnetic cloak at microwave frequencies.,” Science, vol. 314, no. 5801, pp. 977–980, 2006.

This paper describes a practical realization of an invisibility cloak. It was demonstrated using a copper cylinder hidden (not from visible light and therefore was visible to the naked eye) inside a cloak from a metamaterial, constructed using previous theories. It was designed to work over a band of microwave frequencies. It worked by decreasing scattering from the hidden object while also reducing its shadow. This meant it began to resemble empty space.

The metamaterials are designed using the theory of transformation optics, it is designed with the co-ordinate transformations wanted in mind. An electromagnetic cloak is designed to cloak an object from incident radiation. Maxwell's equations, which measure (something), are form-invariant to co-ordinate transformations so that only the permittivity tensor and the permeability tensor are affected by the transformation. There are two ways that invisibility could be achieved using Maxwell's equations and these are either making the cloak and object appear as if they were empty space, rely on the reduction of backscatter or make use of a resonance in which the properties of the cloaked object and the cloak itself must be carefully matched.

The cloak itself is 2D, which means that the measurements for the cloak I am attempting to simulate are going to be a little more difficult, as I have to take into account 3D co-ordiante transforms rather than 2D co-ordinate transforms. The paper contains a simple transform that could achieve something similar to what I am looking for, changing the radial co-ordinates and then using these transformed co-ordinates to discover the permittivity and permeability tensor components. These equations make up most of the paper that is of use to a simulation, as the rest of the paper appears to go into detail on the construction and testing of the material, which is perhaps too in depth for the kind of simulation I was aiming for.

I had hoped to cover a couple more papers today, but I am feeling a little too unwell. Hopefully tomorrow I will be able to look into more detail about the refraction in WebGL.
