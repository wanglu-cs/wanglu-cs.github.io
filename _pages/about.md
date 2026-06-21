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

I am a final-year Ph.D. student at the Natural Language Processing and Knowledge Engineering Group (NLPKE), [Institute of Automation, Chinese Academy of Sciences (CASIA)](http://www.ia.ac.cn/). I am fortunate to be advised by [Prof. Jun Zhao](https://zhaojun-nlpr.github.io/). Before that, I obtained my B.E. degree in Software Engineering from [Northeastern University (NEU)](https://www.neu.edu.cn/) in 2021. My research interests include **natural language processing**, **large language models**, and **knowledge engineering**. I have published over **30 papers** at top-tier conferences, including NeurIPS, ICLR, ACL, AAAI, EMNLP, NAACL, and COLING.

# 🔎 Research

My research aims to **advance intelligent agent systems by making them knowledgeable, multimodal, controllable, and grounded in real-world environments**. Specifically, my work focuses on three closely connected directions:

* **Knowledge for Agent**: Providing knowledge to agents through **agentic environments** and **world models**, enabling them to explore, interact, and accumulate experience.

* **Agent for Knowledge**: Developing agents for **knowledge management** and **knowledge discovery**, enabling them to actively collect, organize, analyze, and update knowledge.

* **Social Intelligence**: Applying agents to **social simulation** and **social governance**, enabling them to model, predict, and guide multi-agent interactions and emergent behaviors.

<div style="border-left: 4px solid #e56565; background: #fff5f5; padding: 0.85em 1em; margin: 1em 0 1.25em 0; border-radius: 6px; box-shadow: 0 1px 4px rgba(0,0,0,0.06);">
  <div style="margin-bottom: 0.45em;">
    <i class="fa-solid fa-envelope" style="color:#e56565; margin-right: 8px" aria-hidden="true"></i>
    <span>If you are interested in my work or want to collaborate, feel free to contact me via: <strong>zhuoran.jin@nlpr.ia.ac.cn</strong>.</span>
  </div>
  <div>
    <i class="fa-solid fa-bullhorn" style="color:#e56565; margin-right: 8px" aria-hidden="true"></i>
    <span style="color:#e56565; font-weight:bold;">诚挚欢迎对大模型与智能体方向感兴趣、并有志于提升科研能力的同学交流探讨，期待一起开展有影响力的高质量研究。</span>
  </div>
</div>

# 🔥 News

* *2026-06*:  📰 We released a survey on [Agentic Environment Engineering](https://arxiv.org/pdf/2606.12191), which systematically summarizes recent progress in Environment Modeling, Synthesis, Evaluation, and Application, with nearly 600 papers reviewed.
* *2026-05*:  🏆 I received the President Special Award of UCAS (57 students in UCAS).
* *2026-03*:  🎉 Four papers are accepted by ACL 2026.
* *2026-03*:  🎉 Four papers are accepted by ICLR 2026, including one selected as an Oral presentation (1.1%).
* *2025.09*:  🎉 One paper is accepted by NeurIPS 2025.
* *2025.05*:  🎉 Five paper are accepted by ACL 2025.

# 📝 Publications

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Survey</div><img src='images/publication/aee.png' alt="Agentic Environment Engineering" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agentic Environment Engineering for Large Language Models: A Survey of Environment Modeling, Synthesis, Evaluation, and Application](https://arxiv.org/pdf/2606.12191) \\
Jiachun Li<sup>*</sup>, **Zhuoran Jin**<sup>*</sup>, Tianyi Men<sup>*</sup>, Yupu Hao<sup>*</sup>, Kejian Zhu<sup>*</sup>, Lingshuai Wang<sup>*</sup>, Dongqi Huang<sup>*</sup>, Longxiang Wang<sup>*</sup>, Shengjia Hua<sup>*</sup>, Lu Wang<sup>*</sup>, Jinshan Gao<sup>*</sup>, Hongbang Yuan, Ruilin Xu, Kang Liu, Jun Zhao

[![Paper](https://img.shields.io/badge/Paper-Survey-b31b1b.svg?logo=arxiv)](https://arxiv.org/pdf/2606.12191) [![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Paper-blue.svg)](https://huggingface.co/papers/2606.12191)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/publication/omni.png' alt="Omni-Reward" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Omni-Reward: Towards Generalist Omni-Modal Reward Modeling with Free-Form Preferences](https://openreview.net/forum?id=9C4gVbPqSy) \\
**Zhuoran Jin**<sup>*</sup>, Hongbang Yuan<sup>*</sup>, Kejian Zhu<sup>*</sup>, Jiachun Li, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

[![Paper](https://img.shields.io/badge/Paper-ICLR_2026-b31b1b.svg?logo=openreview)](https://openreview.net/forum?id=9C4gVbPqSy) [![Homepage](https://img.shields.io/badge/Homepage-OmniReward-orange.svg)](https://omnireward.github.io/) [![Code](https://img.shields.io/badge/GitHub-Code-black.svg?logo=github)](https://github.com/HongbangYuan/OmniReward) [![OmniRewardBench](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-OmniRewardBench-blue.svg)](https://huggingface.co/datasets/HongbangYuan/OmniRewardBench) [![OmniRewardData](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-OmniRewardData-blue.svg)](https://huggingface.co/datasets/jinzhuoran/OmniRewardData) [![OmniRewardModel](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-OmniRewardModel-blue.svg)](https://huggingface.co/jinzhuoran/OmniRewardModel)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/publication/mmrv.png' alt="MMR-V" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMR-V: What's Left Unsaid? A Benchmark for Multimodal Deep Reasoning in Videos](https://openreview.net/forum?id=xk8EqWDPQw) \\
Kejian Zhu, **Zhuoran Jin**, Hongbang Yuan, Jiachun Li, Shangqing Tu, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

[![Paper](https://img.shields.io/badge/Paper-ICLR_2026-b31b1b.svg?logo=acclaim)](https://openreview.net/forum?id=xk8EqWDPQw) [![Homepage](https://img.shields.io/badge/Homepage-MMR_V-orange.svg)](https://mmr-v.github.io/) [![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-MMR_V_Bench-blue.svg)](https://huggingface.co/datasets/JokerJan/MMR-VBench)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/publication/rwku.png' alt="RWKU" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RWKU: Benchmarking Real-World Knowledge Unlearning for Large Language Models](http://papers.nips.cc/paper_files/paper/2024/hash/b1f78dfc9ca0156498241012aec4efa0-Abstract-Datasets_and_Benchmarks_Track.html) \\
**Zhuoran Jin**, Pengfei Cao, Chenhao Wang, Zhitao He, Hongbang Yuan, Jiachun Li, Yubo Chen, Kang Liu, Jun Zhao

[![Paper](https://img.shields.io/badge/Paper-NeurIPS_2024-b31b1b.svg?logo=neurips)](http://papers.nips.cc/paper_files/paper/2024/hash/b1f78dfc9ca0156498241012aec4efa0-Abstract-Datasets_and_Benchmarks_Track.html) [![Homepage](https://img.shields.io/badge/Homepage-RWKU-orange.svg)](https://rwku-bench.github.io/) [![GitHub](https://img.shields.io/badge/GitHub-Code-black.svg?logo=github)](https://github.com/jinzhuoran/RWKU) [![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-RWKU-blue.svg)](https://huggingface.co/datasets/jinzhuoran/RWKU)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/publication/ph3.png' alt="PH3" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cutting Off the Head Ends the Conflict: A Mechanism for Interpreting and Mitigating Knowledge Conflicts in Language Models](https://aclanthology.org/2024.findings-acl.70) \\
**Zhuoran Jin**, Pengfei Cao, Hongbang Yuan, Yubo Chen, Jiexin Xu, Huaijun Li, Xiaojian Jiang, Kang Liu, Jun Zhao

[![Paper](https://img.shields.io/badge/Paper-ACL_2024-b31b1b.svg?logo=acclaim)](https://aclanthology.org/2024.findings-acl.70/)

</div>
</div>

## 2026

* Look Light, Think Heavy: What Multimodal Chain-of-Thought Reasoning Can and Cannot Do. **ACL 2026**.<br>
  **Zhuoran Jin**, Kejian Zhu, Hongbang Yuan, Yupu Hao, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* Empowering GUI Agents via Autonomous Experience Exploration and Hindsight Experience Utilization for Task Planning. **ACL 2026**.<br>
  Tianyi Men, **Zhuoran Jin**, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* Towards Explainable Diagnosis: A Self-learned Explanatory Knowledge Base Approach. **ACL 2026**.<br>
  Dongqi Huang, Tong Zhou, **Zhuoran Jin**, Shenghui Shi, maoyujiao, Kang Liu, Jun Zhao, Yubo Chen

* Pushing the Limits of LLM Tool Calling via Experiential Knowledge Integration and Activation. **ACL Findings 2026**.<br>
  Yupu Hao, **Zhuoran Jin**, Huanxuan Liao, Kang Liu, Jun Zhao

* [Omni-Reward: Towards Generalist Omni-Modal Reward Modeling with Free-Form Preferences](https://openreview.net/forum?id=9C4gVbPqSy). **ICLR 2026 (<span style="color:#FF0000;"><strong>Oral</strong></span>)**.<br>
  **Zhuoran Jin**<sup>*</sup>, Hongbang Yuan<sup>*</sup>, Kejian Zhu<sup>*</sup>, Jiachun Li, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [MMR-Life: Piecing Together Real-life Scenes for Multimodal Multi-image Reasoning](https://openreview.net/forum?id=ds8bBklDV5). **ICLR 2026**.<br>
  Jiachun Li, Shaoping Huang, **Zhuoran Jin**, Chenlong Zhang, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [MMR-V: What's Left Unsaid? A Benchmark for Multimodal Deep Reasoning in Videos](https://openreview.net/forum?id=xk8EqWDPQw). **ICLR 2026**.<br>
  Kejian Zhu, **Zhuoran Jin**, Hongbang Yuan, Jiachun Li, Shangqing Tu, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [Fixing the Broken Compass: Diagnosing and Improving Inference-Time Reward Modeling](https://openreview.net/forum?id=hsBBYOqph2). **ICLR 2026**.<br>
  Jiachun Li, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Jiexin Xu, Huaijun Li, Xiaojian Jiang, Kang Liu, Jun Zhao

## 2025

* [RULE: Reinforcement UnLEarning Achieves Forget-retain Pareto Optimality](https://openreview.net/forum?id=heIh4lkBEd). **NeurIPS 2025**.<br>
  Chenlong Zhang, **Zhuoran Jin**, Hongbang Yuan, Jiaheng Wei, Tong Zhou, Kang Liu, Jun Zhao, Yubo Chen

* [Agent-RewardBench: Towards a Unified Benchmark for Reward Modeling across Perception, Planning, and Safety in Real-World Multimodal Agents](https://aclanthology.org/2025.acl-long.857/). **ACL 2025**.<br>
  Tianyi Men, **Zhuoran Jin**, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [A Troublemaker with Contagious Jailbreak Makes Chaos in Honest Towns](https://aclanthology.org/2025.acl-long.859/). **ACL 2025 (<span style="color:#FF0000;"><strong>SAC Highlights</strong></span>)**.<br>
  Tianyi Men, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Kang Liu, Jun Zhao

* [Evaluating Personalized Tool-Augmented LLMs from the Perspectives of Personalization and Proactivity](https://aclanthology.org/2025.acl-long.1064/). **ACL 2025**.<br>
  Yupu Hao, Pengfei Cao, **Zhuoran Jin**, Huanxuan Liao, Yubo Chen, Kang Liu, Jun Zhao

* [Establishing Trustworthy LLM Evaluation via Shortcut Neuron Analysis](https://aclanthology.org/2025.acl-long.192/). **ACL 2025**.<br>
  Kejian Zhu, Shangqing Tu, **Zhuoran Jin**, Lei Hou, Juanzi Li, Jun Zhao

* [RAG-RewardBench: Benchmarking Reward Models in Retrieval Augmented Generation for Preference Alignment](https://aclanthology.org/2025.findings-acl.877/). **ACL Findings 2025**.<br>
  **Zhuoran Jin**, Hongbang Yuan, Tianyi Men, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [MIRAGE: Evaluating and Explaining Inductive Reasoning Process in Language Models](https://openreview.net/forum?id=tZCqSVncRf/). **ICLR 2025**.<br>
  Jiachun Li, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Kang Liu, Jun Zhao

* [DTELS: Towards Dynamic Granularity of Timeline Summarization](https://aclanthology.org/2025.naacl-long.136/). **NAACL 2025**.<br>
  Chenlong Zhang, Tong Zhou, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Kang Liu, Jun Zhao

* [Beyond Under-Alignment: Atomic Preference Enhanced Factuality Tuning for Large Language Models](https://aclanthology.org/2025.findings-naacl.354/). **NAACL Findings 2025**.<br>
  Hongbang Yuan, Yubo Chen, Pengfei Cao, **Zhuoran Jin**, Kang Liu

* [Towards Robust Knowledge Unlearning: An Adversarial Framework for Assessing and Improving Unlearning Robustness in Large Language Models](https://ojs.aaai.org/index.php/AAAI/inproceedings/view/34769). **AAAI 2025**.<br>
  Hongbang Yuan<sup>*</sup>, **Zhuoran Jin**<sup>*</sup>, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [CITI: Enhancing Tool Utilizing Ability in Large Language Models Without Sacrificing General Performance](https://ojs.aaai.org/index.php/AAAI/article/view/34573). **AAAI 2025**.<br>
  Yupu Hao, Pengfei Cao, **Zhuoran Jin**, Huanxuan Liao, Yubo Chen, Kang Liu, Jun Zhao

## 2024

* [RWKU: Benchmarking Real-World Knowledge Unlearning for Large Language Models](http://papers.nips.cc/paper_files/paper/2024/hash/b1f78dfc9ca0156498241012aec4efa0-Abstract-Datasets_and_Benchmarks_Track.html). **NeurIPS 2024**.<br>
  **Zhuoran Jin**, Pengfei Cao, Chenhao Wang, Zhitao He, Hongbang Yuan, Jiachun Li, Yubo Chen, Kang Liu, Jun Zhao

* [Whispers that Shake Foundations: Analyzing and Mitigating False Premise Hallucinations in Large Language Models](https://aclanthology.org/2024.emnlp-main.155). **EMNLP 2024**.<br>
  Hongbang Yuan, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Daojian Zeng, Kang Liu, Jun Zhao

* [Unlocking the Future: Exploring Look-Ahead Planning Mechanistic Interpretability in Large Language Models](https://aclanthology.org/2024.emnlp-main.440). **EMNLP 2024**.<br>
  Tianyi Men, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Kang Liu, Jun Zhao

* [LINKED: Eliciting, Filtering and Integrating Knowledge in Large Language Model for Commonsense Reasoning](https://aclanthology.org/2024.findings-emnlp.519). **EMNLP Findings 2024**.<br>
  Jiachun Li, Pengfei Cao, Chenhao Wang, **Zhuoran Jin**, Yubo Chen, Kang Liu, Xiaojian Jiang, Jiexin Xu, Jun Zhao

* [AgentsCourt: Building Judicial Decision-Making Agents with Court Debate Simulation and Legal Knowledge Augmentation](https://aclanthology.org/2024.findings-emnlp.549). **EMNLP Findings 2024**.<br>
  Zhitao He, Pengfei Cao, Chenhao Wang, **Zhuoran Jin**, Yubo Chen, Jiexin Xu, Huaijun Li, Kang Liu, Jun Zhao

* [Focus on Your Question! Interpreting and Mitigating Toxic CoT Problems in Commonsense Reasoning](https://aclanthology.org/2024.acl-long.499). **ACL 2024**.<br>
  Jiachun Li, Pengfei Cao, Chenhao Wang, **Zhuoran Jin**, Yubo Chen, Daojian Zeng, Kang Liu, Jun Zhao

* [MULFE: A Multi-Level Benchmark for Free Text Model Editing](https://aclanthology.org/2024.acl-long.732/). **ACL 2024**.<br>
  Chenhao Wang, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Daojian Zeng, Kang Liu, Jun Zhao

* [Cutting Off the Head Ends the Conflict: A Mechanism for Interpreting and Mitigating Knowledge Conflicts in Language Models](https://aclanthology.org/2024.findings-acl.70). **ACL Findings 2024**.<br>
  **Zhuoran Jin**, Pengfei Cao, Hongbang Yuan, Yubo Chen, Jiexin Xu, Huaijun Li, Xiaojian Jiang, Kang Liu, Jun Zhao

* [Tug-of-War between Knowledge: Exploring and Resolving Knowledge Conflicts in Retrieval-Augmented Language Models](https://aclanthology.org/2024.lrec-main.1466). **COLING 2024**.<br>
  **Zhuoran Jin**, Pengfei Cao, Yubo Chen, Kang Liu, Xiaojian Jiang, Jiexin Xu, Qiuxia Li, Jun Zhao

* [Zero-Shot Cross-Lingual Document-Level Event Causality Identification with Heterogeneous Graph Contrastive Transfer Learning](https://aclanthology.org/2024.lrec-main.1551). **COLING 2024**.<br>
  Zhitao He, Pengfei Cao, **Zhuoran Jin**, Yubo Chen, Kang Liu, Zhiqiang Zhang, Mengshu Sun, Jun Zhao

## 2023

* [InstructoR: Instructing Unsupervised Conversational Dense Retrieval with Large Language Models](https://aclanthology.org/2023.findings-emnlp.443/). **EMNLP Findings 2023**.<br>
  **Zhuoran Jin**, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [Alignment Precedes Fusion: Open-Vocabulary Named Entity Recognition as Context-Type Semantic Matching](https://aclanthology.org/2023.findings-emnlp.974/). **EMNLP Findings 2023**.<br>
  **Zhuoran Jin**, Pengfei Cao, Zhitao He, Yubo Chen, Kang Liu, Jun Zhao

* [Zero-Shot Cross-Lingual Event Argument Extraction with Language-Oriented Prefix-Tuning](https://ojs.aaai.org/index.php/AAAI/article/view/26482). **AAAI 2023**.<br>
  Pengfei Cao<sup>*</sup>, **Zhuoran Jin**<sup>*</sup>, Yubo Chen, Kang Liu, Jun Zhao

## 2022 and Earlier

* [A Good Neighbor, A Found Treasure: Mining Treasured Neighbors for Knowledge Graph Entity Typing](https://aclanthology.org/2022.emnlp-main.31/). **EMNLP 2022**.<br>
  **Zhuoran Jin**, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao

* [CogKTR: A Knowledge-Enhanced Text Representation Toolkit for Natural Language Understanding](https://aclanthology.org/2022.emnlp-demos.1/). **EMNLP Demo 2022**.<br>
  **Zhuoran Jin**<sup>*</sup>, Tianyi Men<sup>*</sup>, Hongbang Yuan<sup>*</sup>, Yuyang Zhou, Pengfei Cao, Yubo Chen, Zhipeng Xue, Kang Liu, Jun Zhao

* [CogKGE: A Knowledge Graph Embedding Toolkit and Benchmark for Representing Multi-source and Heterogeneous Knowledge](https://aclanthology.org/2022.acl-demo.16/). **ACL Demo 2022**.<br>
  **Zhuoran Jin**<sup>*</sup>, Tianyi Men<sup>*</sup>, Hongbang Yuan<sup>*</sup>, Zhitao He, Dianbo Sui, Chenhao Wang, Zhipeng Xue, Yubo Chen, Jun Zhao

* [CogIE: An Information Extraction Toolkit for Bridging Texts and CogNet](https://aclanthology.org/2021.acl-demo.11/). **ACL Demo 2021**.<br>
  **Zhuoran Jin**, Yubo Chen, Dianbo Sui, Chenhao Wang, Zhipeng Xue, Jun Zhao

# 🎖 Honors and Awards

* *2026*, President Special Award, Chinese Academy of Sciences. (中国科学院院长特别奖，中科院研究生最高奖项)

* *2026*, Outstanding Doctor Graduates, Beijing. (北京市优秀毕业生)

* *2026*, Outstanding Graduates, University of Chinese Academy of Sciences. (中国科学院大学优秀毕业生)

* *2025*, Wang Shouwu Scholarship, University of Chinese Academy of Sciences. (王守武奖学金)

* *2023*, Second Prize of the Pandeng Scholarship, Institute of Automation. (攀登奖学金二等奖)

* *2022*, Merit Student, University of Chinese Academy of Sciences. (中国科学院大学优秀学生)

* *2021*, Outstanding Graduate, Liaoning Province. (辽宁省优秀毕业生)

# 💼 Services

* *2025-2026*, Teaching Assistant of Knowledge Engineering, University of Chinese Academy of Sciences.

* *2022-2024*, Student Executive Committee Member, Youth Working Committee, Chinese Information Processing Society of China. (中文信息学会青工委学生委员)

* *2023*, Program Chair, The China Student Symposium on Natural Language Processing, CSSNLP 2023. (CSSNLP 2023 程序委员会主席)

* *2022*, Program Chair, EMNLP 2022 Paper Pre-Presentation Session. (EMNLP 2022 论文预讲会主席)

* Regular reviewer for NeurIPS, ICLR, ICML, ACL, EMNLP, NAACL, and TNNLS.

# 📖 Educations

* *2021.09 - 2026.06*, Ph.D., School of Artificial Intelligence, University of Chinese Academy of Sciences, supervised by [Prof. Jun Zhao](https://zhaojun-nlpr.github.io/).

* *2017.09 - 2021.06*, B.E., School of Software Engineering, Northeastern University.
