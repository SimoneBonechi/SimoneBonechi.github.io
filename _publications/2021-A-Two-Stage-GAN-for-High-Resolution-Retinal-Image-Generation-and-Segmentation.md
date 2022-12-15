---
title: "A Two-Stage GAN for High-Resolution Retinal Image Generation and Segmentation"
collection: publications
permalink: /publications/2021-A-Two-Stage-GAN-for-High-Resolution-Retinal-Image-Generation-and-Segmentation
date: 2021-12-25
venue: 'Electronics, Multidisciplinary Digital Publishing Institute'
---

Recommended citation: Paolo Andreini, Giorgio Ciano, Simone Bonechi, Caterina Graziani, Veronica Lachi, Alessandro Mecocci, Andrea Sodi, Franco Scarselli, and Monica Bianchini.
A two-stage GAN for high-resolution retinal image generation and segmentation. Electronics, 11(1):60, 2021. ([BibTex](http://clem.diism.unisi.it/~coco_ts/electronics-v11-i01_20221215.bib))
{: style="text-align: justify"}

### Abstract
In this paper, we use Generative Adversarial Networks (GANs) to synthesize high-quality retinal images along with the corresponding semantic label-maps, instead of real images during training of a segmentation network. Different from other previous proposals, we employ a two-step approach: first, a progressively growing GAN is trained to generate the semantic label-maps, which describes the blood vessel structure (i.e., the vasculature); second, an image-to-image translation approach is used to obtain realistic retinal images from the generated vasculature. The adoption of a two-stage process simplifies the generation task, so that the network training requires fewer images with consequent lower memory usage. Moreover, learning is effective, and with only a handful of training samples, our approach generates realistic high-resolution images, which can be successfully used to enlarge small available datasets. Comparable results were obtained by employing only synthetic images in place of real data during training. The practical viability of the proposed approach was demonstrated on two well-established benchmark sets for retinal vessel segmentation—both containing a very small number of training samples—obtaining better performance with respect to state-of-the-art techniques.
{: style="text-align: justify"}

You can find the full paper [here](https://www.mdpi.com/2079-9292/11/1/60)
{: style="text-align: justify"}
