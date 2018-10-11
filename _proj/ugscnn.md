---
layout: project
title: UGSCNN
permalink: /proj/ugscnn
---
<center>
<h1> Spherical CNNs on Unstructured Grids </h1>
<a href="http://www.maxjiang.ml/">Chiyu "Max" Jiang</a> &nbsp; &nbsp; &nbsp;<a href="http://stanford.edu/~jingweih/">Jingwei Huang</a> &nbsp; &nbsp; &nbsp;<a href="http://www.nersc.gov/about/nersc-staff/data-analytics-services/karthik-kashinath/">Karthik Kashinath</a><br>
<a href=
"http://www.nersc.gov/about/nersc-staff/data-analytics-services/prabhat/">Prabhat</a> &nbsp; &nbsp; &nbsp;<a href="http://www.me.berkeley.edu/people/faculty/philip-s-marcus">Philip Marcus</a> &nbsp; &nbsp; &nbsp;<a href="http://niessnerlab.org/">Matthias Niessner</a><br>
<br>
<a href="#" onclick="return false;">[Paper]</a>&nbsp;<a href="#" onclick="return false;">[Code]</a>&nbsp;<a href="#" onclick="return false;">[Bibtex]</a>
<img src="{{ site.baseurl }}/assets/img/ugscnn/teaser.png" width="750"/>
</center>
**Figure 1** Illustration for the MeshConv operator using parameterized differential operators to replace conventional learnable convolutional kernels.

## Abstract

We present an efficient convolution kernel for Convolutional Neural Networks (CNNs) on unstructured grids using parameterized differential operators while focusing on spherical signals such as panorama images or planetary signals. To this end, we replace conventional convolution kernels with linear combinations of differential operators that are weighted by learnable parameters. Differential operators can be efficiently estimated on unstructured grids using one-ring neighbors, and learnable parameters can be optimized through standard back-propagation. As a result, we obtain extremely efficient neural networks that match or outperform state-of-the-art network architectures in terms of performance but with a significantly lower number of network parameters. We evaluate our algorithm in an extensive series of experiments on a variety of computer vision and climate science tasks, including shape classification, climate pattern segmentation, and omnidirectional image semantic segmentation. Overall, we present (1) a novel CNN approach on unstructured grids using parameterized differential operators for spherical signals, and (2) we show that our unique kernel parameterization allows our model to achieve the same or higher accuracy with significantly fewer network parameters.

## Gallery
<center>
<img src="{{ site.baseurl }}/assets/img/ugscnn/ugscnn_vis.png" width="750"/>
</center>
**Figure 2** Visualization of semantic segmentation results on test set. Our results are generated on a level-5 spherical mesh and mapped to the equirectangular grid for visualization. Model underper- forms in complex environments, and fails to predict ceiling lights due to incomplete RGB inputs.