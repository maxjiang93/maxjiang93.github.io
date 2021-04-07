---
layout: project
title: MeshfreeFlowNet
permalink: /proj/meshfreeflownet
---
<head>
<style>
sup {
    vertical-align: super;
    font-size: 10px;
}
</style>
</head>
<center>
<h1> MeshfreeFlowNet: A Physics-Constrained Deep Continuous Space-Time Super-Resolution Framework </h1>
<a href="http://www.maxjiang.ml/">Chiyu "Max" Jiang*<sup>1</sup></a> &nbsp; &nbsp; &nbsp;<a href="https://soheilesm.github.io/">Soheil Esmaeilzadeh*<sup>2</sup></a> &nbsp; &nbsp; &nbsp;<a href="https://www.cs.purdue.edu/homes/kamyar/">Kamyar Azizzadenesheli<sup>3</sup></a> &nbsp; &nbsp; &nbsp;<br><a href="http://www.nersc.gov/about/nersc-staff/data-analytics-services/karthik-kashinath/">Karthik Kashinath<sup>4</sup></a> &nbsp; &nbsp; &nbsp;
<a href="https://www.nersc.gov/about/nersc-staff/data-analytics-services/mustafa-mustafa/">Mustafa Mustafa<sup>4</sup></a> &nbsp; &nbsp; &nbsp;<a href="https://profiles.stanford.edu/hamdi-tchelepi">Hamdi Tchelepi<sup>2</sup></a>&nbsp; &nbsp; &nbsp;<a href="http://www.me.berkeley.edu/people/faculty/philip-s-marcus">Philip Marcus<sup>1</sup></a>&nbsp; &nbsp; &nbsp;<a href="http://www.nersc.gov/about/nersc-staff/data-analytics-services/prabhat/">Prabhat<sup>4</sup></a>&nbsp; &nbsp; &nbsp;<br><a href="http://tensorlab.cms.caltech.edu/users/anima/">Anima Anandkumar<sup>5,6</sup></a><br/>(* Denotes Equal Contributions)<br/>

<sup>1</sup> University of California, Berkeley &nbsp;
<sup>2</sup> Stanford University &nbsp;
<sup>3</sup> Purdue University <br>
<sup>4</sup> Lawrence Berkeley National Lab &nbsp;
<sup>5</sup> California Institute of Technology &nbsp;
<sup>6</sup> NVIDIA <br>

<br>

<img src="{{ site.baseurl }}/assets/img/meshfreeflownet/mffn_logo.png" width="750"/>

<br>

Published at <i>International Conference for High Performance Computing, Networking, Storage and Analysis (SC20)</i>. Best Student Paper Award Finalist.

<br>
<a href="https://arxiv.org/pdf/2005.01463.pdf">[Paper]</a>&nbsp;&nbsp;<a href="https://github.com/maxjiang93/space_time_pde">[Code]</a>&nbsp;&nbsp;<a href="#" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2020meshfreeflownet.txt'">[Bibtex]</a>&nbsp;&nbsp;<a href="https://youtu.be/mjqwPch9gDo">[Video]</a>
<br>
<br>
<img src="{{ site.baseurl }}/assets/img/meshfreeflownet/teaser_wide.png" width="750"/>
</center>
**Figure 1** MeshfreeFlowNet is a novel deep learning-based super-resolution framework to generate continuous (grid-free) spatio-temporal solutions from the low-resolution inputs. It consists of two end-to-end trainable modules, the Context Generation Network, and a Continuous Decoding Network.

## Abstract

We propose MeshfreeFlowNet, a novel deep learning-based super-resolution framework to generate continuous (grid-free) spatio-temporal solutions from the low-resolution inputs. While being computationally efficient, MeshfreeFlowNet accurately recovers the fine-scale quantities of interest. MeshfreeFlowNet allows for: (i) the output to be sampled at all spatio-temporal resolutions, (ii) a set of Partial Differential Equation (PDE) constraints to be imposed, and (iii) training on fixed-size inputs on arbitrarily sized spatio-temporal domains owing to its fully convolutional encoder.

We empirically study the performance of MeshfreeFlowNet on the task of super-resolution of turbulent flows in the Rayleigh–Bénard convection problem. Across a diverse set of evaluation metrics, we show that MeshfreeFlowNet significantly outperforms existing baselines. Furthermore, we provide a large scale implementation of MeshfreeFlowNet and show that it efficiently scales across large clusters, achieving 96.80% scaling efficiency on up to 128 GPUs and a training time of less than 4 minutes.

## Gallery
<center>
<img src="{{ site.baseurl }}/assets/img/meshfreeflownet/teaser_wide.gif" width="750"/>
</center>
**Figure 2** Visualization of the super-resolution quality of the MeshfreeFlowNet. The framerate is limitted for the gif animation. For better results, checkout the video link above.
