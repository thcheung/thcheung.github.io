---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project
title: "Crossmodal Bipolar Attention for Multimodal Classification on Social Media"
tagline: "Tsun-Hin Cheung, Kin-Man Lam"
git_url: https://github.com/thcheung/CBAN
---

## Abstract

Multimodal classification of social media is used to classify data from different modalities into different categories, which is essential for understanding user behavior on the web. In this paper, we focus on classifying image-text pairs, specifically user-generated content on social media. Recently, the transformer network, a kind of self-attention network, has been widely studied in the disciplines of visual computing and language processing. In the attention mechanism, positive correlation is considered. However, multimedia content posted on social media is diverse. Images and text are not always consistent, and contrary information is also helpful for representation. Therefore, it is equally important to detect conflicts based on negative or inverse attention. Inspired by the attention mechanism, we propose a novel model, namely Crossmodal Bipolar Attention Network (CBAN). Different from existing positive dot-product and additive attention mechanisms, we propose a bipolar attention mechanism, which fuses visual and textual information through their direct and inverse semantic relationships to classify multimodal data. We conducted experiments on multiple multimodal classification data sets, for performing sentiment analysis, sarcasm detection, crisis categorization and hate-speech detection. Experimental results show that our proposed CBAN consistently outperforms state-of-the-art methods in all classification tasks.
## Codes

Pretrained Model and Checkpoint can be found at the [Github Repo](https://github.com/thcheung/CBAN).

## Datasets

Full datasets can be downloaded below.

- [PHEME Dataset](https://mcrlab.net/research/mvsa-sentiment-analysis-on-multi-view-social-data/)

- [Sarcasm Detection Dataset](https://github.com/GT-DLT-2021/Multimodal-Sarcasm-Detection)

- [CrisisMMD Dataset](https://crisisnlp.qcri.org/crisismmd)

- [MMHS150K Dataset](https://gombru.github.io/2019/10/09/MMHS/)
