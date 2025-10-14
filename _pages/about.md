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

Hi, I'm Qi Pang, a third-year Master's student at Xi'an Jiaotong University, where I am fortunate to be supervised by Prof. [Jinghuai Gao](https://scholar.google.com/citations?user=53gDhbgAAAAJ&hl=zh-CN&oi=ao). Prior to this, I received my Bachelor's degree from Shenyang Aerospace University.

I am passionate about solving seismic inverse problems, with a particular focus on leveraging machine learning techniques. In parallel, I have a strong interest in geological modeling, where physics-based simulations enable the construction of realistic synthetic data.

<span style="color:red; font-weight:bold;">🚀 I am currently seeking Ph.D. opportunities starting in Fall 2026</span>, and I am always open to academic collaborations that intersect with my research interests.

Topics I’m Excited About:

- **Seismic inversion guided by multi-source information**  
  *(e.g., using physics-informed machine learning methods, diffusion models)*

- **Geological modeling with realistic priors**  
  *(e.g., geostatistical simulation methods and diffusion models)*

- **Subsurface geoscience with large foundation models**  
  *(grounded in geophysical principles)*

If you are working on similar problems or believe my background could contribute to your group or project, I would love to hear from you. Please feel free to contact me at:
📧 pangjiutian@gmail.com 

<span class='anchor' id='publications'></span>

# 📝 Publications

## Current Research Topics: Geological Modeling/Diffusion Model/Petrophysical Inversion

With the rapid progress of machine learning, high-quality training data has become essential. Yet in geophysics, sensitive data and the lack of open datasets pose major challenges. This drives my research in geological modeling, aiming to create realistic subsurface representations as priors and synthetic training data. My research extends from **numerical simulation** to **generative AI**, seeking to create diverse and realistic datasets that can support a wide range of geophysical applications.

🛠 *Ongoing research*(some progress below)

<p align="center">
  <img src="images/geogen.png" width="600"/>
</p>

## Previous Research Topics: Seismic Impedance Inversion/Transformer/CNN

My research journey began during my Master’s studies, focusing on seismic impedance inversion. Over time, my work progressed from TV to more adaptive structural constraints, from 1D to 2D inversion with improved lateral continuity, and from traditional model-driven approaches to deep learning methods with stronger nonlinear representation capabilities—ranging from CNNs to globally-aware Transformers. These experiences not only deepened my understanding of inverse problems but also fueled my motivation to further explore the underlying methodologies.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2025</div><img src='images/pub1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Iterative Gradient Corrected Semi-Supervised  Seismic Impedance Inversion via Swin Transformer**

**Qi Pang**, Hongling Chen, Jinghuai Gao, et al.

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

<div style="margin-bottom:20px;">
<span style="display: inline-block; background-color:rgb(58, 204, 0); color: white; font-size: 12px; padding: 1px 5px; border-radius: 0px; margin-right: 8px;">
  Experiment
</span>
<a href="https://github.com/PangJiutian/Generating-Time-Shifted-Seismic-Data" target="_blank" style="font-size: 16px;">
  Real-World Time-Shifted Seismic Data Generation
</a>
<div style="margin-top: 4px; font-size: 15px; color: #555;">
  Accurate labeling is critical for deep learning methods in seismic exploration. However, inconsistencies in time-depth relationships often lead to misalignment between well logs and seismic data, resulting in suboptimal training outcomes. This project serves as a precursor for time-shift estimation, aiming to simulate realistic time-shifted seismic data. By leveraging time-depth relationships, we generate large-scale pairs of synthetic time-shifted seismic data to provide high-quality training samples for subsequent deep learning models focused on time-shift estimation.
</div>
</div>

<div style="margin-bottom:20px;">
<span style="display: inline-block; background-color:rgb(58, 204, 0); color: white; font-size: 12px; padding: 1px 5px; border-radius: 0px; margin-right: 8px;">
  Experiment
</span>
<a href="https://github.com/PangJiutian/Model-driven-Seismic-Inversion-with-Structural-Regularization" target="_blank" style="font-size: 16px;">
  Model driven Seismic Inversion with Structural Regularization
</a>
<div style="margin-top: 4px; font-size: 15px; color: #555;">
  I implemented a seismic convolution forward modeling algorithm in MATLAB and generated synthetic seismic data based on the Marmousi model. Seismic dip estimation was performed using both structure tensor eigenvalue decomposition and PWD. Results demonstrate that PWD is more robust in capturing dominant geological trends, while the structure tensor approach is less stable under noise. A structure-oriented smoothing operator was constructed from the dip estimates. Finally, a structure-constrained inversion objective function was formulated and solved using FISTA to obtain the least-squares solution.
</div>  
</div>

<span class='anchor' id='educations'></span>

# 📖 Educations

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
        <p>Supervisor: Prof. <a href="https://yjs.sau.edu.cn/info/1015/3462.htm">Qizhi Fang</a></p>
    </div>   
</div>

<span class="anchor" id="cv"></span>

# 📄 CV

<p>
  <a href="CV_QiPang.pdf" download target="_blank" style="font-size: 16px; text-decoration: none; color: #007acc;">
    📥 Download CV
  </a>
</p>

<span class="anchor" id="hobbies"></span>

# 🎮 Hobbies

When I'm not coding or running simulations, I like to relax (or compete!) through games and sports:

- 🪓 **Don’t Starve Together** – 1000+ hours in the wilderness (and I love eating Meatballs!)  
- ⚔️ **League of Legends** – Chill ARAM grinder / tryhard Top & Jungle main  
- 🏓 **Table Tennis** – Big fan of ping pong! Always up for a quick match  
- 🎲 Also enjoy co-op survival, strategy games, and quirky indie titles

Let’s play sometime!  
🎮 Steam Friend Code: `1034585311`