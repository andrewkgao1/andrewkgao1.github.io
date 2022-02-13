---
layout: post
title: "Shapes of Shadows and Conic Sections"
date: 2021-12-24 21:02:39 +0800
categories: thoughts
---

<figure>
    <img src="/assets/2021-12-24/the_shadow.HEIC"
         alt="the_shadow">
    <figcaption>The shadow created by the lamp</figcaption>
</figure>

My house has a lamp that has lost its lampshade (and is slightly tilted), and the remaining framework casts a shadow on the wall next to it. The natural question is, what shape is the curve?

Interestingly, the answer is quite simple, and it is a hyperbola curve. A general expression for hyperbolae is $$ \frac{x^2}{a^2} - \frac{y^2}{b^2} = 1 $$. The shape looks similar, but how can we get from the shape on the wall to this expression? The answer lies in conic sections. Discovered as early as 200 BC, conic sections are the curves you can get when you intersect the surface of two mirrored cones that stretch to infinity with a plane. 
<figure>
    <img src="/assets/2021-12-24/conic-sections.HEIC"
         alt="conic sections">
    <figcaption>Diagram on conic sections, JensVyff, ![CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en)</figcaption>
</figure>
The curves you can get are parabolae, hyperbolae, and ellipses, circles being a special case of ellipses. To get a hyperbola, you have to arrange the plane as in panel 4 in the graph. To simplify our argument, I will only consider a plane that is parallel with the axis of the cone, as more complicated cases are essentially the same. The cone surface is given by $$ y^2+z^2 = \frac{b^2}{a^2}x^2 $$, and the plane by $$z=a$$. The intersection is thus $$ \frac{x^2}{a^2} - \frac{y^2}{b^2} = 1 $$. 

As the last step, it is straightforward to show that the production of the shadow is identical to the creation of a hyperbola. For a point light source at the center of the lamp, the shape of lines passing through that light source and a point on the framework creates a cone. Clearly the wall intersects this cone as the plane intersects the cone in panel 4, and since light travels in straight lines (at least here it does), the shadow created is a hyperbola. Well, it's actually a hyperbola surrounded by other non-hyperbola curves to create a shadow with area, but that is a good enough approximation.