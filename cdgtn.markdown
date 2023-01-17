---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project
title: "Causal Diffused Graph-Transformer Encoder with Incremental Attention Pooling for Stream Detection of Rumours"
tagline: "Tsun-Hin Cheung, Kin-Man Lam"
git_url: https://github.com/thcheung/cdgtn
---

## Abstract

The growth in social media has led to the increasing spread of unverified or false information. Automatically assessing the veracity of information, i.e., rumours or not, is an important and challenging task. This paper aims to build an effective and scalable stream classification framework for early rumour verification. We propose a Causal Diffused Graph-Transformer Network (CD-GTN) to extract features from the source-reply graph in a social media conversation. Then, we propose incremental attention pooling to aggregate the encoded features with discrete timestamps.  To improve the efficiency of streaming rumour verification, we propose a continuous inference algorithm based on prefix-sum, which can greatly reduce the computational complexity of stream verification of rumours. Furthermore, we annotated the first Chinese rumour verification dataset, by extending the existing Chinese-Twitter dataset, namely CR-Twitter, originally for rumour detection. We conducted experiments on the extended CR-Twitter dataset and existing PHEME dataset, for Chinese and English rumour verification, respectively, to verify our proposed stream rumour verification framework. Experimental results show that our proposed framework can significantly boost the effectiveness and efficiency of early stream verification of rumours.
## Codes

Pretrained Model and Checkpoint can be found at the [Github Repo](https://github.com/thcheung/CDGTN).

## Datasets

The extended CR-Twitter can be downloaded below.

- [Extended CR-Twitter Dataset](https://connectpolyu-my.sharepoint.com/:u:/g/personal/15083269d_connect_polyu_hk/ERlY9X3CA45MgSRsMSthreIB6KT1Cn7sNyEwQAHFJMsbWQ?e=isc9mG)

