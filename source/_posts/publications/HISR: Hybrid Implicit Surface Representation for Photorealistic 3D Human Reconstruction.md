---
title: Weakly supervised region proposal network and object detection
category: publications
cover: assert/1304db003eb50e1c747a6369806a591.jpg
---

### Summary
The Convolutional Neural Network (CNN) based region proposal generation method (ie region proposal network), trained using bounding box annotations, is an essential component in modern fully supervised object detectors. However, Weakly Supervised Object Detection (WSOD) has not benefited from CNN-based proposal generation due to the absence of bounding box annotations, and is relying on standard proposal generation methods such as selective search. In this paper, we propose a weakly supervised region proposal network which is trained using only image-level annotations. The weakly supervised region proposal network consists of two stages. The first stage evaluates the objectness scores of sliding window boxes by exploiting the low-level information in CNN and the second stage refines the proposals from the first stage using a region-based CNN classifier. Our proposed region proposal network is suitable for WSOD, can be plugged into a WSOD network easily, and can share its convolutional computations with the WSOD network. Experiments on the PASCAL VOC and ImageNet detection datasets show that our method achieves the state-of-the-art performance for WSOD with performance gain of about 3% on average.

### Author
Peng Tang, Xinggang Wang, Angtian Wang, Yongluan Yan, Wenyu Liu, Junzhou Huang, Alan Yuille

### Publication
Proceedings of the European conference on computer vision (ECCV)

### Paper
[paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Peng_Tang_Weakly_Supervised_Region_ECCV_2018_paper.pdf)
