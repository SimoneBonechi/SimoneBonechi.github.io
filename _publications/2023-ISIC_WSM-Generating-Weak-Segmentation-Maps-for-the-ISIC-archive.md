---
title: "ISIC_WSM: Generating Weak Segmentation Maps for the ISIC archive"
collection: publications
permalink: /publications/2023-ISIC_WSM-Generating-Weak-Segmentation-Maps-for-the-ISIC-archive
date: 2023-02-28
venue: 'Neurocomputing, Elsevier'
---

Recommended citation: Simone Bonechi, ISIC_WSM: Generating Weak Segmentation Maps for the ISIC archive, Neurocomputing, Volume 523, Pages 69-80, ISSN 0925-2312, 2023, https://doi.org/10.1016/j.neucom.2022.12.033. ([BibTex](http://clem.diism.unisi.it/~coco_ts/cite_ISIC_WSM_Neurocomputing.bib))
{: style="text-align: justify"}

### Abstract
Recognizing skin cancer in time could greatly increase patients’ chances of recovery. For this reason, in recent years, numerous decision support systems have been proposed to help dermatologists in this diagnosis. These systems are generally based on Convolutional Neural Networks and are used for both segmentation and classification of lesions. Although their main goal is to correctly recognize the lesions’ type, the preliminary segmentation step has been shown to increase the performance of the classifier. In fact, this is not surprising because physicians also use information on the shape of the lesion to make a diagnosis. Thanks to the ISIC archive, a huge number of skin lesion images, along with the corresponding metadata (type, position, dimension, etc.), are publicly available to train a deep neural network, but, unfortunately, only a small fraction of them are labeled for segmentation. To overcome this limitation, in this paper, a weak supervised approach is proposed to extract the segmentation label maps from the entire ISIC archive. Moreover, to demonstrate the quality of the proposed approach, the generated supervisions were first compared with those available in ISIC and, then, used to train a segmentation network, whose performance was evaluated against that obtained using only the small set of ISIC label maps. To foster reproducibility and to promote future research in lesion segmentation and classification, the generated ISIC Weak Segmentation Map (ISIC_WSM) dataset has been released. As far as we know, this is the first dataset that contains segmentation supervisions for clinical images of skin lesions.
{: style="text-align: justify"}

You can find the full paper [here](https://www.sciencedirect.com/science/article/pii/S0925231222015302)
{: style="text-align: justify"}
