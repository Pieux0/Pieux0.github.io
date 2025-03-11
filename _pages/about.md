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

I am currently a master's student at Shandong University.

2022-2025, I am a master's student at Shandong University advised by [Xiankai Lu](https://faculty.sdu.edu.cn/luxiankai/zh_CN/index.htm).

2018-2022, I obtained my Bachelor's degree from Shandong University.

**RESEARCH STATEMENT**

1. **Human Mesh Reconstruction/Recovery (HMR):** Reconstruct 3D joint and mesh of human body from image or videos.
2. **Compositional Zero-Shot Learning (CZSL):** Reason novel *attribute-object* compositions based on learned attribute and object representations.

Email address: mvppengwu@gmail.com


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 . One paper about compositional zero-shot learning is accepted to CVPR 2025.
- *2024.07*: &nbsp;🎉🎉 . One paper about video instance segmentation is accepted to ECCV 2024.
- *2023.07*: &nbsp;🎉🎉 . One paper about human mesh recovery is accepted to ACM MM 2023.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/LogiCZSL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

LOGICZSL: Exploring Logic-induced Representation for Compositional Zero-shot Learning [[pdf]()] [[code]()]

**Peng Wu**, Xiankai Lu, Hu Hao, Yongqin Xian, Jianbing Shen, Wenguan Wang


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/OVFormer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unified Embedding Alignment for Open-Vocabulary Video Instance Segmentation [[pdf](https://arxiv.org/pdf/2407.07427)] [[code](https://github.com/fanghaook/OVFormer)]

Hao Fang, **Peng Wu**, Yawei Li, Xinxin Zhang, Xiankai Lu

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/BiCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Clip Fusion with Bi-level Optimization for Human Mesh Reconstruction from Monocular Videos [[pdf](https://dl.acm.org/doi/10.1145/3581783.3611978)] [[code](https://github.com/bicf0/BiCF)]

**Peng Wu**, Xiankai Lu, Jianbing Shen, Yilong Yin (**Oral**)


