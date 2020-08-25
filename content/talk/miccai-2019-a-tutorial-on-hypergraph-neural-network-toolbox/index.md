---
title: "MICCAI 2019: A Tutorial on Hypergraph Neural Network Toolbox "
abstract: 'We organize a tutorial about "Hypergraph Learning: Methods, Tools and
  Applications in Medical Image Analysis". I give a talk about "A Tutorial on
  Hypergraph Neural Network Toolbox".'
location: Shenzhen, China
date: 2019-10-13T08:00:00.374Z
date_end: 2019-10-13T11:20:00.691Z
all_day: false
links:
  - url: https://www.miccai2019.org/programme/workshops-challenges-tutorials/
    name: Link
event: "Tutorial: A Tutorial on Hypergraph Neural Network Toolbox"
event_url: https://www.miccai2019.org/programme/workshops-challenges-tutorials/
publishDate: 2020-08-24T12:54:13.399Z
draft: false
featured: true
authors:
  - Yifan Feng
tags:
  - Tutorial
  - Hypergraph
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
[THU-DeepHypergraph](https://github.com/iMoonLab/THU-DeepHypergraph)(THU-DH) is a python toolbox for hypergraph-based deep learning, which is built upon pytorch. Edge in hypergraph named hyperedge can link more than two nodes, which allows hyperedge to express more than pair-wise relation(like: entity-attribute relation, group relation, hierarchical relation and so on.). Thus, hypergraph owns more powerful model ability than common graph.
It consists of sparse hypergraph construction, fusion, convolution operations, convenient util functions for medical image(MRI, Pathology, etc.), 3D(point cloud, view-based graph, etc.) and other hypergraph applications(to be continue...). Hypergrpah inductive learning and hypergraph transductive learning examples is also included in this toolbox. What's more, we write several examples that deploy hypergraph in different tasks like: Classification, Segmentation and Regression.