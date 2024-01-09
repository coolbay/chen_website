---
title: "Dr2Net: Dynamic Reversible Dual-Residual Networks for Memory-Efficient Finetuning"
publication_types:
  - "2"
authors:
  - admin
  - Shuming Liu
  - Karttikeya Mangalam
  - Guocheng Qian
  - Fatimah Zohra
  - Abdulmohsen Alghannam
  - Jitendra Malik
  - Bernard Ghanem
publication: arXiv:2401.04105
publication_short: arxiv 2024
abstract: "Large pretrained models are increasingly crucial in modern computer vision tasks. These models are typically used in downstream tasks by end-to-end finetuning, which is highly memory-intensive for tasks with high-resolution data, e.g., video understanding, small object detection, and point cloud analysis. In this paper, we propose Dynamic Reversible Dual-Residual Networks, or Dr2Net, a novel family of network architectures that acts as a surrogate network to finetune a pretrained model with substantially reduced memory consumption. Dr2Net contains two types of residual connections, one maintaining the residual structure in the pretrained models, and the other making the network reversible. Due to its reversibility, intermediate activations, which can be reconstructed from output, are cleared from memory during training. We use two coefficients on either type of residual connections respectively, and introduce a dynamic training strategy that seamlessly transitions the pretrained model to a reversible network with much higher numerical precision. We evaluate Dr2Net on various pretrained models and various tasks, and show that it can reach comparable performance to conventional finetuning but with significantly less memory usage."

draft: false
featured: true
tags:
  - Deep learning
  - Computer vision
  - Reversible networks
  - Memory-efficient finetuning
slides: ""
url_pdf: https://arxiv.org/pdf/2401.04105.pdf
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
date: 2024-01-04T00:00:02.020Z
url_slides: ""
publishDate: 2024
url_poster: ""
url_code: ""
---
