---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project
title: "Unifying Multimodal Source and Propagational Graph for Rumour Detection on Social Media with Missing Features"
tagline: "Tsun-Hin Cheung, Kin-Man Lam"
git_url: https://github.com/thcheung/UMGTN
---

## Abstract

With the rapid development of online social media platforms, the spread of rumours has become a critical issue in global society. Existing methods of rumour detection can be divided into two categories, including image-text pair classification and source-reply graph classification. In this paper, we simultaneously leverage the multimodal source and propagational graph features, for rumour classification. We propose a Unified Multimodal Graph Transformer Network, namely UMGTN, to fuse the multimodal source and propagational graph features, through Transformer encoders. In social media, not every message is associated with an image. Moreover, the community responses in the propagational graph do not immediately appear after the source information is posted on social media. Therefore, we aim to build a network architecture that accepts inputs of missing features, i.e., missing images or replies. To improve the robustness of the model to the missing features, we employ a multi-task learning framework, by sharing features between different missing features data. To evaluate the performance of the proposed method, we extend four real-world datasets, by recovering the images and replies from Twitter and Weibo. The Experimental results show that the proposed UMGTN with multi-task learning achieves state-of-the-art performance, in terms of F1-score gains of 1.0 to 4.0%, while maintaining the detection robustness to missing features in all datasets, 2% in terms of accuracy and F1-score, compared to models trained without multi-task learning framework.

## Codes

The Pretrained Model and Checkpoint can be found at the [Github Repo](https://github.com/thcheung/UMGTN)

## Datasets

Full datasets can be downloaded below. Password will be provided once the paper is accepted.

- [PHEME Dataset](https://connectpolyu-my.sharepoint.com/:u:/g/personal/15083269d_connect_polyu_hk/EWMDKoZhXfNBsjZy0IHwss0B50OhrxctkUWbAiOpq3cuXQ?e=XcTKgo)

- [Twitter Dataset](https://connectpolyu-my.sharepoint.com/:u:/g/personal/15083269d_connect_polyu_hk/EXvz_v8eypRPpa9tGDh79MsB9rPvDrmlNZBwPrh8zHt38w?e=JvNJsl)

- [Weibo-16 Dataset](https://connectpolyu-my.sharepoint.com/:u:/g/personal/15083269d_connect_polyu_hk/EU5duP8NOKtOlvHmpCLp0dEB06TYkwWfhUUyyMEvkFQN1A?e=P8bNqP)

- [Weibo-17 Dataset](https://connectpolyu-my.sharepoint.com/:u:/g/personal/15083269d_connect_polyu_hk/EQfnvtPJPU9DmmyRp1UST8UBjK-MolS9mx2DevZJ8vgoEg?e=SXCxQJ)
