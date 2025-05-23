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

# About Me

Hi, I'm Qi Pang, a second-year Master's student at Xi'an Jiaotong University, where I am fortunate to be supervised by Prof. Jinghuai Gao. Prior to this, I received my Bachelor's degree from Shenyang Aerospace University.

I am passionate about solving seismic inverse problems, with a particular focus on leveraging machine learning techniques. In parallel, I have a strong interest in geological modeling, where physics-based simulations enable the construction of realistic synthetic data.

I am always open to academic collaborations. My specific research interests include:

- **Seismic inversion guided by multi-source information** (based on diffusion models or Transformers)
- **Geological modeling** (based on diffusion models or VAEs)

<span class='anchor' id='publications'></span>

# Publications

## Current Research Topics: Petrophysical Inversion/Diffusion Model

Reservoir characterization seeks to reveal the spatial heterogeneity of subsurface properties to better understand fluid flow. Diffusion models, with their powerful learned priors, flexibly integrate various data sources—such as forward models, well logs, seismic facies, and RGT—to reduce the non-uniqueness of inversion. This integration of generative modeling with geophysical inversion is what inspires my research interest in this field.

🛠 *Ongoing research*

## Previous Research Topics: Seismic Impedance Inversion/Transformer/CNN

My research journey began during my Master’s studies, focusing on seismic impedance inversion. Over time, my work progressed from TV to more adaptive structural constraints, from 1D to 2D inversion with improved lateral continuity, and from traditional model-driven approaches to deep learning methods with stronger nonlinear representation capabilities—ranging from CNNs to globally-aware Transformers. These experiences not only deepened my understanding of inverse problems but also fueled my motivation to further explore the underlying theories and methodologies.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2025</div><img src='images/pub1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Iterative Gradient Corrected Semi-Supervised  Seismic Impedance Inversion via Swin Transformer**

**Qi Pang**, Hongling Chen, Jinghuai Gao, et al.

[**Paper**](https://ieeexplore.ieee.org/document/10989649) | [**GitHub**](https://github.com/GeoAI-INV/Iterative-Gradient-Corrected-Swin-Inversion)
</div>
</div>

<span class='anchor' id='research-experience'></span>

# Research Experience

<ul>
  <li>
    <span style="display: inline-block; background-color:rgb(58, 204, 0); color: white; font-size: 12px; padding: 2px 6px; border-radius: 0px; margin-right: 8px;">
      Experiment
    </span>
    <a href="https://github.com/PangJiutian/Generating-Time-Shifted-Seismic-Data" target="_blank">
      Real-world time-shifted seismic data generation
    </a>
    <div style="margin-top: 4px; font-size: 14px; color: #555;">
      Accurate labeling is critical for deep learning methods in seismic exploration. However, inconsistencies in time-depth relationships often lead to misalignment between well logs and seismic data, resulting in suboptimal training outcomes. This project serves as a precursor for time-shift estimation, aiming to simulate realistic time-shifted seismic data. By leveraging time-depth relationships, we generate large-scale pairs of synthetic time-shifted seismic data to provide high-quality training samples for subsequent deep learning models focused on time-shift estimation.
    </div>
  </li>
</ul>

<ul>
  <li>
    <span style="display: inline-block; background-color:rgb(58, 204, 0); color: white; font-size: 12px; padding: 2px 6px; border-radius: 0px; margin-right: 8px;">
      Experiment
    </span>
    <a href="https://github.com/PangJiutian/Model-driven-Seismic-Inversion-with-Structural-Regularization" target="_blank" style="font-size: 20px;">
      Model driven Seismic Inversion with Structural Regularization
    </a>
    <div style="margin-top: 4px; font-size: 14px; color: #555;">
      I implemented a seismic convolution forward modeling algorithm in MATLAB and generated synthetic seismic data based on the Marmousi model. Seismic dip estimation was performed using both structure tensor eigenvalue decomposition and PWD. Results demonstrate that PWD is more robust in capturing dominant geological trends, while the structure tensor approach is less stable under noise. A structure-oriented smoothing operator was constructed from the dip estimates. Finally, a structure-constrained inversion objective function was formulated and solved using FISTA to obtain the least-squares solution.
    </div>  
  </li>
</ul>

<span class='anchor' id='educations'></span>

# Educations

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="images/xjtu.jpg" alt="XJTU Logo">
    </div>
    <div class="experience-box-text">
        <p><strong>2023.09 - Now</strong></p>
        <p>Master, <a href="https://www.xjtu.edu.cn/index.htm">Xi'an Jiaotong University</a></p>
        <p>Supervisor: Prof. <a href="https://scholar.google.com/citations?user=53gDhbgAAAAJ&hl=zh-CN&oi=ao">Jinghuai Gao</a></p>
    </div>
</div>

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="images/sau.jpg" alt="SAU Logo">
    </div>
    <div class="experience-box-text">
        <p><strong>2019.09 - 2023.06</strong></p>
        <p>Bachelor, <a href="https://www.sau.edu.cn/">Shenyang Aerospace University</a></p>
    </div>   
</div>