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

Hi! I am Ruilin Luo. I am currently a master student (3rd year) in [Intelligent Interaction Group (IIGroup)](https://sites.google.com/view/iigroup-thu/home), Tsinghua University, supervised by Prof. [Yujiu Yang](https://scholar.google.com/citations?user=4gH3sxsAAAAJ&hl=zh-CN). I received my bachelor's degree in Huazhong University of Science and Technology.

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

# 💻 Interships

<img class="svg" src="/images/qwen-logo.svg" width="60pt"> Alibaba Group, QwenVL Team, Hangzhou 
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

# 📝 Projects

## *Papers on **Large Language Model**:*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/paper-rescbm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Unlocking Multimodal Mathematical Reasoning via Process Reward Model**

`Ruilin Luo`, Zhuofan Zheng, Yifan Wang, Xinzhe Ni, Zicheng Lin, Songtao Jiang, Yiyao Yu, Chufan Shi, Ruihang Chu, Lei Wang, Jin zeng, Yujiu Yang

[[Paper]](https://arxiv.org/abs/2501.04686) | [[Code]](https://github.com/URSA-MATH/URSA-MATH)

- We are the first to propose leveraging a process reward model (PRM) to provide process-level optimization in multimodal mathematical reasoning.
- We introduce a training framework addressing three key stages: reasoning data scarcity, reward data scaling, and online PRM-integrated reinforcement learning (RL).
- Our data is used to train [Seed1.5-VL](https://arxiv.org/abs/2505.07062), and we open-source URSA-8B-PS-GRPO, a model whose reasoning capability matches that of the [InternVL3](https://rank.opencompass.org.cn/leaderboard-multimodal-reasoning/?m=REALTIME) series.
  </div>
  </div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/paper-csm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**PTD-SQL: Partitioning and Targeted Drilling with LLMs in Text-to-SQL**

`Ruilin Luo`, Liyuan Wang, Binghuai Lin, Zicheng Lin, Yujiu Yang

[[Paper]](https://aclanthology.org/2024.emnlp-main.221/) | [[Code]](https://github.com/lrlbbzl/PTD-SQL)

- We propose a code agent framework for the text-to-SQL task that leverages structured grammars for question-type classification, followed by question-type-specific automated question bank construction and a two-layer few-shot retrieval mechanism.

- We observe that stronger models achieve greater improvements on harder question types when provided with better-matched few-shot chain-of-thought (CoT) prompts, reflecting a learning pattern aligned with human cognition.

- Our method achieves state-of-the-art (SOTA) performance on benchmarks such as Spider and BIRD.

  </div>
  </div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">under review</div><img src='images/paper-ps.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Compositional Generalization through Brain-inspired Geometric Constraints on Representation Structure**


`Chenming Shang`, Shiji Zhou, Hengyuan Zhang, Xinchen Zhang, Lei Ke, Yuwang Wang, Yujiu Yang

- We establish a quantitative relationship between Parallelism Score (PS) in cognitive neuroscience and the compositional generalization (CG) ability of model representations.
- To optimize the CG performance theoretically, we propose the incorporation of two regularization techniques, Parallelism Score Maximization and Distance Variance Minimization, to enhance the model CG ability.
  </div>
  </div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">under review</div><img src='images/paper-hermesflow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**HermesFlow: Seamlessly Closing the Gap in Multimodal Understanding and Generation**


Ling Yang, Xinchen Zhang, Ye Tian, `Chenming Shang`, Minghao Xu, Wentao Zhang, Bin Cui

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">under review</div><img src='images/paper-anycharv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance**


Zhao Wang, Hao Wen, Lingting Zhu, `Chenming Shang`, Yujiu Yang, Qi Dou

[[Paper]](https://www.arxiv.org/abs/2502.08189) | [[Code]](https://github.com/AnyCharV/AnyCharV)
</div>
</div>


## *Papers on Graph Representation Learning**:*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/paper-multilingual.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**ShifCon: Enhancing Non‑Dominant Language Capabilities with a Shift‑based Contrastive Framework**


Hengyuan Zhang\*, `Chenming Shang`\*, Sizhe Wang, Dongdong Zhang, Feng Yao, Renliang Sun, Yiyao Yu, Yujiu Yang, Furu Wei *(\* denotes equal contribution)*

[[Paper]](https://arxiv.org/abs/2410.19453) | [[Code]](https://github.com/rattlesnakey/ShifCon)

- Based on the singular value decomposition, we define the language subspace.
- We then transfer the non‑dominant language space to the dominant language space through shift projection and leverage contrastive learning to further alignment.
- The non‑dominant language can access richer information from the parameters of LLMs and improve comprehension capability.
  </div>
  </div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023 BEA Workshop</div><img src='images/paper-aclworkshop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Assisting Language Learners: Automated Trans-Lingual Definition Generation via Contrastive Prompt Learning**


Hengyuan Zhang, Dawei Li, Yanran Li, `Chenming Shang`, Chufan Shi, Yong Jiang

[[Paper]](https://arxiv.org/abs/2306.06058)
</div>
</div>


## *Papers on **Human‑Computer Interaction**:*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SYSU Bachelor's Thesis, Rank 1st</div><img src='images/paper-thesis.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Back-door Intervention based Causal Machine Learning Algorithm for Confounders**


`Chenming Shang`, Zhi Jin

- I complete my bachelor's thesis under the guidance of Prof. Jin Zhi, and get 95 points, ranking 1st in the major.
- Based on the back-door intervention formula in causal inference, I propose a causal machine learning algorithm for confounders, applying in the recommendation system to solve the problems of popularity bias and conformity bias.
  </div>
  </div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDD 2024, JCR Q1</div><img src='images/paper-edu.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**A Question-centric Multi-experts Contrastive Learning Framework for Improving the Accuracy and Interpretability of Deep Sequential Knowledge Tracing Models**


Hengyuan Zhang, Zitao Liu, `Chenming Shang`, Dawei Li, Yong Jiang

[[Paper]](https://dl.acm.org/doi/10.1145/3674840) | [[Code]](https://github.com/rattlesnakey/Q-MCKT)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2021</div><img src='images/paper-bmi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Seeing Health with Eyes: Feature Combination for Image-Based Human BMI Estimation**


Junjia Huang\*, `Chenming Shang`\*, Aolin Xiong, Yuxian Pang, Zhi Jin *(\* denotes equal contribution)*

[[Paper]](https://ieeexplore.ieee.org/document/9428234) | [[Code]](https://github.com/FVL2020/Features_for_BMI_estimation)
</div>
</div>
    

## *Papers on **Interdisciplinary Science**:*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Frontiers in Immunology, JCR Q1</div><img src='images/paper-med.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Peripheral PD-1+NK Cells Could Predict the 28-day Mortality in Sepsis Patients**


Jia Tang, `Chenming Shang`, Yue Chang, Wei Jiang, Jun Xu, Leidan Zhang, Lianfeng Lu, Ling Chen, Xiaosheng Liu, Qingjia Zeng , Wei Cao, Taisheng Li

[[Paper]](https://pmc.ncbi.nlm.nih.gov/articles/PMC11215063/)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Cell Symposia</div><img src='images/paper-med-3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Machine Learning-Based Metabolic Phenotyping of Stroke Rehabilitation**


Qingjia Zeng\*, `Chenming Shang`\*, Hongpu Hu *(\* denotes equal contribution)*
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">under review</div><img src='images/paper-med-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Establishment of a Differential Diagnosis Method for AOSD and Lymphoma based on Random Forest Algorithm**


Jia Tang\*, `Chenming Shang`\*, Yue Chang, Wei Jiang, Jun Xu, Leidan Zhang, Lianfeng Lu, Ling Chen, Xiaosheng Liu, Qingjia Zeng , Wei Cao, Taisheng Li *(\* denotes equal contribution)*
</div>
</div>

<br>
<span class='anchor' id='-honor'></span>

# 🏅 Honors and Awards

- National Scholarship
- Tsinghua University Comprehensive First-Class Scholarship
- Huazhong University of Science and Technology Outstanding Student

