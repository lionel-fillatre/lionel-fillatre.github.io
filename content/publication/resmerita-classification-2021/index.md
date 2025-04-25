---
title: Classification Error Approximation of a Compressed Linear Softmax Layer
authors:
- Diana Resmerita
- Rodrigo Cabral Farias
- Lionel Fillatre
date: '2021-08-01'
publishDate: '2025-04-25T19:44:33.072266Z'
publication_types:
- paper-conference
publication: '*2021 29th European Signal Processing Conference (EUSIPCO)*'
doi: 10.23919/EUSIPCO54536.2021.9616015
abstract: Deep neural networks need to be compressed due to their high memory requirements
  and computational complexity. Previous papers have proposed numerous methods to
  quantize the weights with a single bit or more. However, the loss of accuracy involved
  in the compression is scarcely studied from a theoretical point of view. Motivated
  by the rate-distortion theory, we propose a new distortion measure which assesses
  the gap between the Bayes risk of a classifier before and after the compression.
  Since this distortion is not easily tractable, we derive a theoretical approximation
  when the last fully connected layer of a deep neural network is compressed under
  the assumption that the layer inputs follow a multivariate normal distribution.
  Numerical results show that the approximation performs well on both synthetic and
  real data. We also show that heuristic quantizers proposed in the literature may
  not be optimal.
tags:
- Analytical models
- Deep learning
- Europe
- Gaussian distribution
- Memory management
- Quantization (signal)
- Rate-distortion
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9616015
---
