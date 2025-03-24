---
title: Recognition of Cognitive Task Load levels using single channel EEG and Stacked
  Denoising Autoencoder
authors:
- Zhong Yin
- Jianhua Zhang
date: '2016-07-01'
publishDate: '2025-03-24T17:07:51.517939Z'
publication_types:
- paper-conference
publication: '*2016 35th Chinese Control Conference (CCC)*'
doi: 10.1109/ChiCC.2016.7553961
abstract: Evaluation of operator Cognitive Task Load (CTL) level is quite crucial
  in Human-Machine (HM) collaborative task environment since operator mental overload
  or inattention caused by abnormal CTL states may lead to human performance degradation
  or even catastrophic accidents. One of the most practical approaches tackling this
  issue is to use ongoing electroencephalogram (EEG) in which human cognitive state
  can be objectively estimated. However, the accurate recognition of CTL via single
  channel EEG with the lowest-intrusivity to task condition is particularly challenging
  as EEG is characterized by individual dependency and nonstationarity. In this paper,
  a deep learning model designed by Stacked Denoising AutoEncoder (SDAE) is employed
  on single EEG channel signal to estimate binary levels (low vs. high) of CTL. By
  adopting a simulated HM process control system, the operator EEG data for 8 healthy
  subjects under different task demands were collected on two experimental sessions
  across two consecutive days. Based on the computed full power spectral of EEG. the
  number of nodes in SDAE is determined by greedy search according to the optimal
  training error of each layer. The shallow layers of the designed deep network are
  used to extract the subject-specific information related to CTL variation while
  the stable power features were reconstructed in those deep layers. Finally, the
  proposed method is demonstrated to be effective and 74% classification rate across
  sessions in average of all subjects were achieved.
tags:
- 5G mobile communication
- Cognitive task load
- Decision support systems
- deep learning
- electroencephalogram
- mental workload
- operator functional state
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/7553961
---
