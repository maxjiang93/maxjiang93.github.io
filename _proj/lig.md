---
layout: project
title: Local Implicit Grid
permalink: /proj/lig
---
<center>
<h1> Local Implicit Grid Representations for 3D Scenes </h1>
<a href="http://www.maxjiang.ml/">Chiyu "Max" Jiang</a> &nbsp; &nbsp; &nbsp;<a href="https://research.google/people/105052/">Avneesh Sud</a> &nbsp; &nbsp; &nbsp;<a href="http://www.ameeshmakadia.com/index.html">Ameesh Makadia</a> &nbsp; &nbsp; &nbsp;<a href="http://stanford.edu/~jingweih/">Jingwei Huang</a> &nbsp; &nbsp; &nbsp;<br>
<a href="https://www.niessnerlab.org/members/matthias_niessner/profile.html">Matthias Niessner</a> &nbsp; &nbsp; &nbsp;<a href="https://www.cs.princeton.edu/~funk/">Thomas Funkhouser</a><br />
<br>
<a href="#" onclick="window.location.href='https://arxiv.org/abs/2003.08981'">[Paper]</a>&nbsp;&nbsp;<a href="#" onclick="window.location.href='https://github.com/google-research/google-research/tree/master/local_implicit_grid'">[Code]</a>&nbsp;&nbsp;<a href="#" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2020lig.txt'">[Bibtex]</a>&nbsp;&nbsp;<a href="#" onclick="window.location.href='https://youtu.be/XCyl1-vxfII'">[Video]</a>
<br>
<br>
<img src="{{ site.baseurl }}/assets/img/lig/lig_teaser_wide.png" width="750"/>
</center>
**Figure 1** We learn an embedding of parts from objects in ShapeNet using a part autoencoder with an implicit decoder. We show that this representation of parts is generalizable across object categories, and easily scalable to large scenes. By localizing implicit functions in a grid, we are able to reconstruct entire scenes from points via optimization of the latent grid.

## Abstract

Shape priors learned from data are commonly used to reconstruct 3D objects from partial or noisy data. Yet no such shape priors are available for indoor scenes, since typical 3D autoencoders cannot handle their scale, complexity, or diversity. In this paper, we introduce Local Implicit Grid Representations, a new 3D shape representation designed for scalability and generality. The motivating idea is that most 3D surfaces share geometric details at some scale – i.e., at a scale smaller than an entire object and larger than
a small patch. We train an autoencoder to learn an embedding of local crops of 3D shapes at that size. Then, we use the decoder as a component in a shape optimization that solves for a set of latent codes on a regular grid of overlapping crops such that an interpolation of the decoded local shapes matches a partial or noisy observation. We demonstrate the value of this proposed approach for 3D surface reconstruction from sparse point observations, showing significantly better results than alternative approaches.

## Gallery
<center>
<img src="{{ site.baseurl }}/assets/img/lig/comparison.png" width="750"/>
</center>
**Figure 2** Visualization of scene reconstruction quality versus Screened Poisson Surface Reconstruction (PSR).
