---
title: 'DPA-P2PNet: Deformable Proposal-Aware P2PNet for Accurate Point-Based Cell
  Detection'
authors:
- Zhongyi Shui
- Sunyi Zheng
- Chenglu Zhu
- Shichuan Zhang
- Xiaoxuan Yu
- Honglin Li
- Jingxiong Li
- Pingyi Chen
- Lin Yang
date: '2024-03-01'
publishDate: '2025-03-17T07:55:28.404946Z'
publication_types:
- article-journal
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence*'
doi: 10.1609/aaai.v38i5.28289
abstract: Point-based cell detection (PCD), which pursues high-performance cell sensing
  under low-cost data annotation, has garnered increased attention in computational
  pathology community. Unlike mainstream PCD methods that rely on intermediate density
  map representations, the Point-to-Point network (P2PNet) has recently emerged as
  an end-to-end solution for PCD, demonstrating impressive cell detection accuracy
  and efficiency. Nevertheless, P2PNet is limited to decoding from a single-level
  feature map due to the scale-agnostic property of point proposals, which is insufficient
  to leverage multi-scale information. Moreover, the spatial distribution of pre-set
  point proposals is biased from that of cells, leading to inaccurate cell localization.
  To lift these limitations, we present DPA-P2PNet in this work. The proposed method
  directly extracts multi-scale features for decoding according to the coordinates
  of point proposals on hierarchical feature maps. On this basis, we further devise
  deformable point proposals to mitigate the positional bias between proposals and
  potential cells to promote cell localization. Inspired by practical pathological
  diagnosis that usually combines high-level tissue structure and low-level cell morphology
  for accurate cell classification, we propose a multi-field-of-view (mFoV) variant
  of DPA-P2PNet to accommodate additional large FoV images with tissue information
  as model input. Finally, we execute the first self-supervised pre-training on immunohistochemistry
  histopathology image data and evaluate the suitability of four representative self-supervised
  methods on the PCD task. Experimental results on three benchmarks and a large-scale
  and real-world interval dataset demonstrate the superiority of our proposed models
  over the state-of-the-art counterparts. Codes and pre-trained weights are available
  at https://github.com/windygoo/DPA-P2PNet.
---
