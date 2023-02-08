---
layout: post
title:  "N-Cloth: Predicting 3D Cloth Deformation with Mesh-Based Networks"
date:   2019-10-26 10:00:40
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/NCloth.jpg
---

Yudi Li<sup>1</sup>, Min Tang<sup>1</sup>, Yun Yang<sup>1</sup>, Zi Huang<sup>1</sup>, Ruofeng Tong<sup>1</sup>, Shuangcai Yang<sup>3</sup>, Yao Li<sup>3</sup>, Dinesh Manocha<sup>2</sup>

<sup>1</sup><i>Zhejiang University, China</i>

<sup>2</sup><i>University of Maryland at College Park, America</i>

<sup>3</sup><i>Tencent</i>

<strong>
Same page link:
</strong>
<a href="https://min-tang.github.io/home/NCloth/">(https://min-tang.github.io/home/NCloth/)</a>

<img src="{{ "/assets/img/content/post-example/NCloth/NCloth.jpg" | absolute_url }}" alt="bay" class="post-pic"/>

## Abstraction

We present a novel mesh-based learning approach (N-Cloth) for plausible 3D cloth deformation prediction. Our approach is  general and can handle cloth or obstacles represented by triangle meshes with arbitrary topologies. We use  graph convolution to transform the cloth and object meshes into a latent space to reduce the non-linearity in the mesh space. Our network can predict the target 3D cloth mesh deformation based on the initial state of the cloth mesh template and the target obstacle  mesh. Our approach can handle complex cloth meshes with up to $100$K triangles and scenes with various objects corresponding to SMPL humans, non-SMPL humans or rigid bodies. In practice, our approach can be used to generate plausible cloth simulation at $30-45$ fps on an NVIDIA GeForce RTX 3090 GPU. We highlight its benefits over prior learning-based methods and physically-based cloth simulators.

## Results
Our network can not only handle SMPL and non-SMPL human bodies, but also rigid obstacles. Our network can also process various types of clothes without providing skin models for those clothes. Compared with the previous method, our network can handle more scenarios.

<img src="{{ "/assets/img/content/post-example/NCloth/1.jpg" | absolute_url }}" alt="bay" class="post-pic"/>

<img src="{{ "/assets/img/content/post-example/NCloth/12.jpg" | absolute_url }}" alt="bay" class="post-pic"/>

## Video
Here is the demo video.

<iframe width="560" height="315" src="https://www.youtube.com/embed/TCPpvx9vYns" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
