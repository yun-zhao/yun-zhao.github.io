---
layout: post
title: "Two-level K-nearest neighbors approach for invasive plants detection and classification"
date: 2021-05-04
thumb: "https://yun-zhao.github.io/Proj_File/KNN.jpg"
---

## Summary
This study proposes and develops a novel **two-level K-nearest neighbors (TLKNN) algorithm**
to detect weed in agricultral land from drone field images. To build the architecture, a **deep convolutional neural
network (CNN)** is first used to extract the features from the patch field image and a kernel map function is
utilized to obtain the kernel features. Two feature sets are then fed to train two **K-nearest neighbor (KNN)
models**. Finally, the final classification is determined by the selection results by KNN models. Experimental results indicate the proposed TLKNN algorithm achieves better
classification performance and reaches the highest accuracy, recall rate, precision rate, and F1-score.


## Illustration

The below figure demonstrates the architecture of the proposed network.

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/KNN-1.jpg" alt="Description of the image" width="200">
</div>


Here is the evaluation results comparision among the proposed method, ConvNets, ResNet, and KNN on an unbalanced data set.

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/KNN-2.PNG" alt="Description of the image" width="800">
</div>


## Links

For full peer-reviewed published paper, click [here](https://www.dropbox.com/scl/fi/zbttokkucv0pemnfgyfi2/Two-level-K-nearest-neighbors-approach-for-invasive-plants-detectio.pdf?rlkey=9rpn020xzecbserl5zbiwh8bt&dl=0). 
