---
title: 'GVCNN: Group-view convolutional neural networks for 3d shape recognition'
date: '2018-01-01'
publishDate: '2020-08-25T03:25:57.555032Z'
authors:
- Yifan Feng
- Zizhao Zhang
- Xibin Zhao
- Rongrong Ji
- Yue Gao
publication_types:
- 1
abstract: '3D shape recognition has attracted much attention recently. Its recent advances advocate the usage of deep features and achieve the state-of-the-art performance. However, existing deep features for 3D shape recognition are restricted to a view-to-shape setting, which learns the shape descriptor from the view-level feature directly. Despite the exciting progress on view-based 3D shape description, the intrinsic hierarchical correlation and discriminability among views have not been well exploited, which is important for 3D shape representation. To tackle this issue, in this paper, we propose a group-view convolutional neural network (GVCNN) framework for hierarchical correlation modeling towards discriminative 3D shape description. The proposed GVCNN framework is composed of a hierarchical view-group-shape architecture, ie, from the view level, the group level and the shape level, which are organized using a grouping strategy. Concretely, we first use an expanded CNN to extract a view level descriptor. Then, a grouping module is introduced to estimate the content discrimination of each view, based on which all views can be splitted into different groups according to their discriminative level. A group level description can be further generated by pooling from view descriptors. Finally, all group level descriptors are combined into the shape level descriptor according to their discriminative weights. Experimental results and comparison with state-of-the-art methods show that our proposed GVCNN method can achieve a significant performance gain on both the 3D shape classification and retrieval tasks.'
featured: false
publication: '*Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition 2018*'
publication_short: "CVPR 2018"

summary: ''

tags: 
- 3D Vision
url_pdf: http://openaccess.thecvf.com/content_cvpr_2018/papers/Feng_GVCNN_Group-View_Convolutional_CVPR_2018_paper.pdf
# url_code: ''
url_dataset: 'http://modelnet.cs.princeton.edu/'
# url_poster: ''
# url_slides: ''

image:
  caption: 'GVCNN Framework'
  focal_point: "left"
  preview_only: false
---

