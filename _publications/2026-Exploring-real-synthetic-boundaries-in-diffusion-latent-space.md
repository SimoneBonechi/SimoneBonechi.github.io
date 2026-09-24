---
title: "Exploring real-synthetic boundaries in diffusion latent space"
collection: publications
permalink: /publications/2026-Exploring-real-synthetic-boundaries-in-diffusion-latent-space
date: 2026-01-01
venue: 'Computer Vision and Image Understanding, Elsivier'
---

Recommended citation:
Simone Bonechi, Paolo Andreini, Barbara Toniella Corradini. Exploring real-synthetic boundaries in diffusion latent space. Computer Vision and Image Understanding, 104815. 2026. ([BibTex](http://clem.diism.unisi.it/~coco_ts/S1077314226001827.bib))
{: style="text-align: justify"}

### Abstract
This study investigates whether pre-trained Diffusion Models (DMs) inherently encode in a different way real and synthetic objects in an image within their latent representations. While DMs have achieved state-of-the-art performance in generative modeling and demonstrated rich semantic representations despite being trained solely with denoising objectives, their widespread accessibility raises critical concerns about detecting AI-generated content. Motivated by the intuition that a model must implicitly capture the distribution of real data to generate it, we hypothesized that real and synthetic objects are mapped to separable regions of the latent space. To test this hypothesis, we conduct a systematic analysis using a pre-trained DM to encode both real objects from the COCO and the Pascal VOC datasets and synthetic samples from DALL-E 3, Midjourney, and Stable Diffusion. We extract internal representations from different layers and evaluate their discriminative capacity through distance-based metrics and linear probing. Our findings reveal that decoder features, in particular, induce statistically meaningful representational differences between real and synthetic objects. The results show that these representations support high linear-probing accuracy under the evaluated experimental conditions, suggesting that pre-trained diffusion representations contain useful signals for distinguishing real and synthetic content.
{: style="text-align: justify"}

You can find the full paper [here](https://www.sciencedirect.com/science/article/pii/S1077314226001827)
{: style="text-align: justify"}
