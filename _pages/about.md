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

I’m Jin Zhou, a Ph.D. candidate in Computer Science at George Mason University, advised by Prof. Songqing Chen. My research explores how machine learning systems can become both more efficient and more responsive to human needs.

On the systems side, I develop efficient neural representations for dynamic 3D and immersive content, with research spanning model compression, neural rendering, representation learning, and video coding. On the human-centered side, I build interactive systems and machine learning models to understand human behavior, perception, and safety in immersive systems.

Across these directions, I enjoy taking open-ended research problems from problem formulation and algorithm design to implementation, experimentation, and rigorous evaluation.

**I am currently exploring Research Engineer and AI Research Scientist opportunities in efficient machine learning, neural representations, and human-centered AI. Actively seeking a full-time position**

🧠 **Efficient AI & Neural Representations** — Developing efficient representations for dynamic 3D and immersive content through model compression, neural rendering, representation learning, and codec-aware optimization.

🤝 **Human-Centered AI & Interaction** — Building intelligent interactive systems and conducting controlled human studies to understand behavior, perception, and safety in immersive and AI-mediated environments.

You can find my publication on <a href='https://scholar.google.com/citations?user=cdj_IUEAAAAJ'><strong>Google Scholar</strong></a>:<br><a href='https://scholar.google.com/citations?user=cdj_IUEAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fscholar.google.com%2Fcitations%3Fuser%3Dcdj_IUEAAAAJ&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE MMSP 2025</div><img src='images/nerfcompressor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**NeRFCompressor: Enhancing Dynamic Scene Representation for Efficient 6-DoF Object Transportation**](https://ieeexplore.ieee.org/abstract/document/11324120)
[[PDF]]('images/NeRFCompressor_MMSP25.pdf')


**Jin Zhou**, Mufeng Zhu, Yao Liu, Songqing Chen 

- Developed **NeRFCompressor**, a codec-aware framework integrating neural representation compression with video encoding to exploit spatial-temporal redundancy in dynamic 3D scenes.

- Designed an end-to-end compression pipeline combining tensor decomposition, quantization, and codec-based encoding for efficient storage and transmission of dynamic 6-DoF content.

- Demonstrated strong rate-distortion performance while preserving reconstruction quality across benchmark dynamic scenes.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ImmerCom 2026</div><img src='images/DynCodec.png' alt="DynCodec" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DynCodec: Codec-Compatible Compression of Dynamic Neural Scene Representations**

**Jin Zhou**, Na Li, Mufeng Zhu, Songqing Chen, Yao Liu

- Designed **DynCodec**, representing dynamic neural scenes as a shared static reference with factorized temporal residuals to reduce inter-frame redundancy and storage overhead.
 
- Developed a codec-compatible representation for efficient dynamic scene storage and transmission while preserving high-fidelity reconstruction.
 
- Evaluated the approach against dynamic neural rendering baselines across reconstruction quality and representation efficiency.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ISMAR 2026</div><img src='images/gender.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Harassment Isn’t Virtual When It Feels Real: Understanding Emotional Impact of Gendered Embodiment in VR**

**Jin Zhou**, Jie Li, Abdallah El Ali, Bo Han, Songqing Chen

- Designed and implemented a controlled social VR research platform in Unity/Ubiq to study how participant, avatar, and virtual harasser gender shape users' responses to harassment.

- Led a mixed-methods research pipeline combining a Qualtrics survey, controlled VR experiments, behavioral ratings, and semi-structured interviews.

- Modeled ordinal discomfort responses using cumulative link mixed-effects models (CLMM) and identified significant effects of gendered embodiment and harasser identity on perceived discomfort.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VR 2024</div><img src='images/hardenvr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**HardenVR: Harassment Detection in Social Virtual Reality**](https://doi.org/10.1109/VR58804.2024.00033)  

**Na Wang***, **Jin Zhou***, Jie Li, Bo Han, Fei Li, Songqing Chen (*Equal contribution)

- Designed a **Transformer-based behavior detection model** using real social VR interaction data and contributed to model optimization and evaluation.
- Built a WebXR-based multi-user research environment and behavioral data pipeline for collecting and analyzing 3D interaction sequences.
- Achieved **98.4% detection accuracy** and validated the system through empirical evaluation and human-subject studies.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Multimedia 2022</div><img src='images/sae.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Exploring Spherical Autoencoder for Spherical Video Content Processing**](https://par.nsf.gov/servlets/purl/10391202)

**Jin Zhou**, Na Li, Yao Liu, Shuochao Yao, Songqing Chen

- Developed a **spherical CNN autoencoder** for learning efficient representations of 360° visual content while accounting for spherical geometry and projection distortion.

- Introduced partial mesh processing and compressive sensing to reduce computational complexity while preserving reconstruction quality.

- Demonstrated improved representation efficiency over conventional 2D autoencoder baselines for immersive visual content.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE MMSP 2024</div><img src='images/mmsp24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Dynamic 6‑DoF Volumetric Video Generation: Software Toolkit and Dataset**](https://doi.org/10.1109/MMSP61759.2024.10743552)  

Mufeng Zhu, Yuan‑Chun Sun, Na Li, **Jin Zhou**, Songqing Chen, Cheng‑Hsin Hsu, Yao Liu  

- Developed a Blender-Python toolkit for generating dynamic 6-DoF volumetric datasets from synthetic 3D assets, supporting point-cloud and NeRF-based representations.
- Contributed to an open-source dataset and benchmarking pipeline for evaluating volumetric video generation and streaming methods.
- 
</div>
</div>


# 📖 Educations
- *2019.08 - 2026.12 (Expected)*, Ph.D. in Computer Science, George Mason University, Fairfax, Virginia, United States
- *2016.01 - 2017.05*, M.S. in Electrical Engineering, George Washington University, Washington D.C., United States


# 💻 Professional Experience
- *2020.05 – Present*, **Graduate Research Assistant**, George Mason University  
  Advised by Prof. Songqing Chen
  
  Conduct research across **machine learning, efficient neural representations, immersive computing, and human-centered AI**.
  
  Develop neural representation and compression methods for dynamic 3D and immersive content using PyTorch and TensorFlow, including end-to-end training, evaluation, and benchmarking pipelines.
  
  Build interactive VR research systems and machine learning models for studying human behavior, perception, and safety in immersive environments.
  
- *2019.09 – Present*, **Graduate Teaching Assistant Lead**, George Mason University  
  Lead and mentor a team of teaching assistants for undergraduate computer science courses, developing Java-based materials covering data structures, algorithms, and software design.

- *2017.07 – 2019.03*, Data Engineer, Noetics Global Technologies, USA  
  Collaborated with technical specialists and engineering teams to design a distributed enterprise application with an optimized MySQL backend.  
  Crafted advanced SQL queries and restructured databases to support large-scale data analysis and extract business-critical insights.  
  Managed a team of five interns, overseeing project timelines and mentoring on foundational data engineering tasks.


<p style="font-size: 0.8em; text-align: center;">
  Built with ❤️ using the <a href="https://github.com/RayeRen/acad-homepage" target="_blank">acad-homepage</a> template by RayeRen.
</p>
