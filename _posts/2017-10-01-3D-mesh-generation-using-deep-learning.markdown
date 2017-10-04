---
layout: post
title:  3D Mesh Generation with Deep Learning
date:   2017-10-01 20:00:00 -07:00
description: My blog on 3d mesh generation with deep learning
img: furniture.png # Add image post (optional)
tags: [Blog, Research]
author: Max Jiang # Add name author (optional)
---
This is a recent project that originated as a class project for Berkeley's CS280: Computer Vision course. The idea is to use neural networks, more precisely 3D convolutional neural network paired with GAN (generative adversarial network) to generate realistic 3D mesh-based object.

Here's a paper on this research:
[ArXiv Link](https://arxiv.org/abs/1709.07581)

<div class='modelo-wrapper'> <iframe src="https://app.modelo.io/embedded/dTGFg8TaYo?viewport=false&autoplay=false" width="640" height="360" frameborder="0" mozallowfullscreen webkitallowfullscreen allowfullscreen ></iframe> <p style="font-size: 13px; font-weight: bold; margin: 10px 10px 10px 0; color: #666666;"> car_sample_15 <span style="font-weight: normal;">By</span> Max Jiang <a href="http://www.modelo.io?utm_source=embed&utm_medium=embedfooter&utm_campaign=model%20embed%20footer" target="_blank" style="display: inline-block; margin-left: 6px; padding-left: 8px; border-left: 1px solid #e2e2e2; color: #e8776f; cursor: pointer; text-decoration: none;">Modelo »</a> </p> </div>

Hallucinating 3D objects has been done in the recent past, with vary degrees of success using binary voxels. However I am more interested in developing a mesh-based framework that creates mesh-based objects. Mesh based objects are nice, as it is the default data structure used in computer graphics, even scientific computational applications. The trick is to use signed distance function (SDF) based voxel representation instead of binary voxels. Of course, there's some more "magic" with detail enhancement, which can be found the the above paper.

Merrying object generators with mesh-based graphics rendering algorithms creates pure magic. Realistic yet artificial scenes:
![Rendered furnitures (chairs and tables)](assets/img/furniture-render.gif)
