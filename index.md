---
layout: about
title: Homepage

---

## Bio
I am currently a Senior Applied Research Scientst at [Cruise AI](https://www.getcruise.com/), where I work on LiDAR-based object detection systems to advance the state of 3D Computer Vision for self-driving cars. 

I received a Ph.D. from UC Berkeley in 2020. I worked on 3D Computer Vision / Geometric Deep Learning algorithms, and have first-author publications in top CV/ML conferences (CVPR, ICCV, ICLR). I had the pleasure of collaborating with [Matthias Niessner](https://www.niessnerlab.org/members/matthias_niessner/profile.html) (TUM), [Tom Funkhouser](https://www.cs.princeton.edu/~funk/) (Google), [Leonidas Guibas](https://geometry.stanford.edu/member/guibas/) (Stanford), [Andrea Tagliasacchi](https://taiya.github.io/) (Google Brain), [Anima Anandkumar](http://tensorlab.cms.caltech.edu/users/anima/) (CalTech, NVIDIA) and [Prabhat](https://www.nersc.gov/about/nersc-staff/data-analytics-services/prabhat/) (LBNL), among other amazing researchers in this field. I was advised by [Philip Marcus](https://www.me.berkeley.edu/people/faculty/philip-s-marcus), and I have worked as interns and student researchers at [Google AI](https://ai.google/research/) and [Lawrence Berkeley National Lab](https://www.nersc.gov/).

## News
* [06/2020] <span style="color:red"> **New!** </span> I started the position of Senior Applied Research Scientist at Cruise, working on 3D Computer Vision for self-driving cars.
* [06/2020] <span style="color:red"> **New!** </span> Our recent work, MeshfreeFlowNet, has been selected for publication at [SC20](https://sc20.supercomputing.org/)!
<details markdown="1"><summary>See More</summary>
<span>
* [03/2020] Two papers accepted to CVPR 2020! Check out our papers on local implicit grid representations for 3D scenes, and adversarial texture optimization from RGB-D scans.
* [07/2019] Our recent paper on Deep Differentiable Simplex Layer has been accepted to ICCV 2019 conference!
* [05/2019] I will be interning in [Machine Perception](https://ai.google/research/teams/perception/) @ [Google Research](https://ai.google/research/) in summer 2019 as a Ph.D research intern.
* [12/2018] My work on Spherical CNNs on Unstructred Grids has been chosen for an oral presentation at the [AGU](https://fallmeeting.agu.org/2018/) (Americal Geophysics Union).
* Two of my papers have been accepted to the ICLR 2019 conference!
* [06/2018] I am interning this summer at the Data Analytics group in NERSC, Lawrence Berkeley National Labratory, working with [Prabhat](http://www.nersc.gov/about/nersc-staff/data-analytics-services/prabhat/) and [Karthik Karshinath](http://www.nersc.gov/about/nersc-staff/data-analytics-services/karthik-kashinath/) on new Deep Learning methodologies for Climate Science.
* [03/2018] I am invited to visit [Center for Nonlinear Studies](https://cnls.lanl.gov/External/) at Los Alamos National Labratory, and to present my work on 3D deep learning.
* [01/2018] I made an oral presentation of my work on Aerodynamics Optimization using Deep Learning at [Physics Informed Machine Learning](http://www.cvent.com/events/2nd-physics-informed-machine-learning/event-summary-ae6f3a0d824944d9bfc805f3d66773ee.aspx).
</details>

## Experiences
**[Cruise](https://www.getcruise.com/)** \| San Francisco, CA 

- (06/2020 - Present) **Senior Applied Research Scientist, Computer Vision**
    - Leading the deployment of the current LiDAR based object detection system on the car, coordinating various cross-team collaborations for runtime optimizations.
    - Improved the functional and runtime performance of the model, resulting in 138x improvement in point data processing speed.

**[Google AI](https://ai.google/research/)** \| Mountain View, CA

- (05/2019 - 03/2020) **Research Intern / Student Researcher**
    - Developed novel learning based implicit 3D geometry representation for large-scale scene reconstruction from point clouds ([Local Implicit Grid](proj/lig) - CVPR 2020).
    - Collaborated on a project for generating enhanced texture for scanned 3D models ([Adversarial Texture Optimization](http://stanford.edu/~jingweih/papers/advtex/) - CVPR 2020).
    - Proficient with Google internal infrastructure and TensorFlow for ML development, and Apache Beam for massive data processing and ML inference workflows.
    - Initiated and coordinated internal and external collaborations with research partners.

**[Lawrence Berekely National Lab](https://www.nersc.gov/)** \| Berkeley, CA

- (05/2018 - 05/2020) **Research Intern / Student Researcher**
    - Research in physics-informed machine learning for spatial-temporal super-resolution ([MeshfreeFlowNet](proj/meshfreeflownet) - SC 20).
    - Research on Spherical CNNs on Unstructured Grids and applications towards computer vision and climate science ([Unstructured Grid Spherical CNN](proj/ugscnn) - ICLR 2019).
    - Mentored and supervised junior researchers and research interns ([Dana Lansigan](http://dlansigan.github.io/), [Eli Jergensen](https://www.linkedin.com/in/gelijergensen/), [Haris Sheikh](https://cfd.me.berkeley.edu/people/haris-moazam-sheikh/))

## Professional Service

Reviewer for ICCV, AAAI, CVPR, ECCV, NeurIPS, ICLR.

## Publications
<table style="width:100%">
  <tr>
      <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/shapeflow/shapeflow_teaser.png" width="350"/></center></td>
      <td width="7%"></td>
      <td width="75%">ShapeFlow: Learnable Deformations Among 3D Shapes
        <br>
        <i>In Submission</i>
        <br>
        <font size="2"><b>Chiyu "Max" Jiang*</b>, Jingwei Huang*, Andrea Tagliasacchi, Leonidas Guibas</font><br>
      <div>
          <style scoped>
              .button-xsmall {
                  font-size: 70%;
              }
          </style>
          <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/abs/2006.07982'">Paper</button>
      </div>

  </td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/meshfreeflownet/teaser.gif" width="350"/></center></td>
    <td width="7%"></td>
    <td width="75%">MeshfreeFlowNet: A Physics-Constrained Deep Continuous Space-Time Super-Resolution Framework
      <br>
      <i>International Conference for High Performance Computing, Networking, Storage and Analysis (SC20)</i>
      <br>
      <font size="2"><b>Chiyu "Max" Jiang*</b>, Soheil Esmaeilzadeh*, Kamyar Azizzadenesheli, Karthik Kashinath, Mustafa Mustafa, Hamdi Tchelepi, Philip Marcus, Prabhat, Anima Anandkumar</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}{% link _proj/meshfreeflownet.md %}'">Webpage</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/pdf/2005.01463.pdf'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/maxjiang93/space_time_pde'">Code</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2020meshfreeflownet.txt'">Bibtex</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://youtu.be/mjqwPch9gDo'">Video</button>
    </div>

</td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/lig/teaser.png" width="350"/></center></td>
    <td width="7%"></td>
    <td width="75%">Local Implicit Grid Representations for 3D Scenes
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
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}{% link _proj/lig.md %}'">Webpage</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/abs/2003.08981'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/tensorflow/graphics/tree/master/tensorflow_graphics/projects/local_implicit_grid'">Code</button>
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
    <td width="75%">Adversarial Texture Optimization from RGB-D Scans
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
        <button class="button-xsmall pure-button" onclick="window.location.href='http://stanford.edu/~jingweih/papers/advtex/'">Webpage</button>
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
    <td width="75%">DDSL: Deep Differentiable Simplex Layer for Learning Geometric Signals
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
        <button class="button-xsmall pure-button" onclick="window.location.href='https://www.niessnerlab.org/projects/jiang2019ddsl.html'">Webpage</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://arxiv.org/abs/1901.11082'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/maxjiang93/DDSL'">Code</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2019ddsl.txt'">Bibtex</button>
    </div>

</td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/ugscnn/cli_pred.png" width="100"/></center></td>
    <td width="7%"></td>
    <td width="75%">Spherical CNNs on Unstructured Grids
        <br>
        <i>International Conference on Learning Representations (2019)</i>
        <br>
        <font size="2"><b>Chiyu "Max" Jiang</b>, Jingwei Huang, Karthik Kashinath, Prabhat, Philip Marcus, Matthias Niessner</font><br>
    <div>
        <style scoped>
            .button-xsmall {
                font-size: 70%;
            }
        </style>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}{% link _proj/ugscnn.md %}'">Webpage</button>
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
    <td width="75%">Convolutional Neural Networks on non-uniform geometrical signals using Euclidean spectral transformation
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
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}{% link _proj/nuft.md %}'">Webpage</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://openreview.net/pdf?id=B1G5ViAqFm'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='https://github.com/maxjiang93/DDSL'">Code</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/jiang2019convolutional.txt'">Bibtex</button>
    </div></td>
  </tr>
  <tr>
  	<td><br></td>
  </tr>
  <tr>
    <td width="18%"><img src="{{ site.baseurl }}/assets/img/bayesianFig.png" width="350"/></td>
    <td width="7%"></td>
    <td width="75%">Leveraging Bayesian Analysis To Improve Reduced Order Models
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
        <button class="button-xsmall pure-button" onclick="window.location.href='https://public.lanl.gov/livescu/frames/Nadiga_etal_JCP19.pdf'">Paper</button>
        <button class="button-xsmall pure-button" onclick="window.location.href='{{ site.baseurl }}/assets/bib/nadiga2019leveraging.txt'">Bibtex</button>
    </div></td>
  </tr>
  <tr>
    <td><br></td>
  </tr>
  <tr>
    <td width="18%"><center><img src="{{ site.baseurl }}/assets/img/train/icon.png" width="200"/></center></td>
    <td width="7%"></td>
    <td width="75%">Finding the optimal shape of the leading-and-trailing car of a high-speed train using design-by-morphing
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
    <td width="75%">Hierarchical Detail Enhancing Mesh-Based Shape Generation with 3D Generative Adversarial Network
        <br>
        <font size="2"><b>Chiyu "Max" Jiang</b>, Philip Marcus</font><br>
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
    <td width="75%">Morphing of Genus-Zero Shapes using Spherical Parameterization&nbsp;&nbsp;
        <br>
        <font size="2"><b>Chiyu "Max" Jiang</b>, Philip Marcus</font><br>
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
