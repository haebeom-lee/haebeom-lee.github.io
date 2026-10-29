---
permalink: /
title: "About me"
excerpt: "System 2 intelligence, world models, and scientific discovery"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an Assistant Professor in the School of Electrical Engineering at Korea University. Previously, I was a postdoctoral researcher at KAIST, working with [Prof. Juho Lee](https://juho-lee.github.io/), and at Mila and Université de Montréal, working with [Prof. Yoshua Bengio](https://yoshuabengio.org/). I received my Ph.D. from KAIST, where I was advised by [Prof. Sung Ju Hwang](http://www.sungjuhwang.com/).

## Research Vision

**I want to build AI systems that can discover how the world works, accumulate what they learn, and reason with that knowledge.**

My research is motivated by a fundamental question: *How can an AI system go beyond recognizing patterns to understand the mechanisms behind its observations, and use that understanding to solve new problems?* I view this as an important step toward **System 2 intelligence**: deliberate, evidence-grounded reasoning that can formulate hypotheses, evaluate alternatives, recognize uncertainty, and revise beliefs when new evidence arrives. The goal is not simply to make language models generate longer reasoning traces, but to make their reasoning more reliable, grounded, and adaptive.

I believe **world models** are central to this goal. By a world model, I mean a structured and uncertainty-aware representation of how a system works: its causal relationships, relational rules, mathematical laws, and mechanisms of change. Rather than storing experience only as unstructured text or implicit model parameters, I am interested in **explicit models that an agent can inspect, test, revise, compose, and reuse** across different problems.

Ultimately, I envision agents that operate in a continuous loop: **propose hypotheses, make predictions, seek informative evidence, update their world models, and use the resulting knowledge to reason and act.** In this view, scientific discovery, learning from experience, and intelligent planning are closely connected aspects of the same problem.

## Research Directions

**1. Discovering world models from data and interaction.**  
How can AI infer the rules and mechanisms governing an unfamiliar system from limited observations? I study the discovery of mathematical, causal, and relational models, including the use of language models to propose hypotheses, probabilistic inference to evaluate them, and active experimentation to distinguish between competing explanations.

**2. Accumulating, revising, and reusing knowledge.**  
An intelligent system should learn more than isolated solutions to individual tasks. I am interested in how agents can consolidate experiences into persistent, structured knowledge; reconcile new evidence with prior beliefs; and identify and correct mistaken assumptions. Crucially, agents should be able to build on existing scientific knowledge, determine which known mechanisms apply to a new system, and discover what remains unknown. The aim is to develop world models that can be revised, composed, and reused instead of being reconstructed from scratch for every task.

**3. Reasoning and planning with world models.**  
A world model should do more than explain past observations: it should guide future decisions. I investigate how agents can use learned mechanisms and calibrated uncertainty to reason through unfamiliar situations, select informative actions or experiments, and plan toward goals. This includes developing agents that can improve how they search, reason, and learn from their own experience.

My work draws on Bayesian inference, language models, structured representations, and sequential decision-making. These are tools toward the broader goal of building AI that **learns reusable knowledge about the world and reasons with it**.

## Prospective Students

I welcome motivated students from electrical engineering, computer science, mathematics, and related fields who are excited by questions about intelligence, reasoning, and learning. If these research directions interest you, please feel free to contact me.

- **Undergraduate interns:** Prior experience in AI or machine learning is not required. Curiosity, initiative, and enthusiasm for research matter most.
- **Master's students:** I generally expect some background in AI or machine learning, demonstrated through coursework, research internships, or relevant experience.
- **Ph.D. students:** I expect applicants to have at least one first-authored paper at a leading AI/ML conference, such as NeurIPS, ICML, ICLR, ACL, EMNLP, CVPR, or ICCV.

For prospective graduate students, I strongly recommend completing a research internship in my group for **at least three months** before applying.

## Contact

haebeomlee [at] korea [dot] ac [dot] kr

## Awards

- Global Ph.D. Fellowship Program, 2019–2021
- Google Ph.D. Fellowship Program, 2021
- Outstanding Reviewer, ICML 2020 (Top 33%) and ICML 2022 (Top 10%)

## Publications

### Recent Preprints

- <font size="4">GFlowPO: Generative Flow Network as a Language Model Prompt Optimizer</font>
[[paper]](https://arxiv.org/abs/2602.03358) \\
Junmo Cho\*, Suhan Kim\*, Sangjune An\*, Minsu Kim, Dong Bok Lee, Heejun Lee, Kyu Hyun Choi, Byung-Soo Kim, Sung Ju Hwang, **Hae Beom Lee** \\
(\*: equal contribution) \\
arXiv, 2026

- <font size="4">Let Agents Design How They Search: Automatic Interface Optimization for Agentic Search</font>
[[paper]](https://arxiv.org/abs/2610.29250) \\
Sangjune An, Jaeyoon Jung, Yumin Choi, Jinheon Baek, Junmo Cho, Sung Ju Hwang, **Hae Beom Lee** \\
arXiv, 2026

- <font size="4">Bayesian Model Discovery with Language Models: Closing the Loop between Hypotheses and Experiments</font>
[[paper]](https://arxiv.org/abs/2610.25747) \\
JooKyung Yuh, Byungmin Park\*, Eunseo Choi\*, Jinheon Baek, Junmo Cho, Kyu Hyun Choi, Sung Ju Hwang, Kyong Hwan Jin†, **Hae Beom Lee**† \\
(\*: equal contribution as second authors, †: co-corresponding authors) \\
arXiv, 2026

### Conference Publications

- <font size="4">ProPolar: Progressive Polar Decomposition for Implicit Neural Representations</font>
[[paper]](https://neurips.cc/virtual/2026/poster/148388) \\
Pureum Kim, Younggeon Ryu, Dongyoon Lee, **Hae Beom Lee**†, Kyong Hwan Jin† \\
(†: co-corresponding authors) \\
<span style="color:darkred">**NeurIPS**</span> 2026

- <font size="4">Cost-Sensitive Freeze-thaw Bayesian Optimization for Efficient Hyperparameter Tuning</font>
[[paper]](https://arxiv.org/abs/2405.17918) \\
Dong Bok Lee, Aoxuan Silvia Zhang, Byungjoo Kim, Junhyeon Park, Steven Adriaensen, Juho Lee, Sung Ju Hwang, **Hae Beom Lee** \\
<span style="color:darkred">**NeurIPS**</span> 2025

- <font size="4">Bayesian Neural Scaling Laws Extrapolation with Prior-Fitted Networks</font>
[[paper]](https://arxiv.org/abs/2505.23032) \\
Dongwoo Lee\*, Dong Bok Lee\*, Steven Adriaensen, Juho Lee, Sung Ju Hwang, Frank Hutter, Seon Joo Kim,  **Hae Beom Lee** \\
(\*: equal contribution) \\
<span style="color:darkred">**ICML**</span> 2025

- <font size="4">Delta-AI: Local Objectives for Amortized Inference in Sparse Graphical Models</font>
[[paper]](https://arxiv.org/abs/2310.02423) \\
Jean-Pierre René Falet*, **Hae Beom Lee\***, Nikolay Malkin\*, Chen Sun, Dragos Secrieru, Dinghuai Zhang, Guillaume Lajoie, Yoshua Bengio \\
(\*: equal contribution) \\
<span style="color:darkred">**ICLR**</span> 2024

- <font size="4">Online Hyperparameter Meta-Learning with Hypergradient Distillation</font>
[[paper]](http://arxiv.org/abs/2110.02508) \\
 **Hae Beom Lee**, Hayeon Lee, Jaewoong Shin, Eunho Yang, Timothy M. Hospedales, Sung Ju Hwang \\
<span style="color:darkred">**ICLR**</span> 2022 <span style="color:darkred">**(spotlight)**</span>

- <font size="4">Sequential Reptile: Inter-Task Gradient Alignment for Multilingual Learning</font>
[[paper]](https://arxiv.org/abs/2110.02600) \\
Seanie Lee\*, **Hae Beom Lee\***, Juho Lee, Sung Ju Hwang \\
(\*: equal contribution) \\
<span style="color:darkred">**ICLR**</span> 2022

- <font size="4">Meta-Learning Low Rank Covariance Factors for Energy-Based Deterministic Uncertainty</font>
[[paper]](https://arxiv.org/abs/2110.06381) \\
Jeffrey Ryan Willette, **Hae Beom Lee**, Juho Lee, Sung Ju Hwang \\
<span style="color:darkred">**ICLR**</span> 2022

- <font size="4">Large-Scale Meta-Learning with Continual Trajectory Shifting</font>
[[paper]](https://arxiv.org/pdf/2102.07215.pdf) [[code]](https://github.com/JWoong148/ContinualTrajectoryShifting) \\
Jaewoong Shin\*, **Hae Beom Lee\***, Boqing Gong, Sung Ju Hwang \\
(\*: equal contribution) \\
<span style="color:darkred">**ICML**</span> 2021

- <font size="4">MetaPerturb: Transferable Regularizer for Heterogeneous Tasks and Architectures</font>
[[paper]](https://papers.nips.cc/paper/2020/file/84ddfb34126fc3a48ee38d7044e87276-Paper.pdf) [[code]](https://github.com/JWoong148/metaperturb) \\
Jeongun Ryu\*, Jaewoong Shin\*, **Hae Beom Lee\***, Sung Ju Hwang \\
(\*: equal contribution) \\
<span style="color:darkred">**NeurIPS**</span> 2020 <span style="color:darkred">**(spotlight)**</span>

- <font size="4">Meta-Learning for Short Utterance Speaker Recognition with Imbalance Length Pairs</font>
[[paper]](https://arxiv.org/pdf/2004.02863.pdf) [[code]](https://github.com/seongmin-kye/meta-SR) \\
Seong Min Kye, Youngmoon Jung, **Hae Beom Lee**, Sung Ju Hwang, and Hoirin Kim \\
<span style="color:darkred">**Interspeech**</span> 2020

- <font size="4">Meta Variance Transfer: Learning to Augment from the Others</font>
[[paper]](https://proceedings.icml.cc/static/paper_files/icml/2020/2222-Paper.pdf) \\
Seong Jin Park, Seungju Han, Ji-won Baek, Insoo Kim, Juhwan Song, **Hae Beom Lee**, Jae-Joon Han and Sung Ju Hwang \\
<span style="color:darkred">**ICML**</span> 2020

- <font size="4">Learning to Balance: Bayesian Meta-Learning for Imbalanced and Out-of-distribution Tasks</font>
[[paper]](https://openreview.net/pdf?id=rkeZIJBYvr) [[code]](https://github.com/haebeom-lee/l2b) \\
**Hae Beom Lee\***, Hayeon Lee\*, Donghyun Na\*, Saehoon Kim, Minseop Park, Eunho Yang, Sung Ju Hwang \\
(\*: equal contribution) \\
<span style="color:darkred">**ICLR**</span> 2020 <span style="color:darkred">**(oral presentation)**</span>

- <font size="4">Meta Dropout: Learning to Perturb Latent Features for Generalization</font>
[[paper]](https://openreview.net/pdf?id=BJgd81SYwr) [[code]](https://github.com/haebeom-lee/metadrop) \\
**Hae Beom Lee**, Taewook Nam, Eunho Yang, Sung Ju Hwang \\
<span style="color:darkred">**ICLR**</span> 2020

- <font size="4">DropMax: Adaptive Variational Softmax</font>
[[paper]](https://arxiv.org/pdf/1712.07834.pdf)[[code]](https://github.com/haebeom-lee/dropmax) \\
**Hae Beom Lee**, Juho Lee, Saehoon Kim, Eunho Yang, Sung Ju Hwang \\
<span style="color:darkred">**NeurIPS**</span> 2018

- <font size="4">Uncertainty-Aware Attention for Reliable Interpretation and Prediction</font>
[[paper]](https://arxiv.org/pdf/1805.09653.pdf)[[code]](https://github.com/jayheo/UA) \\
Jay Heo\*, **Hae Beom Lee\***, Saehoon Kim, Juho Lee, Kwang Joon Kim, Eunho Yang, Sung Ju Hwang \\
(\*: equal contribution) \\
<span style="color:darkred">**NeurIPS**</span> 2018

- <font size="4">Deep Asymmetric Multi-task Feature Learning</font>
[[paper]](https://arxiv.org/pdf/1708.00260.pdf)[[code]](https://github.com/haebeom-lee/amtfl) \\
**Hae Beom Lee**, Eunho Yang, Sung Ju Hwang \\
<span style="color:darkred">**ICML**</span> 2018

### Earlier Preprints

- <font size="4">Dataset Condensation with Latent Space Knowledge Factorization and Sharing</font>
[[paper]](http://arxiv.org/abs/2208.10494) \\
**Hae Beom Lee\***, Dong Bok Lee\*, Sung Ju Hwang \\
(\*: equal contribution) \\
arXiv, 2022

- <font size="4">Meta-Learned Confidence for Few-shot Learning</font>
[[paper]](https://arxiv.org/pdf/2002.12017.pdf)[[code]](https://github.com/seongmin-kye/MCT) \\
Sung Min Kye, **Hae Beom Lee**, Hoirin Kim, Sung Ju Hwang \\
arXiv, 2020

- <font size="4">Adaptive Network Sparsification with Dependent Variational Beta-Bernoulli Dropout</font>
[[paper]](https://arxiv.org/pdf/1805.10896.pdf)[[code]](https://github.com/OpenXAIProject/Variational_Dropouts) \\
Juho Lee, Saehoon Kim, Jaehong Yoon, **Hae Beom Lee**, Eunho Yang, Sung Ju Hwang \\
arXiv, 2018
