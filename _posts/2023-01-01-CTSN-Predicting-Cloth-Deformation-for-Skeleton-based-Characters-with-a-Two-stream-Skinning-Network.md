---
layout: post
title:  "CTSN: Predicting Cloth Deformation for Skeleton-based Characters with a Two-stream Skinning Network"
date:   2019-10-26 10:00:40
blurb: "A look at an example post using Bay Jekyll theme."
og_image: /assets/img/content/post-example/CSTN.jpg
---

Yudi Li<sup>1</sup>, Min Tang<sup>1</sup>, Yun Yang<sup>1</sup>, Ruofeng Tong<sup>1</sup>, Shuangcai Yang<sup>2</sup>, Yao Li<sup>2</sup>, Bailin An<sup>2</sup>, Qilong Kou<sup>2</sup>

<sup>1</sup><i>Zhejiang University, China</i>

<sup>2</sup><i>Tencent</i>

<img src="{{ "/assets/img/content/post-example/CSTN/CSTN.jpg" | absolute_url }}" alt="bay" class="post-pic"/>
<br />

## Abstraction

We present a novel learning method to predict the cloth deformation for skeleton-based characters with a two-stream network. The characters processed in our approach are not limited to humans, and can be other skeletal-based representations of non-human targets such as fish or pets. We use a novel network architecture which consists of skeleton-based and mesh-based residual networks to learn the coarse and wrinkle features as the overall residual from the template cloth mesh. Our network is used to predict the deformation for loose or tight-fitting clothing or dresses. We ensure that the memory footprint of our network is low, and thereby result in reduced storage and computational requirements. In practice, our prediction for a single cloth mesh for the skeleton-based character takes about 7 milliseconds on an NVIDIA GeForce RTX 3090 GPU. Compared with prior methods, our network can generate fine deformation results with details and wrinkles.

## Results
To evaluate that our network can process more complex and different characters, we applied our network on non-human characters such as a monster, a dolphin, and a cat. The monster character has a skeleton similar to the human character, while the dolphin and the cat have different skeletons. The dolphin character has no leg joints, while the cat model has four legs without hands. We can also simulate the cloth deformation on these characters. The monster character wears a loose robe, and the dolphin and the cat wear tight-fitting clothes designed for these characters.

<img src="{{ "/assets/img/content/post-example/CSTN/0.jpg" | absolute_url }}" alt="bay" class="post-pic"/>

<img src="{{ "/assets/img/content/post-example/CSTN/12.jpg" | absolute_url }}" alt="bay" class="post-pic"/>

## Video
Here is the demo video.

<iframe width="560" height="315" src="https://www.youtube.com/embed/41yzneqq-oE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>