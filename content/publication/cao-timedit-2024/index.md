---
title: 'TimeDiT: General-purpose Diffusion Transformers for Time Series Foundation Model'
authors:
- Defu Cao
- Wen Ye
- Yan Liu
date: '2024-07-03'
publishDate: '2025-01-08T05:27:41.746786Z'
publication_types:
- paper-conference
publication: '*ICML 2024 Workshop on Foundation Models in the Wild*'
abstract: With recent advances in building foundation models for texts and video data,
  there is a surge of interest in foundation models for time series. A family of models
  have been developed, utilizing a temporal auto-regressive generative Transformer
  architecture, whose effectiveness has been proven in Large Language Models. While
  the empirical results are promising, almost all existing time series foundation
  models have only been tested on well-curated ``benchmark'' datasets very similar
  to texts. However, real-world time series exhibit unique challenges, such as variable
  channel sizes across domains, missing values, and varying signal sampling intervals
  due to the multi-resolution nature of real-world data. Additionally, the uni-directional
  nature of temporally auto-regressive decoding limits the incorporation of domain
  knowledge, such as physical laws expressed as partial differential equations (PDEs).
  To address these challenges, we introduce the Time Diffusion Transformer (TimeDiT),
  a general foundation model for time series that employs a denoising diffusion paradigm
  instead of temporal auto-regressive generation. TimeDiT leverages the Transformer
  architecture to capture temporal dependencies and employs diffusion processes to
  generate high-quality candidate samples without imposing stringent assumptions on
  the target distribution via novel masking schemes and a channel alignment strategy.
  Furthermore, we propose a finetuning-free model editing strategy that allows the
  seamless integration of external knowledge during the sampling process without updating
  any model parameters. Extensive experiments conducted on a varity of tasks such
  as forecasting, imputation, and anomaly detection, demonstrate the effectiveness
  of TimeDiT.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Machine Learning
links:
- name: OpenReview
  url: https://openreview.net/forum?id=DA36Myd4HD
- name: arXiv
  url: https://arxiv.org/abs/2409.02322
---
