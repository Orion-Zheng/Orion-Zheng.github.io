---
layout: archive
title: "Andy's CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
The PDF format is available [here](/files/ZhengZian's_CV_20250408.pdf).


---

**Education**

**MMath**, Computer Science - **University of Waterloo**, Ontario, Canada  
*Sept 2024 – Now*

---

**MComp**, Artificial Intelligence - **National University of Singapore**, Singapore  
*Sept 2022 – May 2024*  
- Advised by Presidential Young Professor [Yang You](https://www.comp.nus.edu.sg/~youy/)

---

**BEng**, Data Science - **Lanzhou University**, Lanzhou, China  
*Sept 2018 – May 2022*  
- GPA: 92.8/100 (Ranking: 1/192)

---

**Research Projects**

**[OpenMoE: An Early Effort on Open Mixture-of-Experts Language Models](https://github.com/XueFuzhao/OpenMoE)**  
- Worked on the PyTorch implementation of **the first open-source, decoder-only MoE language model, OpenMoE**, providing insights about the routing mechanism to the open-source community ([model checkpoint](https://huggingface.co/OrionZheng/openmoe-8b-chat)).  
- Prepared the training dataset, tokenizer and conducted the **model evaluation**.

---

**[Matrix: Infinite-Horizon World Generation with Real-Time Interaction](https://github.com/Orion-Zheng/matrix)**  
- Built a **data collection pipeline** for Cyberpunk 2077, recording per-frame video data and corresponding control signals to support model training.  
- Served as a **core contributor to a multi-GPU inference framework**, implementing Ray-based workers (DiT, VAE, post-processing) and building an interactive frontend/backend system.  
- Delivered the **first real-time game generation demo with user-controllable** inference ([demo](https://drive.google.com/file/d/1GW6eCH-u9jLWs_Br-JJHIBbHXwWN5wuc/view?usp=sharing)).

---

**[AdaVocab: Boosting SLM Inference with Sparse Vocabulary Activation](https://github.com/Orion-Zheng/AdaVocab)**  
- Identified the growing **vocabulary size** as a major bottleneck for the Small Language Model (SLM) **inference efficiency**.  
- Proposed and implemented a **sparsely active vocabulary** method; prepared training data, modeled Trainer, and completed evaluation with teammates.  
- Achieved over **20% computation reduction** and **10% inference speedup** for SLMs in **CPU settings**.

---

**Work Experience**

**HPC-AI Tech**, Artificial Intelligence Engineer Intern  
*Beijing, China | July 2023 – Nov 2023*

- **Extended** LLaMA’s **vocabulary for Chinese** and contributed to **data preparation** in the **Colossal-LLaMA-2** project, selected as an official base model in the [2023 NeurIPS LLM Efficiency Challenge](https://llm-efficiency-challenge.github.io/challenge.html).  
- Investigated common **context length extrapolation** methods (e.g., PI, NTK, LongLoRA), and implemented corresponding **training and evaluation** pipelines to extrapolate Colossal-LLaMA-2 with **multi-GPU training**.  
- Worked on the [ColossalQA](https://github.com/hpcaitech/ColossalAI/tree/main/applications/ColossalQA) project, a **RAG framework** based on Langchain.

---

**Publications**

- **[ICML 2024]** [OpenMoE: An Early Effort on Open Mixture-of-Experts Language Models](https://icml.cc/virtual/2024/poster/35145)  
  *Fuzhao Xue, **_Zian Zheng_**, Yao Fu, Jinjie Ni, Zangwei Zheng, Wangchunshu Zhou, Yang You*  
  *Jan 2024*

- **[ICLR 2025]** [MixEval-X: Any-to-Any Evaluations from Real-World Data Mixtures](https://arxiv.org/pdf/2410.13754)  
  *Jinjie Ni, Yifan Song, Deepanway Ghosal, Bo Li, David Junhao Zhang, Xiang Yue, Fuzhao Xue, **_Zian Zheng_**, Kaichen Zhang, Mahir Shah, Kabir Jain, Yang You, Michael Shieh*  
  *Oct 2024*

- **[Arxiv]** [The Matrix: Infinite-Horizon World Generation with Real-Time Moving Control](https://icml.cc/virtual/2024/poster/35145)  
  *Ruili Feng, Han Zhang, Zhantao Yang, Jie Xiao, Zhilei Shu, Zhiheng Liu, **_Andy Zheng_**, Yukun Huang, Yu Liu, Hongyang Zhang*  
  *Dec 2024*

---

**Teaching & Service**

- **Teaching Assistant:** CS135, CS479/679 at UWaterloo  
- **Reviewers:** ICLR 2025, AISTATS 2025

---

**Honors & Awards**

- **China National Scholarship** (Top 0.1% across nation), Dec 2019 & Dec 2021  
- **Merit Student in Colleges and Universities in Gansu Province** (Top 1% across province), May 2021  
- **Dr. Derick Wood Graduate Scholarship**, Dec 2024
