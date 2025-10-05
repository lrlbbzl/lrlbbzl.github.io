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

Hi! I am Ruilin Luo. I am currently a master student (3rd year) in [Intelligent Interaction Group (IIGroup)](https://iigroup.github.io/), Tsinghua University, supervised by Prof. [Yujiu Yang](https://scholar.google.com/citations?user=4gH3sxsAAAAJ&hl=zh-CN). I received my bachelor's degree in Huazhong University of Science and Technology.

My research interests lie in LLM/MLLM Reasoning and Graph Representation Learning. 

<span class='anchor' id='-edu'></span>

# 🎓 Education

<img class="svg" src="/images/logo-thu.svg" width="50pt"> Tsinghua University 
<br>

- *Sept. 2023 - Present*, Master's Degree in Electronic and Information Engineering, **National Scholarship for Graduate Students**（2025）

<!-- <div><br></div> -->
<!-- <br> -->

<img class="svg" src="/images/hust-logo.svg" width="50pt"> Huazhong University of Science and Technology
<br>

- *Sept. 2019 - June 2023*, Bachelor’s Degree in Computer Science and Technology, GPA 3.96/4.00.


<span class='anchor' id='-intern'></span>

# 🎆 News
- *Sept. 2025*: Qwen3-VL is released! Try stronger reasoning on [Qwen Chat](https://chat.qwen.ai/).
- *Sept. 2025*: URSA has been accepted by **NeurIPS 2025**. See you in San Diego! 
- *Aug. 2025*: FairTAG has been accepted by **EMNLP 2025**. See you in Suzhou! The arXiv preprint and code are coming soon.
- *May 2025*: One paper has been accepted by **ICML 2025**. Congrats to Zicheng.
- *Sept. 2024*: PTD-SQL has been accepted by **EMNLP 2024**. See you in Miami.
- *May 2024*: UniBi has been accepted by **ECML-PKDD 2024** as an oral paper. See you in Vilnius, Lithuania.
- *Feb. 2024*: PReSA has been accepted by **COLING 2024**. See you in Torino, Italy.

# 💻 Interships

<img class="svg" src="/images/qwen-logo.svg" width="30pt"> Alibaba Group, QwenVL Team, Hangzhou 
<br>

- *Mar. 2025 - Present*, Research Intern, Multimodal Large Language Model Reasoning.

<!-- <br> -->

<img class="svg" src="/images/logo-bytedance.svg" width="60pt"> ByteDance, Beijing 
<br>

- *Sept. 2024 - Mar. 2025*, Research Intern, Multimodal Large Language Model Reasoning.

<!-- <br> -->

<img class="svg" src="/images/tencent-logo.svg" width="60pt"> Tencent, Beijing
<br>

- *Jan. 2024 - July 2024*, Research Intern, Large Language Model Code Agent.

<!-- <br> -->

<span class='anchor' id='-pub'></span>

# 📝 Publications

## *Papers on **Large Language Model**:*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/ursa_image.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Unlocking Multimodal Mathematical Reasoning via Process Reward Model**

`Ruilin Luo`, Zhuofan Zheng, Yifan Wang, Xinzhe Ni, Zicheng Lin, Songtao Jiang, Yiyao Yu, Chufan Shi, Ruihang Chu, Lei Wang, Jin zeng, Yujiu Yang

[[Paper]](https://arxiv.org/abs/2501.04686) | [[Code]](https://github.com/URSA-MATH/URSA-MATH)
- We are the first to propose leveraging a process reward model (PRM) to provide process-level optimization in multimodal mathematical reasoning.
- We introduce a training framework addressing three key stages: reasoning data scarcity, reward data scaling, and online PRM-integrated reinforcement learning (RL).
- Our data is used to train [Seed1.5-VL](https://arxiv.org/abs/2505.07062), and we open-source URSA-8B-PS-GRPO, a model whose reasoning capability matches that of the [InternVL3](https://rank.opencompass.org.cn/leaderboard-multimodal-reasoning/?m=REALTIME) series.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/ptdsql-image.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**PTD-SQL: Partitioning and Targeted Drilling with LLMs in Text-to-SQL**

`Ruilin Luo`, Liyuan Wang, Binghuai Lin, Zicheng Lin, Yujiu Yang

[[Paper]](https://aclanthology.org/2024.emnlp-main.221/) | [[Code]](https://github.com/lrlbbzl/PTD-SQL)
- We propose a code agent framework for the text-to-SQL task that leverages structured grammars for question-type classification, followed by question-type-specific automated question bank construction and a two-layer few-shot retrieval mechanism.
- We observe that stronger models achieve greater improvements on harder question types when provided with better-matched few-shot chain-of-thought (CoT) prompts, reflecting a learning pattern aligned with human cognition.
- Our method achieves state-of-the-art (SOTA) performance on benchmarks such as Spider and BIRD.
</div>
</div>

## *Papers on **LLM for Graph Representation Learning**:*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECML-PKDD 2024 Oral</div><img src='images/ecmlpkdd-image.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Prior Bilinear Based Models for Knowledge Graph Completion**

`Ruilin Luo`\*, Jiayi Li\*, Jiaqi Sun, Jing Xiao, Yujiu Yang

[[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-70352-2_19)
- We propose the principle of identity in knowledge graph completion (KGC).
- We introduce a bilinear KGC method that explicitly models the law of identity and outperforms classical approaches such as RESCAL and ComplEx.
- We provide a theoretical derivation for modeling the law of identity.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2024</div><img src='images/coling-image.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Prior Relational Schema Assists Effective Contrastive Learning for Inductive Knowledge Graph Completion**

`Ruilin Luo`, Jiayi Li, Jianghangfan Zhang, Jing Xiao, Yujiu Yang

[[Paper]](https://aclanthology.org/2024.lrec-main.1139/) | [[Code]](https://github.com/lrlbbzl/PReSA)
</div>
</div>

<br>
<span class='anchor' id='-honor'></span>

# 🏅 Honors and Awards

- National Scholarship
- Tsinghua University Comprehensive First-Class Scholarship
- Huazhong University of Science and Technology Outstanding Student

# 🎵 Miscellaneous

- Favorite singers/groups: Wang Leehom, JJ Lin, Jacky Cheung, Eric Chou, LE SSERAFIM, (G)I-DLE, BIGBANG, IZ*ONE
- Hobbies: Cycling, fitness, esports (DOTA 2, CS2), singing, badminton
