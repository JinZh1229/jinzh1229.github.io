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

I’m Jin Zhou, a Ph.D. candidate in Computer Science at George Mason University. My research bridges Human-Computer Interaction (HCI) and immersive media system optimization.

In HCI, I investigate the ethical and psychological challenges of harassment in social VR and metaverse environments. One line of work focuses on the design of AI-driven detection systems, using Transformer models, behavioral modeling, and WebXR-based deployments to support fairness and safety. Another line addresses the psychological impact of harassment in immersive spaces, supported by large-scale surveys and user studies conducted within a custom-built interactive social VR platform developed in Unity and deployed on VR headsets.

In immersive media systems, I work on optimizing 360-degree video compression using spherical CNNs and autoencoders, and improving dynamic 3D scene representations such as NeRF and other 3D reconstruction models through model quantization, compression-aware training, and perceptual quality-preserving techniques. My work aims to balance transmission efficiency with visual fidelity, and has been published at venues like ACM Multimedia and IEEE VR.

My research interests also include <strong>computer vision</strong>, <strong>neural scene understanding</strong>, and <strong>human-centered AI</strong>. I focus on applying models such as <strong>transformers</strong>, <strong>autoencoders</strong>, and <strong>neural rendering frameworks</strong> to develop perceptually aware, efficient, and socially responsible technologies. You can find my publication record on  
<a href='https://scholar.google.com/citations?user=cdj_IUEAAAAJ'><strong>Google Scholar</strong></a>:<br><a href='https://scholar.google.com/citations?user=cdj_IUEAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fscholar.google.com%2Fcitations%3Fuser%3Dcdj_IUEAAAAJ&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Multimedia 2020</div><img src='images/sae.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Spherical Autoencoder for Spherical Video Content Processing](https://par.nsf.gov/servlets/purl/10391202)

**Jin Zhou**, Na Li, Yao Liu, Shuochao Yao, Songqing Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=cdj_IUEAAAAJ&citation_for_view=cdj_IUEAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Proposed a **spherical CNN autoencoder framework** designed specifically for 360° video, addressing the geometric distortion challenges of spherical content.
- Introduced two key optimizations—**partial mesh processing** and **compressive sensing**—to improve encoding efficiency while significantly reducing computational cost and preserving perceptual quality.
- Achieved a **PSNR gain up to 40 dB**, outperforming standard 2D autoencoders by over **260%**, making the method well-suited for real-time immersive video streaming in VR/AR applications.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VR 2024</div><img src='images/hardenvr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**HardenVR: Harassment Detection in Social Virtual Reality**](https://doi.org/10.1109/VR58804.2024.00033)  
**Na Wang**, **Jin Zhou**, Jie Li, Bo Han, Fei Li, Songqing Chen

[**Project**](https://scholar.google.com/citations?view_op=view_citation&user=cdj_IUEAAAAJ&citation_for_view=cdj_IUEAAAAJ:9yKSN-GCB0IC)  
<strong><span class='show_paper_citations' data='cdj_IUEAAAAJ:9yKSN-GCB0IC'></span></strong>

- Designed and implemented a real-time detection system for harassment behaviors in social VR using Transformer-based spatiotemporal models.
- Developed a WebXR-based multi-user simulation platform and released the SAHARA dataset with labeled 3D behavior logs.
- Achieved 98.4% detection accuracy and validated system performance through structured user studies and empirical evaluation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE MMSP 2024</div><img src='images/mmsp24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Dynamic 6‑DoF Volumetric Video Generation: Software Toolkit and Dataset**](https://doi.org/10.1109/MMSP61759.2024.10743552)  
**Mufeng Zhu**, Yuan‑Chun Sun, Na Li, **Jin Zhou**, Songqing Chen, Cheng‑Hsin Hsu, Yao Liu  

[**Project & Code**](https://6-dof-dynamic-content-software.github.io/)  
<strong><span class='show_paper_citations' data='cdj_IUEAAAAJ: dynamic6dof'></span></strong>

- Released a **Blender-Python toolkit** to generate dynamic 6-DoF volumetric datasets from synthetic 3D assets, compatible with both point-cloud and NeRF-based representations.  
- Constructed a **comprehensive dataset**, including point-cloud sequences and training/testing splits, facilitating fair comparisons across volumetric video models.  
- Enabled multimedia systems research by delivering an **open-source toolkit and compliant dataset** under asset permissions, supporting benchmarking for practical volumetric streaming :contentReference[oaicite:1]{index=1}.

</div>
</div>


# 📖 Educations
- *2019.08 - 2025.12 (Expected)*, Ph.D. in Computer Science, George Mason University , Fairfax, Virginia, United States
- *2016.01 - 2017.05*, Master in Electrical Engineering, George Washington University, Washington D.C., United States


# 💻 Professional Experience
- *2019.09 – Present*, Graduate Teaching Assistant Lead, George Mason University, USA  
  Oversaw and led a team of over 10 teaching assistants across multiple undergraduate programming courses.  
  Coordinated weekly TA training, maintained grading consistency, and facilitated team communication with faculty.  
  Designed and deployed Java-based lab materials and tutorials focused on data structures, algorithms, and software design.  
  Acted as the primary point of contact for curriculum support and student feedback in large-scale CS courses (100+ students).

- *2017.07 – 2019.03*, Data Architect / Engineer, Noetics Global Technologies, USA  
  Collaborated with technical specialists and engineering teams to design a distributed enterprise application with an optimized MySQL backend.  
  Crafted advanced SQL queries and restructured databases to support large-scale data analysis and extract business-critical insights.  
  Managed a team of five interns, overseeing project timelines and mentoring on foundational data engineering tasks.
