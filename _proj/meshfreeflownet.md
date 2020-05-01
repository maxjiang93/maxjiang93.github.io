---
layout: project
title: MeshfreeFlowNet
permalink: /proj/meshfreeflownet
---
<center>
<h1> MeshfreeFlowNet: A Physics-Constrained Deep Continuous Space-Time Super-Resolution Framework </h1>
<a href="http://www.maxjiang.ml/">Chiyu "Max" Jiang*</a> &nbsp; &nbsp; &nbsp;<a href="https://soheilesm.github.io/">Soheil Esmaeilzadeh*</a> &nbsp; &nbsp; &nbsp;<a href="https://www.cs.purdue.edu/homes/kamyar/">Kamyar Azizzadenesheli</a> &nbsp; &nbsp; &nbsp;<a href="http://www.nersc.gov/about/nersc-staff/data-analytics-services/karthik-kashinath/">Karthik Kashinath</a> &nbsp; &nbsp; &nbsp;
<a href="https://www.nersc.gov/about/nersc-staff/data-analytics-services/mustafa-mustafa/">Mustafa Mustafa</a> &nbsp; &nbsp; &nbsp;<a href="https://profiles.stanford.edu/hamdi-tchelepi">Hamdi Tchelepi</a>&nbsp; &nbsp; &nbsp;<a href="http://www.me.berkeley.edu/people/faculty/philip-s-marcus">Philip Marcus</a>&nbsp; &nbsp; &nbsp;<a href="http://www.nersc.gov/about/nersc-staff/data-analytics-services/prabhat/">Prabhat</a>&nbsp; &nbsp; &nbsp;<a href="http://tensorlab.cms.caltech.edu/users/anima/">Anima Anandkumar</a><br/>(* Denotes Equal Contributions)<br/>

<br>
<a href="#" onclick="window.location.href=''">[Paper]</a>&nbsp;&nbsp;<a href="#" onclick="window.location.href='https://github.com/maxjiang93/space_time_pde'">[Code]</a>&nbsp;&nbsp;<a href="#" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2020meshfreeflownet.txt'">[Bibtex]</a>&nbsp;&nbsp;<a href="#" onclick="window.location.href='https://youtu.be/mjqwPch9gDo'">[Video]</a>
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
