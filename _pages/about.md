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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 😺 About Me

Hi, I’m **Qi Pang**, a Ph.D. student at the **School of Artificial Intelligence and Data Science (AIDS), University of Science and Technology of China (USTC)**, where I am fortunate to be supervised by **Prof. [Xinming Wu](https://cig.ustc.edu.cn/xinming/list.htm)**. Before that, I received my Master’s degree from **Xi’an Jiaotong University** under the supervision of **Prof. [Jinghuai Gao](https://scholar.google.com/citations?user=53gDhbgAAAAJ&hl=zh-CN&oi=ao)**, and my Bachelor’s degree from **Shenyang Aerospace University**.

My research interests include **inverse problems**, **generative modeling**, and **geological modeling**, with a particular focus on developing physics-informed generative models for geoscience.

<!-- <span style="color:red; font-weight:bold;">🚀 I am currently seeking Ph.D. opportunities starting in Fall 2026</span>, and I’m always happy to explore academic collaborations aligned with my research interests. -->

#### 🔍 Topics I’m Excited About

- **Subsurface geoscience with generative models**  
  *(grounded in geophysical principles)*

- **Geological modeling with realistic priors**  
  *(e.g., geostatistical simulation methods)*

- **Inversion guided by multi-source information**  
  *(e.g., physics-informed machine learning)*


#### 🌍 Vision

<div class='paper-box'><div class='paper-box-image'><div><div class="badge vision">Vision</div><img src='images/sim2gen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**World Model for the Subsurface**

My future research aims to build a **World Model for Earth Science** — a generative framework that deeply understands the subsurface by integrating physics, multi-modal observations, and geological knowledge.

</div>
</div>


If you’re working on related problems—or think my background could contribute to your group or project—I’d love to connect. Feel free to reach out at: 📧 **pangjiutian@gmail.com**


<span class='anchor' id='publications'></span>

# 📝 Publications

## Current Research Topics: Generative Models/Geological Modeling

High-quality training data is essential in modern geophysics, yet sensitive data and the lack of open datasets remain major challenges. My research bridges **numerical simulation** and **generative AI** to create diverse, realistic subsurface datasets for geophysical applications. 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/geovoldiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GeoVolDiff: Taming 3D Geological Volumes with  Latent Diffusion**

<strong style="color:#0056b3;">Qi Pang</strong>, Hongling Chen, Jinghuai Gao.

We present GeoVolDiff, a latent diffusion framework for synthesizing realistic 3D geological volumes at scale. The generated geological models can be used to pre-train downstream geophysical learning systems, significantly reducing dependence on expensive labeled field data. Results on seismic impedance inversion show strong transferability from synthetic to real-world datasets.

[**Paper**](https://arxiv.org/abs/2606.03572v1) | [**GitHub**](https://github.com/PangJiutian/geovoldiff) ![ ](https://img.shields.io/github/stars/PangJiutian/geovoldiff?style=social)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAGE 2026</div><img src='images/eage2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Scaling the Subsurface: Deep Generative Synthesis of 3D Seismic Properties**

<strong style="color:#0056b3;">Qi Pang</strong>, Hongling Chen, Jinghuai Gao, et al.

A latent diffusion framework for unconditional 3D geological model generation.


[**Paper**](https://www.earthdoc.org/content/papers/10.3997/2214-4609.2026101269) | [**GitHub**](https://github.com/PangJiutian/geovoldiff/blob/main/pipelines/uncond_gvd_pipeline.py) ![ ](https://img.shields.io/github/stars/PangJiutian/geovoldiff?style=social)
</div> 
</div>


## Previous Research Topics: Seismic Impedance Inversion/Transformer/CNN

My research journey began with seismic impedance inversion, progressing from traditional model-driven approaches to deep learning methods — from CNNs to globally-aware Transformers — which ultimately motivated my shift toward generative modeling.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2025</div><img src='images/pub1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Iterative Gradient Corrected Semi-Supervised  Seismic Impedance Inversion via Swin Transformer**

<strong style="color:#0056b3;">Qi Pang</strong>, Hongling Chen, Jinghuai Gao, et al.

An iterative gradient correction strategy guides the network to learn update mappings in model space and capture implicit priors, effectively suppressing null-space uncertainty. Combined with Swin Transformer for long-range dependency modeling, achieving high-accuracy seismic impedance inversion.


[**Paper**](https://ieeexplore.ieee.org/document/10989649) | [**GitHub**](https://github.com/GeoAI-INV/Iterative-Gradient-Corrected-Swin-Inversion) ![ ](https://img.shields.io/github/stars/GeoAI-INV/Iterative-Gradient-Corrected-Swin-Inversion?style=social)
</div>
</div>

<span class='anchor' id='research-experience'></span>

# 💻 Research Experience

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Software</div><img src='images/com_seiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Seisvis - Seismic Data Visualization Library**

A simple and easy-to-use Python library for seismic data visualization, designed for geophysicists and seismic data analysts.

[**GitHub**](https://github.com/PangJiutian/Seisvis) ![ ](https://img.shields.io/github/stars/PangJiutian/Seisvis)
</div>
</div>

<div class='paper-box-small'>
<div class='paper-box-item'>

<a href="https://github.com/PangJiutian/Generating-Time-Shifted-Seismic-Data"><strong>Real-World Time-Shifted Seismic Data Generation</strong></a>

Inconsistencies in time-depth relationships often cause misalignment between well logs and seismic data. This project simulates realistic time-shifted seismic data by leveraging time-depth relationships, generating large-scale synthetic pairs as high-quality training samples for deep learning-based time-shift estimation models.

</div>

<div class='paper-box-item'>

<a href="https://github.com/PangJiutian/Model-driven-Seismic-Inversion-with-Structural-Regularization"><strong>Model-Driven Seismic Inversion with Structural Regularization</strong></a>

Implemented seismic convolution forward modeling in MATLAB based on the Marmousi model. Compared structure tensor and PWD for dip estimation — PWD proved more robust under noise. A structure-constrained inversion objective was solved via FISTA.

</div>
</div>


<span class='anchor' id='educations'></span>

# 📖 Educations

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="images/ustc.jpg" alt="USTC Logo">
    </div>
    <div class="experience-box-text">
        <p><strong>2026.09 - Present</strong></p>
        <p>Ph.D., <a href="https://www.ustc.edu.cn/index.htm">University of Science and Technology of China</a></p>
        <p>Advisor: Prof. <a href="https://cig.ustc.edu.cn/xinming/list.htm">Xinming Wu</a></p>
    </div>
</div>

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="images/xjtu.jpg" alt="XJTU Logo">
    </div>
    <div class="experience-box-text">
        <p><strong>2023.09 - 2026.06</strong></p>
        <p>M.S., <a href="https://www.xjtu.edu.cn/index.htm">Xi'an Jiaotong University</a></p>
        <p>Advisor: Prof. <a href="https://scholar.google.com/citations?user=53gDhbgAAAAJ&hl=zh-CN&oi=ao">Jinghuai Gao</a></p>
    </div>
</div>

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="images/sau.jpg" alt="SAU Logo">
    </div>
    <div class="experience-box-text">
        <p><strong>2019.09 - 2023.06</strong></p>
        <p>B.Eng., <a href="https://www.sau.edu.cn/">Shenyang Aerospace University</a></p>
    </div>
</div>

<span class="anchor" id="hobbies"></span>

# 🎮 Hobbies

When I'm not coding or running simulations, I like to relax (or compete!) through games and sports:

- 🪓 **Don’t Starve Together** – 1000+ hours in the wilderness (and I love eating Meatballs!)  
- ⚔️ **League of Legends** – Chill ARAM grinder / tryhard Top & Jungle main  
- 🏓 **Table Tennis** – Big fan of ping pong! Always up for a quick match  
- 🎲 Also enjoy co-op survival, strategy games, and quirky indie titles

Let’s play sometime!  
🎮 Steam Friend Code: `1034585311`

<span class="anchor" id="cv"></span>

# 📄 CV

<p>
  <a href="CV_QiPang.pdf" download target="_blank" style="font-size: 16px; text-decoration: none; color: #007acc;">
    📥 Download CV
  </a>
</p>



