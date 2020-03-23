---
layout: about
title: Homepage

---

## About

I'm a fifth-year Ph.D student at UC Berkeley advised by Prof. [Philip Marcus](https://www.me.berkeley.edu/people/faculty/philip-s-marcus), affiliated with the Data Analytics group at [NERSC](http://nersc.gov/), Lawrence Berkeley National Lab. My research interest is in Machine Learning and Deep Learning methodologies related to 3D geometry. In particular, I am interested in leveraging advances in 3D learning for applications in a variety of physical and engineering systems, examples include 3D scene reconstruction, omnidirectional image segmentation, climate pattern detection and aerodynamical shape optimization.

Prior to joining UC Berkeley, I got my Bachelor's degree from [Cornell University](https://www.cornell.edu/), as well as a joint degree from [Zhejiang University](http://www.zju.edu.cn/english/).

## News
* <span style="color:red"> **New!** </span> Two papers accepted to CVPR 2020! Check out my paper on learning local implicit grid representation for 3D scenes, and adversarial texture optimization from RGB-D scans.
* My recent paper on Deep Differentiable Simplex Layer has been accepted to ICCV 2019 conference!
* I will be interning in [Machine Perception](https://ai.google/research/teams/perception/) @ [Google Research](https://ai.google/research/) in summer 2019 as a Ph.D research intern.
* My work on Spherical CNNs on Unstructred Grids has been chosen for an oral presentation at the [AGU](https://fallmeeting.agu.org/2018/) (Americal Geophysics Union).
* Two of my papers have been accepted to the ICLR 2019 conference!
* I am interning this summer at the Data Analytics group in NERSC, Lawrence Berkeley National Labratory, working with [Prabhat](http://www.nersc.gov/about/nersc-staff/data-analytics-services/prabhat/) and [Karthik Karshinath](http://www.nersc.gov/about/nersc-staff/data-analytics-services/karthik-kashinath/) on new Deep Learning methodologies for Climate Science.
* I am invited to visit [Center for Nonlinear Studies](https://cnls.lanl.gov/External/) at Los Alamos National Labratory, and to present my work on 3D deep learning.
* I made an oral presentation of my work on Aerodynamics Optimization using Deep Learning at [Physics Informed Machine Learning](http://www.cvent.com/events/2nd-physics-informed-machine-learning/event-summary-ae6f3a0d824944d9bfc805f3d66773ee.aspx).

## Experiences
* [Su 19] <b>Research Intern at Google AI - Perception</b>: <br> Research on deep 3D geometric representation and reconstructions.

* [Su 18] <b>Research Intern at Lawrence Berkeley National Lab</b>: <br>Research on Spherical CNNs on Unstructured Grids and applications towards computer vision and climate science (subsequent publication at ICLR 2019).

* [Fa 17] <b>Graduate Student Instructor</b>: <br>([CS294-73](https://inst.eecs.berkeley.edu/~cs294-73/fa17/)): Software Engineering for Scientific Computing.

## Professional Service

Reviewer [ICCV'19, AAAI'20, CVPR'20, ECCV'20, NeurIPS'20]

## Recent Publications
<table style="width:100%">
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/lig/teaser.png" width="350"/></center></td>
    <td width="7%"></td>
    <td width="75%"><a href="{{ site.baseurl }}{% link _proj/lig.md %}">Learning Local Implicit Grid Representation for 3D Scenes</a>
      <br>
      <i>Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (2020)</i>
      <br>
      <font size="2"><b>Chiyu "Max" Jiang</b>, Avneesh Sud, Ameesh Makadia, Jingwei Huang, Matthias Niessner, Tom Funkhouser</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/abs/2003.08981'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/google-research/google-research/tree/master/local_implicit_grid'">Code</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2020lig.txt'">Bibtex</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://youtu.be/XCyl1-vxfII'">Video</button>
    </div>

</td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/texturegen/teaser.png" width="350"/></center></td>
    <td width="7%"></td>
    <td width="75%"><a href='http://stanford.edu/~jingweih/papers/advtex/'>Adversarial Texture Optimization from RGB-D Scans</a>
      <br>
      <i>Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (2020)</i>
      <br>
      <font size="2">Jingwei Huang, Justus Thies, Angela Dai, Abhijit Kundu, <b>Chiyu "Max" Jiang</b>, Leonidas Guibas, Matthias Niessner, Tom Funkhouser</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='http://stanford.edu/~jingweih/papers/advtex/supp/paper.pdf'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='http://stanford.edu/~jingweih/papers/advtex/supp/supplemental.pdf'">Supplemental</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/hjwdzh/AdversarialTexture'">Code</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/huang2020adversarial.txt'">Bibtex</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://youtu.be/52xlRn0ESek'">Video</button>
    </div>

</td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/ddsl/teaser.png" width="350"/></center></td>
    <td width="7%"></td>
    <td width="75%"><a href='{{ site.baseurl }}{% link _pages/tobereleased.md %}'>DDSL: Deep Differentiable Simplex Layer for Learning Geometric Signals</a>
      <br>
      <i>Proceedings of the IEEE International Conference on Computer Vision (2019)</i>
      <br>
      <font size="2"><b>Chiyu "Max" Jiang</b>*, Dana Lansigan*, Philip Marcus, Matthias Niessner</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/abs/1901.11082'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/maxjiang93/DDSL'">Code</button>
    </div>

</td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/ugscnn/cli_pred.png" width="100"/></center></td>
    <td width="7%"></td>
    <td width="75%"><a href="{{ site.baseurl }}{% link _proj/ugscnn.md %}">Spherical CNNs on Unstructured Grids</a>&nbsp;&nbsp;<i>International Conference on Learning Representations (2019)</i><br><font size="2"><b>Chiyu "Max" Jiang</b>, Jingwei Huang, Karthik Kashinath, Prabhat, Philip Marcus, Matthias Niessner</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/abs/1901.02039'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/maxjiang93/ugscnn'">Code</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2019spherical.txt'">Bibtex</button>
    </div>

</td>
  </tr>
  <tr>
  	<td><br></td>
  </tr>
  <tr>
    <td width="18%"><img src="{{ site.baseurl }}/assets/img/nuft/icon.png" width="350"/></td>
    <td width="7%"></td>
    <td width="75%"><a href="{{ site.baseurl }}{% link _proj/nuft.md %}">Convolutional Neural Networks on non-uniform geometrical signals using Euclidean spectral transformation</a>
      <br>
      <i>International Conference on Learning Representations (2019)</i>
      <br>
      <font size="2"><b>Chiyu "Max" Jiang</b>, Dequan Wang, Jingwei Huang, Philip Marcus, Matthias Niessner</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://openreview.net/pdf?id=B1G5ViAqFm'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}{% link _pages/tobereleased.md %}'">Code</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2019convolutional.txt'">Bibtex</button>
    </div></td>
  </tr>
  <tr>
  	<td><br></td>
  </tr>
  <tr>
    <td width="18%"><img src="{{ site.baseurl }}/assets/img/bayesianFig.png" width="350"/></td>
    <td width="7%"></td>
    <td width="75%"><a href='#'>Leveraging Bayesian Analysis To Improve Reduced Order Models</a>
      <br>
      <i>Journal of Computational Physics</i> (2019): 280-297.
      <br>
      <font size="2">B.T. Nadiga, <b>Chiyu Max Jiang</b>, Daniel Livscu</font>
      <br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}{% link _pages/tobereleased.md %}'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}{% link _pages/tobereleased.md %}'">Bibtex</button>
    </div></td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/train/icon.png" width="200"/></center></td>
    <td width="7%"></td>
    <td width="75%"><a href="https://link.springer.com/article/10.1007/s00466-017-1482-4">Finding the optimal shape of the leading-and-trailing car of a high-speed train using design-by-morphing</a>
      <br>
      <i>Computational Mechanics</i> (2017): 1-23.
      <br>
      <font size="2">Sahuck Oh, Chung-Hsiang Jiang, <b>Chiyu "Max" Jiang</b>, Philip Marcus</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="location.href='https://link.springer.com/article/10.1007/s00466-017-1482-4'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/oh2017finding.txt'">Bibtex</button>
    </div>

</td>
  </tr>
  <tr>
  	<td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/shape/furniture-render.gif" width="250"/></center></td>
    <td width="7%"></td>
    <td width="75%"><a href="https://arxiv.org/abs/1709.07581">Hierarchical Detail Enhancing Mesh-Based Shape Generation with 3D Generative Adversarial Network</a><br><font size="2"><b>Chiyu "Max" Jiang</b>, Philip Marcus</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/pdf/1709.07581.pdf'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2017hierarchical.txt'">Bibtex</button>
    </div>

</td>
  </tr>
</table>

## Other Select Projects

<table style="width:100%">
  <tr>
    <td width="18%"><img src="{{ site.baseurl }}/assets/img/morph/head_morph_cropped.gif" width="250"/></td>
    <td width="7%"></td>
    <td width="75%"><a href="{{ site.baseurl }}{% link _proj/nuft.md %}">Morphing of Genus-Zero Shapes using Spherical Parameterization</a>&nbsp;&nbsp;<br><font size="2"><b>Chiyu "Max" Jiang</b>, Philip Marcus</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/maxjiang93/morph'">Code</button>
    </div></td>
  </tr>
</table>
 <br>
