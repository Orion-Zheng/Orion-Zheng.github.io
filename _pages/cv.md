---
layout: archive
title: "Andy's CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
The PDF format is available [here](/files/ZhengZian's_CV.pdf).

Education
======
* **B.Eng. in Data Science, Lanzhou University(LZU)**, 09/2018 - 07/2022
  * **GPA:** 92.8/100, **Ranking:** 1/192
  * **Honors:**
    * China National Scholarship (Top 0.1% Across Nation)
    * Merit Student in Gansu Province (Top 1% Across Province)
* **M.Comp. in Artificial Intelligence, National University of Singapore(NUS)**, 08/2022 - Now
  * **GPA:** 4.42/5,
  * **Advisor:** Prof. [Yang You](https://www.comp.nus.edu.sg/~youy/) (Director of HPC-AI Lab)

Research Experience
======
* **Master Dissertation in HPC-AI Lab, National University of Singapore**, 05/2023 – Now

  Keywords: Data-Centric methods, Mixture-of-Experts Model

  * Working on OpenMoE project (second author) with [Fuzhao Xue](https://xuefuzhao.github.io), which is the **first open-source, decoder-only MoE language model**. We released the code and checkpoint and got **1k+ stars** on [GitHub](https://github.com/XueFuzhao/OpenMoE).
  * Investigated publicly available pre-training corpus (English, Chinese, multilingual, code, etc), preprocessing methods and tokenization techniques. Do experiments comparing tokenizers. Prepare the pre-training, SFT and evaluation datasets in TFDS format.
  *	Worked on the Pytorch implementation of OpenMoE with the ColossalAI team. Performing model evaluations and contributed to the paper writing.


Work Experience
======

* **Artificial Intelligence Engineer Intern, Beijing, HPC-AI Tech**, 07/2023 – 11/2023

  Keywords: Data-Centric methods, Long Context LLM, Retrieval Augmented Generation

  * Extended the LLaMA’s vocabulary for Chinese text and participated in the data cleaning and preparation process in the [Colossal-LLaMA-2 project](https://huggingface.co/hpcai-tech/Colossal-LLaMA-2-7b-base) (achieved **18k+ downloads** on Huggingface so far).
  * Context length extrapolation: Investigated common context extrapolation techniques (e.g. PI, NTK, LongLLaMA , LongLoRA, etc.), training corpus with long data and long-text evaluation methods. Working on constructing Chinese long text training data and doing multi-GPU training to extrapolate Colossal-LLaMA-2.
  * Participated in the [ColossalQA](https://github.com/hpcaitech/ColossalAI/tree/main/applications/ColossalQA) project, a retrieval-based QA framework based on Langchain.
  * Involved in the writing of the book 'Practical Large AI Models', edited by Professor Yang You.

Publications
======
  * OpenMoE: An Early Effort on Open Mixture-of-Experts Language Models [[Code]](https://github.com/XueFuzhao/OpenMoE) [[Paper]](https://arxiv.org/abs/2402.01739) [[Twitter]](https://x.com/XueFz/status/1693696988611739947?s=20) \
    Fuzhao Xue, **Zian Zheng**, Yao Fu, Jinjie Ni, Zangwei Zheng, Wangchunshu Zhou and Yang You