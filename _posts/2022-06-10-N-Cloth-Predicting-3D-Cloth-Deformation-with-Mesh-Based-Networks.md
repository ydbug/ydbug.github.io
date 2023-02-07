---
layout: post
title:  "N-Cloth：Predicting 3D Cloth Deformation with Mesh-Based Networks"
date:
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/NCloth.jpg
---

Yudi Li<sup>1</sup>, Min Tang<sup>1</sup>, Yun Yang<sup>1</sup>, Zi Huang<sup>1</sup>, Ruofeng Tong<sup>1</sup>, Shuangcai Yang<sup>3</sup>, Yao Li<sup>3</sup>, Dinesh Manocha<sup>2</sup>

<sup>1</sup><i>Zhejiang University, China</i>

<sup>2</sup><i>University of Maryland at College Park, America</i>

<sup>3</sup><i>Tencent</i>

<img src="{{ "/assets/img/content/post-example/NCloth.jpg" | absolute_url }}" alt="bay" class="post-pic"/>
<br />
<br />

We present a novel mesh-based learning approach (N-Cloth) for plausible 3D cloth deformation prediction. Our approach is  general and can handle cloth or obstacles represented by triangle meshes with arbitrary topologies. We use  graph convolution to transform the cloth and object meshes into a latent space to reduce the non-linearity in the mesh space. Our network can predict the target 3D cloth mesh deformation based on the initial state of the cloth mesh template and the target obstacle  mesh. Our approach can handle complex cloth meshes with up to $100$K triangles and scenes with various objects corresponding to SMPL humans, non-SMPL humans or rigid bodies. In practice, our approach can be used to generate plausible cloth simulation at $30-45$ fps on an NVIDIA GeForce RTX 3090 GPU. We highlight its benefits over prior learning-based methods and physically-based cloth simulators.

<br />


<!-- #### Table of Contents
- [Table of Contents](#table-of-contents)
- [PART 1](#part-1)
- [PART 2](#part-2)
  - [PART 2 SUB PART 1](#part-2-sub-part-1)
  - [PART 2 SUB PART 2](#part-2-sub-part-2)
  - [FOOTNOTES](#footnotes) -->

#### PART 1
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
<br />

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<br />
<br />

#### PART 2
**Lorem ipsum dolor sit amet,** consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<br />

##### PART 2 SUB PART 1
*Duis aute irure dolor in reprehenderit* in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<br />

##### PART 2 SUB PART 2
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<br />


##### FOOTNOTES

[^1]: This is a note!
