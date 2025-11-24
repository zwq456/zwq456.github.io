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
From 2023 to present, I am a Master's Student at the School of Electrical and Information Engineering, Tianjin University, advised by Associate Prof. [Jiale Cao](https://jialecao001.github.io/). Since February 2025, I have been an intern in the Foundation Model Group at MEGVII Technology.



My current research interests are in the areas of (1) **Embodied AI**, (2) **Open-vocabulary segmentation**, (3) **Video segmentation**.


# 🔥 News
- *2025.10*: One paper(SED++) is accepted by IEEE TPAMI.
- *2025.02*: One paper(VideoGLaMM) is accepted by CVPR 2025.
- *2024.10*: One paper(CLIP-VIS) is accepted by IEEE TCSVT.


# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TPAMI</div><img src='iimages/sed++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SED++: A Simple Encoder-Decoder for  Improved Open-Vocabulary Semantic  Segmentation
|**IEEE TPAMI**|[Paper](https://ieeexplore.ieee.org/document/11223241)|[Code](https://github.com/xb534/SED.git)|

**Wenqi Zhu***, Bin Xie*, Jiale Cao, Jin Xie, Fahad Shahbaz Khan, and Yanwei Pang

- <strong style="color:green">We introduce no-label prompt learning and CER in the encoder, which jointly improve the model’s inference speed and segmentation accuracy. In addition, we propose a lightweight temporal aggregation layer that adapts the method to video-based tasks.
</strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images\VideoGLaMM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

VideoGLaMM : A Large Multimodal Model for Pixel-Level  Visual Grounding in Videos
|**CVPR 2025**|[Paper]([https://arxiv.org/abs/2411.04923](https://openaccess.thecvf.com/content/CVPR2025/html/Munasinghe_VideoGLaMM__A_Large_Multimodal_Model_for_Pixel-Level_Visual_Grounding_CVPR_2025_paper.html))|[Code](https://mbzuai-oryx.github.io/VideoGLaMM)|

Shehan Munasinghe, Hanan Gani, **Wenqi Zhu**, Jiale Cao, Eric Xing, Fahad Shahbaz Khan and Salman Khan

- <strong style="color:green">We propose a multimodal model for pixel-level  visual grounding in videos and introduce a dataset with diverse multimodal annotations. Our model and dataset support various tasks, including grounded conversation generation, visual grounding, and referring video segmentation.</strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TCSVT</div><img src='images\CLIP-VIS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

CLIP-VIS: Adapting CLIP for Open-Vocabulary
Video Instance Segmentation  
|**IEEE TCSVT**|[Paper](https://ieeexplore.ieee.org/document/10706247)|[Code](https://github.com/zwq456/CLIP-VIS)|

**Wenqi Zhu**, Jiale Cao, Jin Xie, Shuangming Yang, and Yanwei Pang

- <strong style="color:green">To address the issue of poor model generalization caused by the alignment of learnable queries and text embeddings in existing methods, we implemented the alignment of image features and text features using Mask Pooling. Additionally, we proposed a TopK-enhanced instance matching strategy to mitigate problems such as error propagation in matching and susceptibility to noisy frames in the original matching strategy.</strong>
</div>
</div>

# Service
  
Invited Reviewer for journals:
- IET Image Processing
