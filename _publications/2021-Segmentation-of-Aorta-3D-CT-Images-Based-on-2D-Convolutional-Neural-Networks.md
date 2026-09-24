---
title: "Segmentation of Aorta 3D CT Images Based on 2D Convolutional Neural Networks"
collection: publications
permalink: /publications/2021-Segmentation-of-Aorta-3D-CT-Images-Based-on-2D-Convolutional-Neural-Networks
date: 2021-10-18
venue: 'Electronics, Multidisciplinary Digital Publishing Institute'
---

Recommended citation: Simone Bonechi, Paolo Andreini, Alessandro Mecocci, Nicola Giannelli, Franco Scarselli, Eugenio Neri, Monica Bianchini, and Giovanna Maria Dimitri. Segmentation of aorta 3D CT images based on 2D convolutional neural networks. Electronics, 10(20):2559, 2021. ([BibTex](data:application/octet-stream;charset=utf-8;base64,QGFydGljbGV7Qm9uZWNoaTIwMjFTZWdtZW50YXRpb25PQSwKICB0aXRsZT17U2VnbWVudGF0aW9uIG9mIEFvcnRhIDNEIENUIEltYWdlcyBCYXNlZCBvbiAyRCBDb252b2x1dGlvbmFsIE5ldXJhbCBOZXR3b3Jrc30sCiAgYXV0aG9yPXtTaW1vbmUgQm9uZWNoaSBhbmQgUGFvbG8gQW5kcmVpbmkgYW5kIEFsZXNzYW5kcm8gTWVjb2NjaSBhbmQgTi4gR2lhbm5lbGxpIGFuZCBGcmFuY28gU2NhcnNlbGxpIGFuZCBFdWdlbmlvIE5lcmkgYW5kIE1vbmljYSBCaWFuY2hpbmkgYW5kIEdpb3Zhbm5hIE1hcmlhIERpbWl0cml9LAogIGpvdXJuYWw9e0VsZWN0cm9uaWNzfSwKICB5ZWFyPXsyMDIxfQp9))
{: style="text-align: justify"}

### Abstract
The automatic segmentation of the aorta can be extremely useful in clinical practice, allowing the diagnosis of numerous pathologies to be sped up, such as aneurysms and dissections, and allowing rapid reconstructive surgery, essential in saving patients’ lives. In recent years, the success of Deep Learning (DL)-based decision support systems has increased their popularity in the medical field. However, their effective application is often limited by the scarcity of training data. In fact, collecting large annotated datasets is usually difficult and expensive, especially in the biomedical domain. In this paper, an automatic method for aortic segmentation, based on 2D convolutional neural networks (CNNs), using 3D CT (computed axial tomography) scans as input is presented. For this purpose, a set of 153 CT images was collected and a semi-automated approach was used to obtain their 3D annotations at the voxel level. Although less accurate, the use of a semi-supervised labeling technique instead of a full supervision proved necessary to obtain enough data in a reasonable amount of time. The 3D volume was analyzed using three 2D segmentation networks, one for each of the three CT views (axial, coronal and sagittal). Two different network architectures, U-Net and LinkNet, were used and compared. The main advantages of the proposed method lie in its ability to work with a reduced number of data even with noisy targets. In addition, analyzing 3D scans based on 2D slices allows for them to be processed even with limited computing power. The results obtained are promising and show that the neural networks employed can provide accurate segmentation of the aorta.
{: style="text-align: justify"}

You can find the full paper [here](https://www.mdpi.com/2079-9292/10/20/2559)
{: style="text-align: justify"}
