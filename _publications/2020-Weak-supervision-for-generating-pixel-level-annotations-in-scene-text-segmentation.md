---
title: "Weak supervision for generating pixel-level annotations in scene text segmentation"
collection: publications
permalink: /publications/2020-Weak-supervision-for-generating-pixel-level-annotations-in-scene-text-segmentation
date: 2020-06-04
venue: 'Pattern Recognition Letters, Elsevier'
---

Recommended citation: Simone Bonechi, Monica Bianchini, Franco Scarselli, and Paolo Andreini. Weak supervision for generating pixel–level annotations in scene text segmentation. Pattern Recognition Letters, 138:1–7, 2020 ([BibTex](http://clem.diism.unisi.it/~coco_ts/cite_MLT_S.bib))
{: style="text-align: justify"}

### Abstract
Providing pixel–level supervisions for scene text segmentation is inherently difficult and costly, so that only few small datasets are available for this task. To face the scarcity of training data, previous approaches based on Convolutional Neural Networks (CNNs) rely on the use of a synthetic dataset for pre–training. However, synthetic data cannot reproduce the complexity and variability of natural images. In this work, we propose to use a weakly supervised learning approach to reduce the domain–shift between synthetic and real data. Leveraging the bounding–box supervision of the COCO–Text and the MLT datasets, we generate weak pixel–level supervisions of real images. In particular, the COCO–Text–Segmentation (COCO_TS) and the MLT–Segmentation (MLT_S) datasets are created and released. These two datasets are used to train a CNN, the Segmentation Multiscale Attention Network (SMANet), which is specifically designed to face some peculiarities of the scene text segmentation task. The SMANet is trained end–to–end on the proposed datasets, and the experiments show that COCO_TS and MLT_S are a valid alternative to synthetic images, allowing to use only a fraction of the training samples, with a significant improvement in performance.
{: style="text-align: justify"}

You can find the full paper [here](https://www.sciencedirect.com/science/article/pii/S0167865520302415)
{: style="text-align: justify"}
