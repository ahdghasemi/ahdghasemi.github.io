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
selected_papers: true
social: true
---

I am a Postdoctoral Research Fellow and Adjunct Faculty in Electrical & Computer Engineering at the University of Massachusetts Amherst. My research is in the **foundations of machine learning**, with a focus on **graph-structured learning**, **learning under dependence**, and **structure-aware complexity**. I study how graph topology, statistical dependence, and problem geometry change the effective difficulty of estimation and generalization, and how these structural effects should inform both theory and algorithm design.

#### Quick pathways
- **Theory overview (graph learning, minimax theory, learning under dependence):** [Open]({{ '/research-theory/' | relative_url }})
- **Systems / CPS / Edge AI overview (deployable ML, autonomy, resource-aware inference):** [Open]({{ '/research-systems/' | relative_url }})

Much of my work starts from a simple observation: classical i.i.d. intuition often breaks down in the graph-structured and dependent settings that matter most in modern machine learning. In these regimes, nominal sample size can be a poor proxy for effective information, and performance may be limited by topology, dependence, or computational budget rather than model capacity alone. My goal is to characterize these limits clearly and use that understanding to develop sharper theory, better diagnostics, and evaluation protocols that remain meaningful in practice.

#### Active projects

- **Minimax limits of graph neural networks:** characterizing when topology and dependence fundamentally limit generalization in message-passing architectures.

- **Deployable graph learning:** low-rank and constrained training methods that control inference cost under latency, memory, and energy budgets.

- **Confidence-guided inference for large models (CGES):** adaptive stopping rules that reduce compute while preserving reasoning accuracy.

- **Trustworthy autonomy in UAV systems (NSF CPS AERIAL):** reliability metrics and validation protocols for learning-enabled autonomous swarms.

**I welcome collaborations in graph algorithms, theoretical machine learning, graph learning, and learning under dependence.**
