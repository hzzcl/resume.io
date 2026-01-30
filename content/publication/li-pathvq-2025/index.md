---
title: 'PathVQ: Reforming Computational Pathology Foundation Model for Whole Slide
  Image Analysis via Vector Quantization'
authors:
- Honglin Li
- Zhongyi Shui
- Yunlong Zhang
- Chenglu Zhu
- Lin Yang
date: '2025-03-01'
publishDate: '2026-01-30T15:23:21.164193Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2503.06482
abstract: Computational pathology and whole-slide image (WSI) analysis are pivotal
  in cancer diagnosis and prognosis. However, the ultra-high resolution of WSIs presents
  significant modeling challenges. Recent advancements in pathology foundation models
  have improved performance, yet most approaches rely on [CLS] token representation
  of tile ViT as slide-level inputs (16x16 pixels is refereed as patch and 224x224
  pixels as tile). This discards critical spatial details from patch tokens, limiting
  downstream WSI analysis tasks. We find that leveraging all spatial patch tokens
  benefits WSI analysis but incurs nearly 200x higher storage and training costs (e.g.,
  196 tokens in ViT$_224$). To address this, we introduce vector quantized (VQ) distillation
  on patch feature, which efficiently compresses spatial patch tokens using discrete
  indices and a decoder. Our method reduces token dimensionality from 1024 to 16,
  achieving a 64x compression rate while preserving reconstruction fidelity. Furthermore,
  we employ a multi-scale VQ (MSVQ) strategy, which not only enhances VQ reconstruction
  performance but also serves as a Self-supervised Learning (SSL) supervision for
  a seamless slide-level pretraining objective. Built upon the quantized patch features
  and supervision targets of tile via MSVQ, we develop a progressive convolutional
  module and slide-level SSL to extract representations with rich spatial-information
  for downstream WSI tasks. Extensive evaluations on multiple datasets demonstrate
  the effectiveness of our approach, achieving state-of-the-art performance in WSI
  analysis. Code will be available soon.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2503.06482
---
