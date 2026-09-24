---
title: "An analysis of pre-trained stable diffusion models through a semantic lens"
collection: publications
permalink: /publications/2025-An-analysis-of-pre-trained-stable-diffusion-models-through-a-semantic-lens
date: 2025-01-01
venue: 'Neurocomputing, Elsevier'
---

Recommended citation:
Simone Bonechi, Paolo Andreini, Barbara Toniella Corradini, Franco Scarselli. An analysis of pre-trained stable diffusion models through a semantic lens. Neurocomputing, 128846. 2025. ([BibTex](http://clem.diism.unisi.it/~coco_ts/S0925231224016175.bib))
{: style="text-align: justify"}

### Abstract
Recently, generative models for images have garnered remarkable attention, due to their effective generalization ability and their capability to generate highly detailed and realistic content. Indeed, the success of generative networks (e.g., BigGAN, StyleGAN, Diffusion Models) has driven researchers to develop increasingly powerful models. As a result, we have observed an unprecedented improvement in terms of both image resolution and realism, making generated images indistinguishable from real ones. In this work, we focus on a family of generative models known as Stable Diffusion Models (SDMs), which have recently emerged due to their ability to generate images in a multimodal setup (i.e., from a textual prompt) and have outperformed adversarial networks by learning to reverse a diffusion process. Given the complexity of these models that makes it hard to retrain them, researchers started to exploit pre-trained SDMs to perform downstream tasks (e.g., classification and segmentation), where semantics plays a fundamental role. In this context, understanding how well the model preserves semantic information may be crucial to improve its performance.
This paper presents an approach aimed at providing insights into the properties of a pre-trained SDM through the semantic lens. In particular, we analyze the features extracted by the U-Net within a SDM to explore whether and how the semantic information of an image is preserved in its internal representation. For this purpose, different distance measures are compared, and an ablation study is performed to select the layer (or combination of layers) of the U-Net that best preserves the semantic information. We also seek to understand whether semantics are preserved when the image undergoes simple transformations (e.g., rotation, flip, scale, padding, crop, and shift) and for a different number of diffusion denoising steps. To evaluate these properties, we consider popular benchmarks for semantic segmentation tasks (e.g., COCO, and Pascal-VOC). Our experiments suggest that the first encoder layer at 16×16 resolution effectively preserves semantic information. However, increasing inference steps (even for a minimal amount of noise) and applying various image transformations can affect the diffusion U-Net’s internal feature representation. Additionally, we propose some examples taken from a video benchmark (DAVIS dataset), where we investigate if an object instance within a video preserves its internal representation even after several frames. Our findings suggest that the internal object representation remains consistent across multiple frames in a video, as long as the configuration changes are not excessive.
{: style="text-align: justify"}

You can find the full paper [here](https://www.sciencedirect.com/science/article/pii/S0925231224016175)
{: style="text-align: justify"}
