---
title: "Semi-supervised Method of Landmark Detection of hand joints"
collection: projects
excerpt: "We implemented a semi-supervised method for landmark detection, and apply the method to a new task, landmark detection of standard X-ray views of hand."
date: 2020.09.01
layout: single
permalink: /projects/semi-supervised-method-of-landmark-detection-of-hand-joints
---

We implemented a semi-supervised method for landmark detection, following [3FabRec: Fast Few-shot Face alignment by Reconstruction](https://arxiv.org/abs/1911.10448). This method used an adversarial autoencoder to generate images and learn the potential features, in order to deal with imprecise and inconsistent annotations in datasets.

We apply the method to a new task, landmark detection of standard X-ray views of hand, by refining the SSIM index for particular X-ray pictures.
More details can be found in this [Chinese version report](/files/Detection_Term_Project.pdf).

Source code is available at [github](https://github.com/BingyangWu/Landmark-Dectection).

![](/images/projects/landmark_1000.jpg)

