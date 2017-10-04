---
layout: post
title:  3D Mesh Morphing with Parameterization
date:   2017-10-01 20:00:00 -07:00
description: My blog on 3d mesh morphing with parameterization 
img: morph\_cow\_horse.png # Add image post (optional)
tags: [Blog, Research]
author: Max Jiang # Add name author (optional)
---

One of my first year projects to morph arbitrary genus-one mesh and mesh patches with same number of boundaries. Input meshes are parameterized using spherical parameterization (for genus-zero shapes) and uv-parameterization (for mesh patches), and warped to match feature points. 

<head>
<meta charset=utf-8 />
<title></title>
<style>
div.container {
display:inline-block;
}

p {
text-align:center;
}
</style>
</head>
<body>
<div class="container">
<img src="{{site.baseurl}}/assets/img/cmcf.gif" height="200" width="300" />
<p>This is image 1</p>
</div>
<div class="container">
<img class="middle-img" src="{{site.baseurl}}/assets/img/horse_cow_morph.gif"/ height="200" width="300" />
<p>This is image 2</p>
</div>
<div class="container">
<img src="{{site.baseurl}}/assets/img/head_morph_cropped.gif" height="200" width="100" />
<p>This is image 3</p>
</div>
</div>
</body>

