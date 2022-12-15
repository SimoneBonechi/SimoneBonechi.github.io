---
title: "ISIC_WSM"
collection: downloads_skin_lesio
permalink: /downloads/isic_wsm
excerpt: 'ISIC Weak Segmentation Maps'
carousels:
  - images:
    - image: ../images/img_isic_1.png
    - image: ../images/img_isic_2.png
    - image: ../images/img_isic_3.png
    - image: ../images/img_isic_4.png
---

## Coco-Text Segmentation (COCO_TS) Dataset

{% include carousel.html height="35" unit="%" duration="7" images=carousels %}
<br>
The ISIC_WSM dataset ([ISIC_WSM_labels.zip (198 MB)](http://clem.diism.unisi.it/~coco_ts/download_isic_wsm.php)) provides pixel–level supervisions for a subset of images (43885) from the [ISIC](https://www.isic-archive.com/#!/topWithHeader/wideContentTop/main) archive, while the original images can be downloaded separately at the [ISIC website](https://www.isic-archive.com/#!/topWithHeader/onlyHeaderTop/gallery?filter=%5B%5D). The supervision is obtained from the available bounding–boxes of the COCO–Text dataset exploiting a weakly supervised algorithm. See the [paper](https://www.esann.org/sites/default/files/proceedings/2022/ES2022-46.pdf) for more details.
{: style="text-align: justify"}

### Annotations Description
The semantic label maps are saved as .png images with the same name as the original images of the ISIC archive.
Pixel values of the provided annotation are defined as follows:
*  0 - Background
*  1 - Foreground (Lesion)
*  255 - Uncertain
{: style="text-align: justify"}

### Terms of use
The annotations in this dataset are licensed under a [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode) and by downloading the annotations you confirm that you agree to this terms of use.
{: style="text-align: justify"}

If you use this dataset for your research, please cite the following papers:
* [[bib](http://clem.diism.unisi.it/~coco_ts/cite_ISIC_WSM_ESANN.bib)] Bonechi, S. (2022, November). A weakly supervised approach to skin lesion segmentation. In ESANN 2022 proceedings European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning.
* [[bib]()] Bonechi, S.. ISIC_WSM: Generating Weak Segmentation Maps for the ISIC archive. To be published in Neurocomputing.
{: style="text-align: justify"}
