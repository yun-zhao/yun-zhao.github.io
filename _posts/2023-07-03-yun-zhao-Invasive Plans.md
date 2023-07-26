---
layout: post
title: "Using Convolutional and Rrcurrent Neural Netowrks (CNN & RNN) for Invasive Plants Detection"
date: 2023-07-20
---

## Summary
This study develops a novel deep learning model using a unmanned aerial vehicle (UAV) and associated
**geographic information system (GIS)** to detect and identify invasive Phragmites australis (PA) in its early growth stage.
This novel network, integrating a **convolutional neural network (CNN)** and a **recurrent neural network (RNN)**, proves to be
an efficient and accurate method to detect PA in time series UAS images. CNN is good at extracting spatial features on
images, and RNN excels in processing temporal features. Temporal features of the time series UAS images are extracted
and employed with spatial features for the classification by an RNN model. Experiments are conducted in Nature Conservancy’s
Emiquon Preserve. The proposed network achieves the highest performance compared with other IP detection
models. With its high generalization ability, the proposed model might find more applications in precision agriculture and
land conservation areas.


## Illustration

The below figure demonstrates the architecture of the proposed network.

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/Novel_CNN-1.png" alt="Description of the image" width="200">
</div>


Here is the evaluation results for the propossed methods and ResNet50 on the data set.

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/Novel_CNN-2.png" alt="Description of the image" width="700">
</div>

This below figure is an visualization of how the predicted results (outlined in yellow) match the ground truth (outlined in red).

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/Novel_CNN-3.PNG" alt="Description of the image" width="500">
</div>


## Links

For full peer-reviewed published paper, click [here](https://www.dropbox.com/scl/fi/se2e4q7rqxynl5mfdtygu/A-novel-invasive-plant-detection-approach-using-time-series-images-from-unmanned-aerial-systems-based-on-convolutional-and-recurrent-neural-networks.pdf?rlkey=yyt3x57ur8tey2r7m51an6y99&dl=0). 
