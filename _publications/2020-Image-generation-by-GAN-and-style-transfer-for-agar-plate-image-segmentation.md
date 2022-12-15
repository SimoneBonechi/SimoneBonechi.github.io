---
title: "Image generation by GAN and style transfer for agar plate image segmentation"
collection: publications
permalink: /publications/2020-Image-generation-by-GAN-and-style-transfer-for-agar-plate-image-segmentation
date: 2020-02-01
venue: 'Computer methods and programs in biomedicine, Elsevier'
---

Recommended citation: Paolo Andreini, Simone Bonechi, Monica Bianchini, Alessandro Mecocci, and Franco Scarselli. Image generation by gan and style transfer for agar plate image
segmentation. Computer methods and programs in biomedicine, 184:105268, 2020. ([BibTex](data:application/octet-stream;charset=utf-8;base64,QGFydGljbGV7QW5kcmVpbmkyMDE5SW1hZ2VHQiwKICB0aXRsZT17SW1hZ2UgZ2VuZXJhdGlvbiBieSBHQU4gYW5kIHN0eWxlIHRyYW5zZmVyIGZvciBhZ2FyIHBsYXRlIGltYWdlIHNlZ21lbnRhdGlvbn0sCiAgYXV0aG9yPXtQYW9sbyBBbmRyZWluaSBhbmQgU2ltb25lIEJvbmVjaGkgYW5kIE1vbmljYSBCaWFuY2hpbmkgYW5kIEFsZXNzYW5kcm8gTWVjb2NjaSBhbmQgRnJhbmNvIFNjYXJzZWxsaX0sCiAgam91cm5hbD17Q29tcHV0ZXIgbWV0aG9kcyBhbmQgcHJvZ3JhbXMgaW4gYmlvbWVkaWNpbmV9LAogIHllYXI9ezIwMTl9LAogIHZvbHVtZT17MTg0fSwKICBwYWdlcz17CiAgICAgICAgICAxMDUyNjgKICAgICAgICB9Cn0=))
{: style="text-align: justify"}

### Abstract
Background and objectives: Deep learning models and specifically Convolutional Neural Networks (CNNs) are becoming the leading approach in many computer vision tasks, including medical image analysis. Nevertheless, the CNN training usually requires large sets of supervised data, which are often difficult and expensive to obtain in the medical field. To address the lack of annotated images, image generation is a promising method, which is becoming increasingly popular in the computer vision community. In this paper, we present a new approach to the semantic segmentation of bacterial colonies in agar plate images, based on deep learning and synthetic image generation, to increase the training set size. Indeed, semantic segmentation of bacterial colony is the basis for infection recognition and bacterial counting in Petri plate analysis.

Methods: A convolutional neural network (CNN) is used to separate the bacterial colonies from the background. To face the lack of annotated images, a novel engine is designed - which exploits a generative adversarial network to capture the typical distribution of the bacterial colonies on agar plates - to generate synthetic data. Then, bacterial colony patches are superimposed on existing background images, taking into account both the local appearance of the background and the intrinsic opacity of the bacterial colonies, and a style transfer algorithm is used for further improve visual realism.

Results: The proposed deep learning approach has been tested on the only public dataset available with pixel-level annotations for bacterial colony semantic segmentation in agar plates. The role of including synthetic data in the training of a segmentation CNN has been evaluated, showing how comparable performances can be obtained with respect to the use of real images. Qualitative results are also reported for a second public dataset in which the segmentation annotations are not provided.

Conclusions: The use of a small set of real data, together with synthetic images, allows obtaining comparable results with respect to using a complete set of real images. Therefore, the proposed synthetic data generator is able to address the scarcity of biomedical data and provides a scalable and cheap alternative to human ground-truth supervision.
{: style="text-align: justify"}

You can find the full paper [here](https://pubmed.ncbi.nlm.nih.gov/31891902/)
{: style="text-align: justify"}
