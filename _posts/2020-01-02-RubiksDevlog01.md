---
layout: post
comments: true
title: "December 2019 Devlog #1:‌ Rubik's Cube Revisited"
date: "2020-01-02"
---

![Rubiks Cube](/assets/images/rubiks-0-0-2.png)

Hello everyone. It's mechasparrow again.

While I‌ was redeveloping my website, I‌ had to carefully pick what projects I‌ wanted to showcase. One of which was a Rubik's Cube Scrambler application that I‌ haven't worked on since 2016\.

I decided to showcase that one as I‌ thought it was simple and completed its purpose well.

However.

With my new knowledge and skill I‌'ve gained since then, I‌ wanted to give it another go. This time with new and improved functionality!

You can find a demo of the project over at [https://dah-rubiks.surge.sh/](https://dah-rubiks.surge.sh/)

## The Focus

There are two main things that I‌ wanted to add to the project.

1. An interactive Rubik's Cube simulation
2. An attractive UI

Last time, I‌ focused on generating scrambles for cubing since that was the main thing I was into at the time.

Nowadays, I'm really interested in using programming for 2D and 3D visualizations.

As such, I‌ thought it would be cool to add an interactive Rubik's Cube simulation to the project.

## ‌Added Features

So far, an interactive Rubik's cube simulation has been created. It can be scrambled and solved just like a regular Rubik's cube.

The current user interface is limited to a set of buttons below the Rubiks cube that rotates each individual layer.

You can also scramble and reset the cube with two buttons above the cube.

## Challenges

The main challenge was rotating parts of the cube.

Certain pieces of the cube (known as cubelets) may move around about several axes of rotation. An edge cubelet has two axes of rotation while a corner piece has three axes.

Given the constraint of the 3D library I‌ was using (THREE.JS)‌, I‌ had to do some fudging about to get the cubelets to be rotated about different axes.

## Future Features

For the future features of the project, I‌ want to add the following

1. Cube Timer
2. Make it more mobile-friendly
3. Add informational pages/resources
4. Better cube rendering/design

Currently, the web app is lacking design-wise. It is difficult to use on the phone, and It does not look like a Rubik's cube at first glance.

This can be remedied by adding borders around cubelets of the cube. Custom 3d models can also be utilized to give it an authentic feel.

For mobile responsiveness, I‌ can focus on testing it through a mobile viewport. Not only that, but I‌ can add buttons in 3-dimensional space. This may make the interface more intuitive for users.

## Conclusion

I'm really glad about how the project has turned out so far. It has served as a good project to build my understanding of [three.js](https://threejs.org/). This library provides a good framework for building WebGL applications on the web.

It's been a very exciting project to work on and I‌ can't wait to add more features in the following updates.

-- Navazhylau
