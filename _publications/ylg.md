---
title: "Your Local GAN: Designing Two Dimensional Local Attention Mechanisms for Generative Models"
collection: publications
permalink: /publication/ylg
excerpt: ''
status: 'Published'
venue: 'CVPR 2020'
paperurl: 'https://arxiv.org/abs/1911.12287'
code: 'https://github.com/giannisdaras/ylg'
authors: '<strong>Giannis Daras</strong>, Augustus Odena, Han Zhang, Alexandros G. Dimakis'
date: 2019-11-27
---
We introduce a new local sparse attention layer that preserves two-dimensional geometry and locality. We show that by just replacing the dense attention layer of SAGAN with our construction, we obtain very significant FID, Inception score and pure visual improvements. FID score is improved from 18.65 to **15.94** on ImageNet, keeping all other parameters the same. The sparse attention patterns that we propose for our new layer are designed using a novel information theoretic criterion that uses information flow graphs. We also present a novel way to invert Generative Adversarial Networks with attention. Our method extracts from the attention layer of the discriminator a saliency map, which we use to construct a new loss function for the inversion. This allows us to visualize the newly introduced attention heads and show that they indeed capture interesting aspects of two-dimensional geometry of real images.


## Results after training YLG for 1M steps on ImageNet
![](../images/ylg_collage.jpg)
