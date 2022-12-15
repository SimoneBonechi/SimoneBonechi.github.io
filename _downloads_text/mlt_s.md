---
title: "MLT_S"
collection: downloads_text
permalink: /downloads/mlt_s
excerpt: 'Multilingual Scene Text Segmentation Dataset'
carousels:
  - images:
    - image: ../images/img_mlt_1.png
    - image: ../images/img_mlt_4.png
    - image: ../images/img_mlt_5.png
    - image: ../images/img_mlt_6.png
---

## Multilingual Scene Text Segmentation (MLT_S) Dataset

{% include carousel.html height="40" unit="%" duration="7" images=carousels %}
<br>
The MLT_S dataset ([MLT_S_labels.zip (102.0 MB)](http://clem.diism.unisi.it/~coco_ts/download_mlt_s.php)) contains 6896 (5540 from the training set and 1356 from the validation set) label maps for the [MLT](https://rrc.cvc.uab.es/?ch=8&com=introduction) dataset, while the original images can be downloaded separately at the [MLT dataset webpage](https://rrc.cvc.uab.es/?ch=8&com=downloads). The supervision is obtained from the available bounding–boxes of the MLT dataset exploiting a weakly supervised algorithm. See [Implementation](http://clem.diism.unisi.it/~coco_ts/implementation.html) for more details.
{: style="text-align: justify"}

### Annotations Description
The semantic label maps are saved as .png images with the same name as the original images of MLT.
Pixel values of the provided annotation are defined as follows:
*  0 - Background
*  1 - Foreground (Text)
*  255 - Uncertain
{: style="text-align: justify"}

### Terms of use
The annotations in this dataset are licensed under a [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode) and by downloading the annotations you confirm that you agree to this terms of use.
{: style="text-align: justify"}

If you use this dataset for your research, please cite the following papers:
* [[bib](http://clem.diism.unisi.it/~coco_ts/cite_COCO_TS.bib)] Bonechi, S., Andreini, P., Bianchini, M., & Scarselli, F. (2019, September). COCO_TS Dataset: Pixel–Level Annotations Based on Weak Supervision for Scene Text Segmentation. In International Conference on Artificial Neural Networks (pp. 238-250). Springer, Cham.
* [[bib](http://clem.diism.unisi.it/~coco_ts/cite_MLT_S.bib)] Bonechi, S., Andreini, P., Bianchini, M., & Scarselli, F. (2019). Weak Supervision for Generating Pixel-Level Annotations in Scene Text Segmentation. Pattern Recognition Letters, 2020, ISSN 0167-8655, [https://doi.org/10.1016/j.patrec.2020.06.023](https://doi.org/10.1016/j.patrec.2020.06.023)
{: style="text-align: justify"}
