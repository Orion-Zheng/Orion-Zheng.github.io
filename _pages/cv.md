---
layout: archive
title: "Zheng Zian's CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
The PDF format is available [here](/files/ZhengZian's CV-20240106.pdf).

Education
======
* **B.Eng. in Data Science, Lanzhou University(LZU)**, 09/2018 - 07/2022
  * **GPA:** 92.8/100, **Ranking:** 1/192
  * **Honors:** 
        * China National Scholarship (Top 0.1% Across Nation) 
        * Merit Student in Gansu Province (Top 1% Across Province)
* **M.Comp. in Artificial Intelligence, National University of Singapore(NUS)**, 08/2022 - Now
  * **GPA:** 4.42/5, **Supervisor:** Prof. [Yang You](https://www.comp.nus.edu.sg/~youy/) (Director of HPC-AI Lab)

Research Experience
======
* **Master Dissertaion in HPC-AI Lab, National University of Singapore**, 05/2023 – Now
  * Working on OpenMoE project (second author) with [Fuzhao Xue](https://xuefuzhao.github.io), which is the **first open-source, decoder-only MoE language model**. We released the code and checkpoint and got ~**750 stars** on [GitHub](https://github.com/XueFuzhao/OpenMoE) and ~**500 likes** on [Twitter](https://twitter.com/xuefz/status/1693696988611739947?s=61&t=shUN33SHHFV3CuEuz26WcA).
  * Investigated publicly available pre-training corpus (English, Chinese, multilingual, code, etc), preprocessing methods and tokenization techniques. Do experiments comparing tokenizers. Prepare the pre-training, SFT and evaluation datasets in TFDS format.
  * Participated in the Pytorch Implementation of OpenMoE. Now conducting literature review of Mixture of Experts models and writing the paper.


Work Experience
======

* **Artificial Intelligence Engineer Intern, Beijing, HPC-AI Tech**, 07/2023 – 11/2023

  **Keywords:** Data-Centric methods, Long Context LLM, Retrieval Augmented Generation

  * Extended the LLaMA’s vocabulary for Chinese text and participated in the data cleaning and preparation process in the [Colossal-LLaMA-2 project](https://huggingface.co/hpcai-tech/Colossal-LLaMA-2-7b-base) (achieved **186,000 downloads** on Huggingface so far).
  * Context length extrapolation: Investigated common context extrapolation techniques (e.g. PI, NTK, LongLLaMA , LongLoRA, etc.), training corpus with long data and long-text evaluation methods. Working on constructing Chinese long text training data and doing multi-GPU training to extrapolate Colossal-LLaMA-2.
  * Participated in the [ColossalQA](https://github.com/hpcaitech/ColossalAI/tree/main/applications/ColossalQA) project, a retrieval-based QA framework based on Langchain.
  * Involved in the writing of the book 'Practical Large AI Models', edited by Professor Yang You.

Publications
======
  * OpenMoE: Open Mixture-of-Experts Language Models [[Code]](https://github.com/XueFuzhao/OpenMoE) [[Blog]](https://www.notion.so/Aug-2023-OpenMoE-v0-2-Release-43808efc0f5845caa788f2db52021879) [[Twitter]](https://x.com/XueFz/status/1693696988611739947?s=20) \
    Fuzhao Xue, **Zian Zheng**, Yao Fu, Jinjie Ni, Zangwei Zheng, Wangchunshu Zhou and Yang You
    ***GitHub repository***
