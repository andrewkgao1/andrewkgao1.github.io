---
layout: post
title: "Tops, Gyroscopes, and Rigid Bodies"
date: 2021-11-13 10:40:53 +0800
categories: thoughts
---

Tops are very common toys for children. That is, at least before the internet was as prevalent as now. As a child, I was always fascinated by them. They would spin and spin, and start to tilt and draw circles until they eventually made contact with the ground and toppled over. It was very curious to me how the top could tilt but not fall. After learning about rigid bodies and their rotation, I can finally explain the physics behind them.

A simplified version of the answer is: a consequence of Newton's laws of motion is the law of angular momentum, which is similar to the law of momentum, stating that the change rate of angular momentum with respect to time is the torque applied. Angular momentum, simply speaking, is how much an object spins, and torque is a [cross product](https://en.m.wikipedia.org/wiki/Cross_product) between the force applied and the displacement between the reference point and the point the force is applied. A commonly used example is pushing a door. It is much easier to push a door from the doorknob than from right next to the hinges, which is due to a difference in position of the force applied and therefore a difference in torque. The direction of the angular momentum of a top is more or less aligned with its axis. When a top is tilted, the net force on the top is perpendicular to the ground. According to the rules of a cross product, the torque is perpendicular with the axis and parallel with the ground, thus causing the angular momentum of the top to change in direction, drawing a circle, but not in magnitude. This causes the top to wobble, and friction slows down the top until it falls.

The above answer is basically correct, but it glosses over many fine details that should not be ignored. To properly formulate this problem, we must consider the dynamics of a symmetrical rigid body. Using Euler's angles and Lagrangian mechanics, we can acquire a much more detailed analysis of the problem. The phenomena known as precession (the regular circular motion of the axis of the top) and nutation (the wobbling of the axis with respect to the circular "orbit" of precession) can be explained, as well as many more nuanced details. Goldsteins _Classical Mechanics_ provides an excellent in depth discussion, although there is much preliminary material to cover to understand it.

The properties of tops is utilized in a device called the gyroscope. It is often used in spacecraft and aircraft, and is useful as it maintains its orientation and angular velocity, and can be used similarly to a compass to guide direction. Its structure is basically a top inside of some framework, and works based on conservation of angular momentum.

<figure>
    <img src="/assets/2021-11-13/gyroscope.GIF"
         alt="Gyroscope">
    <figcaption>A gyroscope</figcaption>
</figure>

Simple gyroscopes are available to buy online at relatively cheap prices, and you can have much fun playing with its seemingly magical behavior. For example, while rotating, its axis can lie completely parallel with the ground while precessing. It is also incredibly stable, and can balance itself on a string while rotating. You will also find that if you hold it while it is spinning and attempt to rotate its axis, it will not comply and will try to move perpendicular to the direction you want it to move. Many more interesting and counterintuitive phenomena arise from the law of angular momentum, so go out and explore for yourself!