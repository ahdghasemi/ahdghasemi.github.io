---
layout: about
title: About
permalink: /
subtitle: |
  <p class="text-success"><font size="2">
  Graph algorithms and theoretical machine learning <br/>
  Graph learning, minimax theory, and learning under dependence
  </font></p>

profile:
  align: right
  image: 20190309_105621_ahmad.jpg
  image_circular: false
  more_info: |
    <p>Department of Electrical & Computer Engineering</p>
    <p>University of Massachusetts Amherst</p>
    <p><mark> aghasemi (at) umass [dot] edu </mark></p>

news: true
latest_posts: false
selected_papers: false
social: true
---

I am a Postdoctoral Research Fellow and Adjunct Faculty in Electrical & Computer Engineering at the University of Massachusetts Amherst. My research is in the **foundations of machine learning**, with a focus on **graph-structured learning**, **learning under dependence**, and **structure-aware complexity**. I study how graph topology, statistical dependence, and problem geometry change the effective difficulty of estimation and generalization, and how these structural effects should inform both theory and algorithm design.

#### Quick pathways
- **Theory overview (graph learning, minimax theory, learning under dependence):** [Open]({{ '/research-theory/' | relative_url }})
- **Systems overview (deployable ML, autonomy, resource-aware inference):** [Open]({{ '/research-systems/' | relative_url }})

Much of my work starts from a simple observation: classical i.i.d. intuition often breaks down in the graph-structured and dependent settings that matter most in modern machine learning. In these regimes, nominal sample size can be a poor proxy for effective information, and performance may be limited by topology, dependence, or computational budget rather than model capacity alone. My goal is to characterize these limits clearly and use that understanding to develop sharper theory, better diagnostics, and evaluation protocols that remain meaningful in practice.

#### Active projects

- **Minimax limits of graph neural networks:** characterizing when topology and dependence fundamentally limit generalization in message-passing architectures.

- **Local graph learning for structured decision-making**: studying when message-passing architectures can support reliable learning across structured optimization and decision problems.

- **Deployable graph learning:** low-rank and constrained training methods that control inference cost under latency, memory, and energy budgets.

- **Confidence-guided inference for large models (CGES):** adaptive stopping rules that reduce compute while preserving reasoning accuracy.

- **Trustworthy autonomy in UAV systems (NSF CPS AERIAL):** reliability metrics and validation protocols for learning-enabled autonomous swarms.

#### Selected publications

- **Minimax Sample Complexity of Graph Neural Networks: Lower Bounds and Structural Effects**  
  Ahmad Ghasemi and Hossein Pishro-Nik.  
  *International Conference on Learning Representations (ICLR), 2026.*  
  [Read the paper](https://openreview.net/pdf?id=P2GIT8LpV2)

- **Constrained Optimization for Low-Rank Training of Graph Neural Networks**  
  Sajjad Amini*, Ahmad Ghasemi*, and Hossein Pishro-Nik.  
  *Under review.*

- **CGES: Confidence-Guided Early Stopping for Efficient and Accurate Self-Consistency**  
  Ehsan Aghazade, Ahmad Ghasemi, Hamed Beyhaghi, and Hossein Pishro-Nik.  
  *Efficient Reasoning Workshop @ NeurIPS 2025, Spotlight.*  
  [Read the paper](https://arxiv.org/pdf/2511.02603)

- **Adversarial Attacks on Graph Neural Networks-Based Spatial Resource Management in P2P Wireless Communications**  
  Ahmad Ghasemi, Erfan Zeraatkar, Morteza Moradikia, and Reza Zekavat.  
  *IEEE Transactions on Vehicular Technology, 2024.*  
  [Read the paper](https://doi.org/10.1109/TVT.2024.3358505)

- **Tiny Graph Neural Networks for Radio Resource Management**  
  Ahmad Ghasemi and Hossein Pishro-Nik.  
  *tinyML Research Symposium, 2024.*  
  [Read the paper](https://dl.acm.org/doi/10.1145/3662033.3662036)

**I welcome collaborations in graph algorithms, theoretical machine learning, graph learning, and learning under dependence.**
