---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project
title: "Author-Aware Rumour Detection with Layer-Wise Parameter-Efficient Tuning and Incomplete Feature Learning"
tagline: "Tsun-Hin Cheung, Kin-Man Lam"
git_url: https://github.com/thcheung/aard
---

## Abstract

Detecting rumours on social media is a crucial task for natural language processing and social computing. Existing methods rely on analysing the text of the source post with propagation graph, and external evidence, which can lead to delayed detection of rumours. To address this issue, we propose an early detection approach that leverages textual claims and the credibility of the source author to identify rumours, by converting an author-aware rumour detection into a text classification problem using pre-trained language models. The pretrained models are tuned to select the important features between post content and author profile, for author-aware rumour detection. We employ a multi-task learning framework that simultaneously identifies rumour claims and malicious accounts, improving overall detection accuracy. To bridge the task gap between pretraining and fine-tuning, we propose a Layer-Wise Parameter-Efficient Tuning (LWPET) strategy that optimizes the parameters of pre-trained language models, reducing the computation and memory requirements for tuning these models for rumour detection. Our approach can be easily integrated into most transformer-based pre-trained models, minimizing newly initialized parameters. Experimental results show that our method significantly improves transformer-based models on three benchmark datasets, namely Twitter15, Twitter16, and CR-Twitter, demonstrating its effectiveness in real-world rumour detection. We provide public access to the source code and trained models, enabling easy replication and extension of our work. 
## Codes

Pretrained Model and Checkpoint can be found at the [Github Repo](https://github.com/thcheung/AARD).

## Datasets

The datasets can be downloaded below..

- [AARD Dataset](https://connectpolyu-my.sharepoint.com//:u:/r/personal/19104564r_connect_polyu_hk/Documents/AARD_dataset.zip?csf=1&web=1&e=js0NRv)
