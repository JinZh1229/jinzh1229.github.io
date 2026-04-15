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

I’m Jin Zhou, a Ph.D. candidate in Computer Science at George Mason University, advised by **Dr. Songqing Chen**(IEEE Fellow). 

I build scalable and production-oriented machine learning systems for immersive and real-world applications. My work focuses on model compression, inference optimization, and performance engineering to reduce latency, memory usage, and compute cost while maintaining stable output quality. In parallel, I conduct large-scale user research in immersive environments to evaluate system behavior, user perception, and safety. I design and run controlled experiments, analyze quantitative and qualitative data, and translate findings into system improvements. This allows me to connect ML system design with real user impact. I work on transmission-efficient 3D and 360° media systems (e.g., NeRF-based pipelines), engineering real-time inference and bandwidth-aware deployment strategies.

**❗️ I am open to positions as a Research Engineer, Machine Learning Engineer, and UX Researcher.**

🧠 HCI & VR Ethics: Investigate harassment in social VR through AI-driven behavior detection and psychological analysis; conduct large-scale user studies in Unity-based immersive platforms.

🎥 3D Visual Computing & Compression: Enhance 360° video and dynamic 3D scene representation (e.g., NeRF, 360-degree video system) using autoencoder, quantization, perceptual modeling, and transmission-aware techniques.

You can find my publication on <a href='https://scholar.google.com/citations?user=cdj_IUEAAAAJ'><strong>Google Scholar</strong></a>:<br><a href='https://scholar.google.com/citations?user=cdj_IUEAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fscholar.google.com%2Fcitations%3Fuser%3Dcdj_IUEAAAAJ&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">


# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/mipcp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DynCodec: Codec-Compatible Compression of Dynamic Neural Scene Representations**

**Jin Zhou**, Na Li, Mufeng Zhu, Songqing Chen, Yao Liu 

– Proposed a compression-aware NeRF extension combining feature factorization and video-codec encoding, achieving significant compression rate with high reconstruction performance.
– Designed scalable feature representations and integrated deferred shading for high-fidelity dynamic scene rendering.
– Validated on the Dynamic reconstruction dataset with outstanding visualization performance and noticeable model-size reduction, demonstrating practical deployment on edge devices.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE MMSP 2025</div><img src='images/nerfcompressor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**NeRFCompressor: Enhancing Dynamic Scene Representation for Efficient 6-DoF Object Transportation**](https://ieeexplore.ieee.org/abstract/document/11324120)

**Jin Zhou**, Mufeng Zhu, Yao Liu, Songqing Chen 

- Designed NeRFCompressor, a model-aware compression system for dynamic NeRF scenes, reducing model size by up to 34× with <2 dB PSNR degradation.

- Engineered a hybrid pipeline combining tensor decomposition, 8-bit quantization, and H.264/YUV444 video encoding for scalable 6-DoF scene transmission.

- Delivered superior rate-distortion performance over VQ-TensoRF on benchmark datasets, enabling real-time rendering on resource-constrained AR/VR platforms.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/gender.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Harassment Isn’t Virtual When It Feels Real: mixed-methods research with users on VR environment**
- Built and implemented a custom Unity3D-based VR environment along with an interactable rating system on a social VR simulated platform, including real-time behavior logging and survey integration, post-study interview.

- Led a mixed-methods study with **60+ online surveys via Qualitrics** and **46+ participants' user study with post-study interview**, combining quantitative surveys and behavioral rating data with qualitative interviews to capture more profound insights.

- Designed and executed a complete research workflow: study design, participant recruitment, large-scale data collection, statistical analysis, and synthesis of findings into actionable outcomes.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VR 2024</div><img src='images/hardenvr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**HardenVR: Harassment Detection in Social Virtual Reality**](https://doi.org/10.1109/VR58804.2024.00033)  

**Na Wang**, **Jin Zhou**, Jie Li, Bo Han, Fei Li, Songqing Chen (Equal contribution)

- Designed and implemented a **detection system for harassment behaviors** in social VR using **Transformer-based spatiotemporal models**.
- Developed a **WebXR-based** multi-user simulation platform and released the SAHARA dataset with labeled 3D behavior logs.
- Achieved **98.4% detection accuracy** and validated system performance through structured user studies and empirical evaluation.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Multimedia 2020</div><img src='images/sae.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Exploring Spherical Autoencoder for Spherical Video Content Processing**](https://par.nsf.gov/servlets/purl/10391202)

**Jin Zhou**, Na Li, Yao Liu, Shuochao Yao, Songqing Chen

- Proposed a **spherical CNN autoencoder framework** designed specifically for 360° video, addressing the geometric distortion challenges of spherical content.
- Introduced two key optimizations—**partial mesh processing** and **compressive sensing**—to improve encoding efficiency while significantly reducing computational cost and preserving perceptual quality.
- Achieved a **PSNR gain up to 40 dB**, outperforming standard 2D autoencoders by over **260%**, making the method well-suited for real-time immersive video streaming in VR/AR applications.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE MMSP 2024</div><img src='images/mmsp24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Dynamic 6‑DoF Volumetric Video Generation: Software Toolkit and Dataset**](https://doi.org/10.1109/MMSP61759.2024.10743552)  

Mufeng Zhu, Yuan‑Chun Sun, Na Li, **Jin Zhou**, Songqing Chen, Cheng‑Hsin Hsu, Yao Liu  

- Released a Blender-Python toolkit to generate dynamic 6-DoF volumetric datasets from synthetic 3D assets, compatible with both point-cloud and NeRF-based representations.  
- Constructed a **comprehensive dataset**, including point-cloud sequences and training/testing splits, facilitating fair comparisons across volumetric video models.  
- Enabled multimedia systems research by delivering an **open-source toolkit and compliant dataset** under asset permissions, supporting benchmarking for practical volumetric streaming: contentReference[oaicite:1]{index=1}.

</div>
</div>


# 📖 Educations
- *2019.08 - 2026.08 (Expected)*, Ph.D. in Computer Science, George Mason University, Fairfax, Virginia, United States
- *2016.01 - 2017.05*, M.S. in Electrical Engineering, George Washington University, Washington D.C., United States


# 💻 Professional Experience
- *2020.05- Present*, Graduate Research Assistant, George Mason University, USA
  Advised by Dr.Songqing Chen
  Designed and optimized scalable ML systems for immersive applications, focusing on **model compression and inference optimization** to reduce latency, memory usage, and compute cost.
  Engineered **compression-aware neural pipelines** (e.g., NeRF-based systems) and built end-to-end training, evaluation, and benchmarking workflows using PyTorch and TensorFlow.
  Led immersive UXR projects on social VR safety, developing AI-based behavior detection systems and conducting controlled user studies to evaluate system performance and user impact.
  
- *2019.09 – Present*, Graduate Teaching Assistant Lead, George Mason University, USA  
  Oversaw and led a team of over 10 teaching assistants across multiple undergraduate programming courses.  
  Coordinated weekly TA training, maintained grading consistency, and facilitated team communication with faculty.  
  Designed and deployed Java-based lab materials and tutorials focused on data structures, algorithms, and software design.  
  Acted as the primary point of contact for curriculum support and student feedback in large-scale CS courses (100+ students).

- *2017.07 – 2019.03*, Data Architect / Engineer, Noetics Global Technologies, USA  
  Collaborated with technical specialists and engineering teams to design a distributed enterprise application with an optimized MySQL backend.  
  Crafted advanced SQL queries and restructured databases to support large-scale data analysis and extract business-critical insights.  
  Managed a team of five interns, overseeing project timelines and mentoring on foundational data engineering tasks.


<p style="font-size: 0.8em; text-align: center;">
  Built with ❤️ using the <a href="https://github.com/RayeRen/acad-homepage" target="_blank">acad-homepage</a> template by RayeRen.
</p>
