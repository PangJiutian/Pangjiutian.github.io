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

# A Few Publications (more to come, I hope)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2025</div><img src='images/pub1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Iterative Gradient Corrected Semi-Supervised  Seismic Impedance Inversion via Swin Transformer**

**Qi Pang**, Hongling Chen, Jinghuai Gao, et al.

[**Paper**](https://ieeexplore.ieee.org/document/10989649) | [**GitHub**](https://github.com/GeoAI-INV/Iterative-Gradient-Corrected-Swin-Inversion)
</div>
</div>

<span class='anchor' id='educations'></span>

# Educations

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="images/xjtu.jpg" alt="XJTU Logo">
    </div>
    <div class="experience-box-text">
        <p><strong>2023.09 - Now</strong></p>
        <p>Master, <a href="https://www.xjtu.edu.cn/index.htm">Xi’an Jiaotong University</a></p>
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