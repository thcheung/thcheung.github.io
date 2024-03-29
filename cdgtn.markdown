---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project
title: "Causal Diffused Graph-Transformer Network with Stacked Early Classification Loss for Efficient Stream Classification of Rumours"
tagline: "Tsun-Hin Cheung, Kin-Man Lam"
git_url: https://github.com/thcheung/cdgtn
---

## Abstract

The growth in social media has led to the increasing spread of unverified or false information. Automatically detecting rumours and accessing the veracity of rumours, i.e., false rumours, true rumours, or unverified rumours, are important and challenging tasks in social media analytics. This paper aims to build an effective and scalable stream classification framework for early fine-grained rumour classification, based on community response. We propose a Causal Diffused Graph- Transformer Network (CDGTN) to extract features from the source-reply graph in a social media conversation. Then, we propose source-guided incremental attention pooling to aggregate the encoded features with discrete timestamps. To improve the performance of early classification, we propose a stacked early classification loss, which aims to minimize the classification loss over the time instances. This can greatly improve the effectiveness of early classification of rumours. To improve the efficiency of streaming rumour verification, we propose a continued inference algorithm based on prefix-sum, which can greatly reduce the computational complexity of stream classification of rumours. Furthermore, we annotated the first Chinese rumour verification dataset, by extending the existing Chinese-Twitter dataset, namely CR-Twitter, originally for rumour detection. We conducted experiments on the Twitter15, Twitter 16, and the extended CR-Twitter datasets for finegrained rumour classification, to verify our proposed stream classification framework. Experimental results show that our proposed framework can significantly boost the effectiveness and efficiency of early stream classification of rumours.

## Codes

Pretrained Model and Checkpoint can be found at the [Github Repo](https://github.com/thcheung/CDGTN).

## Datasets
The extended CR-Twitter can be downloaded below. Password is: CDGTN2023.

- [Extended CR-Twitter Dataset](https://connectpolyu-my.sharepoint.com/:u:/g/personal/15083269d_connect_polyu_hk/EdUFxIS-Ea9Igvk6ddku93wBxPYSehGT3OWAb3Y00J42Yw?e=BhWfgT)

## Model Checkpoints

The model checkpoints can be found in the releases [here](https://github.com/thcheung/CDGTN/releases/tag/checkpoint).

