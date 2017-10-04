---
layout: post
title:  3D Mesh Morphing with Parameterization
date:   2017-10-01 20:00:00 -07:00
description: My blog on 3d mesh morphing with parameterization 
img: morph-cow-horse.png # Add image post (optional)
tags: [Blog, Research]
author: Max Jiang # Add name author (optional)
---

One of my first year projects to morph arbitrary genus-one mesh and mesh patches with same number of boundaries. Input meshes are parameterized using spherical parameterization (for genus-zero shapes) and uv-parameterization (for mesh patches), and warped to match feature points. 

<img src="{{site.baseurl}}/assets/img/cmcf.gif" align="left" height="200" width="300"/>
<img src="{{site.baseurl}}/assets/img/horse_cow_morph.gif" align="left" height="200" width="300"/>
<img src="{{site.baseurl}}/assets/img/head_morph_cropped.gif" height="200" width="100"/>
