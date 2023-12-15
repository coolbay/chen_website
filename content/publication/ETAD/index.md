---
title: "ETAD: Training Action Detection End to End on a Laptop"
publication_types:
  - "1"
authors:
  - Shuming Liu
  - Mengmeng Xu
  - admin
  - Xu Zhao
  - Bernard Ghanem
publication: IEEE Conference on Computer Vision and Pattern Recognition Workshop (**CVPRW**), 2023. **<span style="color:red">[Oral]</span>**
publication_short: CVPRW 2023. **<span style="color:red">[Oral]</span>**
abstract: Untrimmed video understanding such as temporal action detection (TAD) often suffers from the pain of huge demand for computing resources. Because of long video durations and limited GPU memory, most action detectors can only operate on pre-extracted features rather than the original videos, and they still require a lot of computation to achieve high detection performance. To alleviate the heavy computation problem in TAD, in this work, we first propose an efficient action detector with detector proposal sampling, based on the observation that performance saturates at a small number of proposals. This detector is designed with several important techniques, such as LSTM-boosted temporal aggregation and cascaded proposal refinement to achieve high detection quality as well as low computational cost. To enable joint optimization of this action detector and the feature encoder, we also propose encoder gradient sampling, which selectively back-propagates through video snippets and tremendously reduces GPU memory consumption. With the two sampling strategies and the effective detector, we build a unified framework for efficient end-to-end temporal action detection (ETAD), making real-world untrimmed video understanding tractable. ETAD achieves state-of-the-art performance on both THUMOS-14 and ActivityNet-1.3. Interestingly, on ActivityNet-1.3, it reaches 37.78% average mAP, while only requiring 6 mins of training time and 1.23 GB memory based on pre-extracted features. With end-to-end training, it reduces the GPU memory footprint by more than 70% with even higher performance (38.21% average mAP), as compared with traditional end-to-end methods.
draft: false
featured: false
tags:
  - Deep learning
  - Temporal action detection
  - Sampling
  - LSTM
slides: ""
url_pdf: https://arxiv.org/pdf/2205.07134.pdf
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: ""
projects: []
date: 2023-06-02T00:00:02.020Z
url_slides: ""
publishDate: 2023
url_poster: ""
url_code: ""
---
