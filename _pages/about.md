---
permalink: /
title: "About Me"
excerpt: "About me (Andy)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
**Hey there👋🏻! I’m Zian(Andy) Zheng, an AI enthusiast on a quest for challenges and unexplored horizons.**

- As a CS MMath student at University of Waterloo, I’m always eager to push boundaries and embrace novel ideas.  
- Beyond the study, I thrive on adrenaline-fueled outdoor pursuits like skydiving, scuba diving, free diving, climbing, and kayaking.  
Whether it’s conquering algorithms or mountains, I relish every opportunity to grow, learn, and adapt.

---

**Research Interests**  
Generally, I’m deeply interested in LLMs, VLMs, and AIGC. Here are some research questions I’m currently exploring (along with what I’ve already done):

---

**1. How can we make LLMs/VLMs/Diffusion models more efficient?**  

- **OpenMoE**: We dive into the routing mechanism of Mixture-of-Experts (MoE) models during training, aiming for better load balancing during inference.  
  *Key findings:* context-independent specialization, early routing learning, and drop-towards-the-end.

- **AdaVocab**: Can we speed up SLM inference by sparsely activating the vocabulary for next-token prediction? Turns out, yes.

- **TheMatrix**: (my contribution) How do we achieve real-time, interactive video generation with diffusion models?  
  Think of it as a baby game engine without reward signals — or a stepping stone toward an efficient video-based world model with proper rewards.

---

**2. Can we learn policies in AI-generated virtual worlds with AI feedback?**  

This is a research vision I’m super passionate about — the idea that:  
> *We can generate any environment with a world model and learn any policy inside it using VLM-based feedback — and it might even transfer to the real world.*

**Roadmap (in my head):**

- ✅ **Build action-controllable world models**  
  We now have models like Matrix, Cosmos, etc.

- 🔄 **Wrap the world model + VLM reward into an RL environment (with a Gym interface)**  
  *Status:* ongoing.

**Two key challenges I’m working on:**

- **Efficient world model inference**  
  Inference speed deeply impacts policy learning.  
  *My contribution:* pipelined and parallelized the inference of DiT, VAE, and post-processors in TheMatrix.

- **AI-generated rewards for virtual agents**  
  Can VLMs directly provide reward signals? Or should we let VLMs label preferences to train reward models?  
  *Still figuring it out — stay tuned.*

---

**3. Making Human-AI interaction better**  
*(a.k.a. I’m not just doing research — I build tools too)*

As a heavy LLM/VLM user myself — you know what they say: *sharpen your tools before cutting wood.*  
I'm actively exploring new interaction paradigms for LLMs. I think current chatbot interfaces are far from optimal.

**My Goals:**

- Build systems that let users segment, reuse, and compose dialogue context more effectively — so we can think better, together with AI.  
- Create tools that turn everyday chat history into a **personalized knowledge base** — for reflection, personal review, and knowledge sharing.

---

**Miscellaneous**  

- I have the fortune to be Newton's 18th generation of students. The academic family tree is ![here](/images/AcademicFamilyTree.png).  
- I am an extreme sports lover and adrenaline junkie. You can call me 'Tri-diver Andy' ([skydiver](/images/USPA-A.jpeg), [freediver](/images/AIDA-2star.png), [scuba diver](/images/AOW.jpg)).  
- I like writing poems (in English/Chinese). For example, ![here](/images/poem.png) is one of my poems about life and yet-to-be-discovered love.
