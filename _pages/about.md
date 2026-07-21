---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



Hi! Nice to meet you! 
I am **Chia-Hsuan (Michael) Lee**, currently a senior applied researcher at Capital One AI Foundations team working on post-training for language models. I RL post-trained our first internal foundation model and actively publish research.
I obtained my PhD from the University of Washington where I was advised by [Prof. Mari Ostendorf](https://people.ece.uw.edu/ostendorf/) in the [Natural Language Processing Group](https://nlp.washington.edu/). I also worked with [Prof. Noah A. Smith](https://nasmith.github.io/). 

I was a research intern at Google Brain (2022), co-hosted by [Ankur Bapna](https://scholar.google.com/citations?user=6xaz-r0AAAAJ&hl=en) and [Yu Zhang](https://scholar.google.com/citations?user=EilVnKwAAAAJ&hl=en); interned at Google Research (2021), hosted by [Melvin Johnson](https://scholar.google.com/citations?user=g4oMRgsAAAAJ&hl=en); interned at Microsoft Research NLP group (2020), co-hosted by [Matthew Richardson](https://scholar.google.com/citations?user=IT-vb_kAAAAJ&hl=en) and [Alex Polozov](https://alexpolozov.com/).

My research foucs on **reinforcement learning post-training for large language models** — improving how models reason and act, not just the answers they produce. My work spans:

- **Fine-Grained Rewards for GRPO**: I develop reinforcement learning methods (GRPO / OPD) that improve reasoning capability, including a drift-aware training method that leverages segment-level rewards to raise accuracy while reducing overthinking [DASH](https://arxiv.org/abs/2607.00482). I also proposed [CGD (ICML)](https://arxiv.org/abs/2505.11628), a framework that integrates teacher-generated explanatory critiques and refined responses into SFT.
- **Competence-Aware On-Policy Distillation**: I propose [SEAD](https://arxiv.org/abs/2606.28562) , a new on-policy distillation (OPD) framework that leverages both student and teacher entropy to achieve more effective and efficient OPD.
- **Preference Optimization / Alignment**: I lead the DPO workstream for in-house instruction-tuned LMs — spanning data collection/synthesis, training, and evaluation. I also study data-efficient preference learning [scaling law](https://arxiv.org/abs/2604.08723), showing that a small, carefully selected set of high-quality preference pairs can match datasets several times larger

**Earlier work** explored complementary directions in language modeling: long-context pretraining ([DOCmT5, NAACL 2022](https://aclanthology.org/2022.findings-naacl.32/)), in-context learning ([IC-DST, EMNLP 2022](https://aclanthology.org/2022.findings-emnlp.193/)) and prompt-tuning ([SDP-DST, EMNLP 2021](https://aclanthology.org/2021.emnlp-main.404/)), inference-time routing across models ([OrchestraLLM, NAACL 2024](https://aclanthology.org/2024.naacl-long.79/)), and LLM-free self-correction for small models ([CorrectionLM](https://arxiv.org/abs/2410.18209)).


Here is my <a href="files/CV_0703.pdf" target="_blank">CV</a> 

You can find me at: chiahsuan.li [at] gmail [dot] com 

## Highlights
- 07/2026: Our paper on reducing overthinking with fine-grained structure-aware rewards ([DASH](https://arxiv.org/abs/2607.00482)) is out on arxiv.
- 06/2026: Our paper on efficient on policy distillation via joint entropy ([SEAD](https://arxiv.org/abs/2606.28562)) is out on arxiv.
- 04/2026: Our paper on scaling laws of reasoning preference optimization ([Decomposing the Delta](https://arxiv.org/abs/2604.08723)) is out on arxiv.
- 04/2026: Our paper on Reasoning LM critique-guided distillation ([CGD](https://arxiv.org/abs/2505.11628)) is accepted to ICML 2026.
- 09/2024: I have joined Capital One as an applied researcher.
- 08/2024: I have passed my defense and officially a PhD!