---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-CV6BK46TMV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-CV6BK46TMV');
</script>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I started my Ph.D. in April 2023, at the Center for Language and Cognition (CLCG), University of Groningen.

My research mainly focuses on low-resource conversational generation, the generalization of factual knowledge across languages, and prompt-based learning for classification. The ultimate goal for me is to achieve Artificial General Intelligence (AGI) someday in the future.

Some of my papers were published at international NLP conferences. See <a href='https://scholar.google.com/citations?hl=en&user=bN9bPVUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> for details.


# 🔥 News
- 2023.12.10: &nbsp; Our paper "[Cross-Lingual Consistency of Factual Knowledge in Multilingual Language Models](https://arxiv.org/abs/2310.10378)" was selected for the Outstanding Paper award in the Multilinguality and Linguistic Diversity track at EMNLP 2023!
- 2023.12.06: &nbsp; Best Data Award of <a href='https://genbench.org/workshop/'> The 1st GenBench Workshop </a> at EMNLP 2023!
- 2023.10.06: &nbsp; Paper accepted by EMNLP 2023! <a href='https://arxiv.org/abs/2310.10378'> Cross-Lingual Consistency of Factual Knowledge in Multilingual Language Models </a>
- 2023.04.01: &nbsp; Ph.D. journey started at the University of Groningen, supervised by <a href='https://www.cs.rug.nl/~bisazza/'> Arianna Bisazza </a>  and <a href='https://staff.fnwi.uva.nl/r.fernandezrovira/'> Raquel Fernández </a>.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> EMNLP 2023 </div><img src='images/916x820.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-Lingual Consistency of Factual Knowledge in Multilingual Language Models](https://arxiv.org/abs/2310.10378) <br> **Jirui Qi**, Raquel Fernández, Arianna Bisazza

Multilingual large-scale Pretrained Language Models (PLMs) have been shown to store considerable amounts of factual knowledge, but large variations are observed across languages. With the ultimate goal of ensuring that users with different language backgrounds obtain consistent feedback from the same model, we study the cross-lingual consistency (CLC) of factual knowledge in various multilingual PLMs. To this end, we propose a Ranking-based Consistency (RankC) metric to evaluate knowledge consistency across languages independently from accuracy. Using this metric, we conduct an in-depth analysis of the determining factors for CLC, both at model level and at language-pair level. Among other results, we find that increasing model size leads to higher factual probing accuracy in most languages, but does not improve cross-lingual consistency. Finally, we conduct a case study on CLC when new factual associations are inserted in the PLMs via model editing. Results on a small sample of facts inserted in English reveal a clear pattern whereby the new piece of knowledge transfers only to languages with which English has a high RankC score.

</div>
</div>

- [Multi-mask label mapping for prompt-based learning](https://ojs.aaai.org/index.php/AAAI/article/view/26579) <br> **Jirui Qi**, Richong Zhang, Jaein Kim, Junfan Chen, Wenyi Qin, Yongyi Mao <br> **AAAI-23**
- [Parameter-free Automatically Prompting: A Latent Pseudo Label Mapping Model for Prompt-based Learning
](https://aclanthology.org/2022.findings-emnlp.291/) <br> **Jirui Qi**, Richong Zhang, Junfan Chen, Jaein Kim, Yongyi Mao <br> **Findings of EMNLP 2022**
- [Cross Domain Few-Shot Learning via Meta Adversarial Training](https://arxiv.org/abs/2202.05713) <br> **Jirui Qi**, Richong Zhang, Chune Li, Yongyi Mao <br> arXiv preprint

# 🎮 Demos
- Interested in having a competition against LMs? Try our [demo](https://huggingface.co/spaces/GroNLP/LM-Explanation-Demo-Soft) here and see if you can beat them!

# 📖 Educations
- 2023.04 - Current: Ph.D. Candidate, Center for Language and Cognition, University of Groningen
- 2020.09 - 2023.01: Master, Beijing Advanced Innovation Center for Big Data and Brain Computing, Beihang University
- 2016.09 - 2020.06: Undergraduate, Beijing Jiaotong University
- 2013.09 - 2016.06: Senior High, The High School Affiliated to Renmin University of China (RDFZ)


<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 


# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)


# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
