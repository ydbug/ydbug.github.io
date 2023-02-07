---
layout: post
title:  "CTSN：Predicting Cloth Deformation for Skeleton-based Characters with a Two-stream Skinning Network"
author: Yudi Li, Min Tang, Yun Yang
date:   2023-01-01 10:00:00
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/CSTN.jpg
---

Yudi Li$^{1}$, Min Tang$^{1}$, Yun Yang$^{1}$, Zi Huang$^{1}$, Ruofeng Tong$^{1}$, Shuangcai Yang$^{3}$, Yao Li$^{3}$, Dinesh Manocha$^{2}$

*$^{1}$ Zhejiang University, China*

*$^{2}$ University of Maryland at College Park, America*

*$^{3}$ Tencen*t

<img src="{{ "/assets/img/content/post-example/CSTN.jpg" | absolute_url }}" alt="bay" class="post-pic"/>
<br />
<br />

## Abstraction

We present a novel mesh-based learning approach (N-Cloth) for plausible 3D cloth deformation prediction. Our approach is  general and can handle cloth or obstacles represented by triangle meshes with arbitrary topologies. We use  graph convolution to transform the cloth and object meshes into a latent space to reduce the non-linearity in the mesh space. Our network can predict the target 3D cloth mesh deformation based on the initial state of the cloth mesh template and the target obstacle  mesh. Our approach can handle complex cloth meshes with up to $100$K triangles and scenes with various objects corresponding to SMPL humans, non-SMPL humans or rigid bodies. In practice, our approach can be used to generate plausible cloth simulation at $30-45$ fps on an NVIDIA GeForce RTX 3090 GPU. We highlight its benefits over prior learning-based methods and physically-based cloth simulators.

This is an example of blog post.
Picture by [Bethany Legg](https://unsplash.com/@bkotynski).

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum[^1].

<br />


#### Table of Contents
- [Abstraction](#abstraction)
    - [Table of Contents](#table-of-contents)
    - [PART 1](#part-1)
    - [PART 2](#part-2)
      - [PART 2 SUB PART 1](#part-2-sub-part-1)
      - [PART 2 SUB PART 2](#part-2-sub-part-2)
      - [FOOTNOTES](#footnotes)

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
