---
title: "A Unified Continual Learning Framework with General Parameter-Efficient Tuning"
publication_types:
  - "1"
authors:
  - Qiankun Gao, 
  - admin, 
  - Yifan Sun, 
  - Teng Xi, 
  - Gang Zhang, 
  - Bernard Ghanem, 
  - Jian Zhang


publication: International Conference on Computer Vision (ICCV), 2023
publication_short: ICCV 2023
abstract: "The 'pre-training → downstream adaptation' presents both new opportunities and challenges for Continual Learning (CL). Although the recent state-of-the-art in CL is achieved through Parameter-Efficient-Tuning (PET) adaptation paradigm, only prompt has been explored, limiting its application to Transformers only. In this paper, we position prompting as one instantiation of PET, and propose a unified CL framework with general PET, dubbed as Learning-Accumulation-Ensemble (LAE). PET, e.g., using Adapter, LoRA, or Prefix, can adapt a pre-trained model to downstream tasks with fewer parameters and resources. Given a PET method, our LAE framework incorporates it for CL with three novel designs. 1) Learning: the pre-trained model adapts to the new task by tuning an online PET module, along with our adaptation speed calibration to align different PET modules, 2) Accumulation: the task-specific knowledge learned by the online PET module is accumulated into an offline PET module through momentum update, 3) Ensemble: During inference, we respectively construct two experts with online/offline PET modules (which are favored by the novel/historical tasks) for prediction ensemble. We show that LAE is compatible with a battery of PET methods and gains strong CL capability. For example, LAE with Adaptor PET surpasses the prior state-of-the-art by 1.3% and 3.6% in last-incremental accuracy on CIFAR100 and ImageNet-R datasets, respectively."

draft: false
featured: true
tags:
  - Deep learning
  - Continual learning
  - Parameter efficient tuning
slides: ""
url_pdf: https://arxiv.org/pdf/2303.10070.pdf
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
date: 2023-07-15T00:00:02.020Z
url_slides: ""
publishDate: 2023
url_poster: ""
url_code: 
---
