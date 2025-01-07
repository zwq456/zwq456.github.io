---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I received the B.E degree in electronic
information engineering from Tianjin University,
Tianjin, China, in 2023.
From 2023 to present, I am a Master's Student at the School of Electrical and Information Engineering, Tianjin University, advised by Associate Prof. [Jiale Cao](https://jialecao001.github.io/).


My current research interests are in the areas of (1) **Video segmentation**, (2) **Open-vocabulary segmentation**.


# 🔥 News
- *2024.10*: One paper(CLIP-VIS) is accepted by IEEE TCSVT.

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TCSVT</div><img src='images\CLIP-VIS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

CLIP-VIS: Adapting CLIP for Open-Vocabulary
Video Instance Segmentation  
|**IEEE TCSVT**|[Paper](https://ieeexplore.ieee.org/document/10706247)|[Code](https://github.com/zwq456/CLIP-VIS)|

**Wenqi Zhu**, Jiale Cao, Jin Xie, Shuangming Yang, and Yanwei Pang

- <strong style="color:green"> </strong>To address the issue of poor model generalization caused by the alignment of learnable queries and text embeddings in existing methods, we implemented the alignment of image features and text features using Mask Pooling. Additionally, we proposed a TopK-enhanced instance matching strategy to mitigate problems such as error propagation in matching and susceptibility to noisy frames in the original matching strategy.</strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images\VideoGLaMM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

VideoGLaMM : A Large Multimodal Model for Pixel-Level  Visual Grounding in Videos
[Paper](https://arxiv.org/abs/2411.04923)|[Code](https://mbzuai-oryx.github.io/VideoGLaMM)|

Shehan Munasinghe, Hanan Gani, **Wenqi Zhu**, Jiale Cao, Eric Xing, Fahad Shahbaz Khan and Salman Khan

- <strong style="color:green"> </strong>We propose a multimodal model for pixel-level  visual grounding in videos and introduce a dataset with diverse multimodal annotations. Our model and dataset support various tasks, including grounded conversation generation, visual grounding, and referring video segmentation.</strong>
</div>
</div>


