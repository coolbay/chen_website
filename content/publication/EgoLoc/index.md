---
title: "EgoLoc: Revisiting 3D Object Localization from Egocentric Videos with Visual Queries"
publication_types:
  - "1"
authors:
  - Jinjie Mai
  - Abdullah Hamdi
  - Silvio Giancola
  - admin
  - Bernard Ghanem

publication: International Conference on Computer Vision (ICCV), 2023
publication_short: ICCV 2023
abstract: "With the recent advances in video and 3D understanding, novel 4D spatio-temporal methods fusing both concepts have emerged. Towards this direction, the Ego4D Episodic Memory Benchmark proposed a task for Visual Queries with 3D Localization (VQ3D). Given an egocentric video clip and an image crop depicting a query object, the goal is to localize the 3D position of the center of that query object with respect to the camera pose of a query frame. Current methods tackle the problem of VQ3D by unprojecting the 2D localization results of the sibling task Visual Queries with 2D Localization (VQ2D) into 3D predictions. Yet, we point out that the low number of camera poses caused by camera re-localization from previous VQ3D methods severally hinders their overall success rate. In this work, we formalize a pipeline (we dub EgoLoc) that better entangles 3D multiview geometry with 2D object retrieval from egocentric videos. Our approach involves estimating more robust camera poses and aggregating multi-view 3D displacements by leveraging the 2D detection confidence, which enhances the success rate of object queries and leads to a significant improvement in the VQ3D baseline performance. Specifically, our approach achieves an overall success rate of up to 87.12\%, which sets a new state-of-the-art result in the VQ3D task. We provide a comprehensive empirical analysis of the VQ3D task and existing solutions and highlight the remaining challenges in VQ3D. The code and models will be released upon publication to set a new standard for the VQ3D task."

draft: false
featured: true
tags:
  - Deep learning
  - Egocentric video understanding
  - 3D modelling
slides: ""
url_pdf: https://arxiv.org/pdf/2212.06969.pdf 
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
