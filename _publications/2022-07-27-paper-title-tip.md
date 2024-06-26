---
title: "Unsupervised High-Resolution Portrait Gaze Correction and Animation"
collection: publications
permalink: /publication/2022-07-27-paper-title-tip
excerpt: ''
date: 2022-07-27
venue: 'IEEE Transactions on Image Processing'
paperurl: 'https://ieeexplore.ieee.org/document/9843921'
citation: 'Jichao Zhang; Jingjing Chen; Hao Tang; Enver Sangineto; <b>Peng Wu</b>; Yan Yan; Nicu Sebe; Wei Wang, &quot;Unsupervised High-Resolution Portrait Gaze Correction and Animation;. <i>IEEE Transactions on Image Processing</i>, 2022, doi: 10.1109/TIP.2022.3191852.'
---
Abstract
===
This paper proposes a gaze correction and animation method for high-resolution, unconstrained portrait images, which can be trained without the gaze angle and the head pose annotations. Common gaze-correction methods usually require annotating training data with precise gaze, and head pose information. Solving this problem using an unsupervised method remains an open problem, especially for high-resolution face images in the wild, which are not easy to annotate with gaze and head pose labels. To address this issue, we first create two new portrait datasets: CelebGaze ( 256×256 ) and high-resolution CelebHQGaze ( 512×512 ). Second, we formulate the gaze correction task as an image inpainting problem, addressed using a Gaze Correction Module (GCM) and a Gaze Animation Module (GAM). Moreover, we propose an unsupervised training strategy, i.e., Synthesis-As-Training, to learn the correlation between the eye region features and the gaze angle. As a result, we can use the learned latent space for gaze animation with semantic interpolation in this space. Moreover, to alleviate both the memory and the computational costs in the training and the inference stage, we propose a Coarse-to-Fine Module (CFM) integrated with GCM and GAM. Extensive experiments validate the effectiveness of our method for both the gaze correction and the gaze animation tasks in both low and high-resolution face datasets in the wild and demonstrate the superiority of our method with respect to the state of the art.

[Download paper here](https://ieeexplore.ieee.org/document/9843921)
