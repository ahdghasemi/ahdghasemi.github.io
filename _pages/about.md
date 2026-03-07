---
layout: about
title: About
permalink: /
subtitle: |
  <p class="text-success"><font size="2">
  Graph algorithms and theoretical machine learning <br/>
  Minimax learning theory, graph learning, and structure-aware complexity
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

I am a Postdoctoral Research Fellow and Adjunct Faculty in Electrical & Computer Engineering at the University of Massachusetts Amherst. My research lies in the **foundations of machine learning**, with a focus on **graph-structured learning**, **learning under dependence**, and **structure-aware complexity**. I study how graph topology, statistical dependence, and problem geometry alter the effective difficulty of estimation and generalization, and how these structural effects should inform both theory and algorithm design.

#### Quick pathways
- **Theory overview (graph learning, minimax theory, learning under dependence):** [Open]({{ '/research-theory/' | relative_url }})
- **Systems / CPS / Edge AI overview (deployable ML, autonomy, resource-aware inference):** [Open]({{ '/research-systems/' | relative_url }})

Much of my work starts from a simple observation: classical i.i.d.-based intuition often breaks down in the graph-structured and dependent settings that matter most in modern machine learning. In these regimes, nominal sample size can be a poor proxy for effective information, and performance may be limited by topology, dependence, or computational budget rather than model capacity alone. My goal is to characterize these regimes clearly and use that understanding to build sharper theory, better diagnostics, and more meaningful evaluation protocols.

### Active projects

- **Minimax sample complexity of GNNs under topology and dependence (ICLR 2026):** I developed minimax lower bounds and structural regime characterizations for message-passing GNNs, identifying when generalization follows classical sample-size behavior and when graph-induced dependence and mixing constraints dominate effective sample complexity.

- **Low-rank / compact graph inference for deployable ML:** I study low-rank and constrained training for graph models to make inference cost controllable under latency, energy, and memory limits, while preserving strong performance and tunable deployment tradeoffs.

- **Efficient inference and confidence-guided computation for large models (CGES):** We developed **Confidence-Guided Early Stopping**, a Bayesian stopping rule for budgeted inference that halts sampling when posterior evidence crosses a threshold or a hard budget binds. Across five reasoning benchmarks, CGES reduces model calls by **69.4%** while matching self-consistency accuracy.

- **NSF CPS AERIAL (Co-PI):** I lead work on trustworthy and budget-aware learning-and-control and digital-twin validation protocols for UAV swarm autonomy, with emphasis on reliability metrics, stress testing, and evaluation under operational constraints.

### Research agenda
My current agenda has three connected directions:

1. **Learning under dependence:** minimax limits, regime characterization, and effective sample-size phenomena in graph and sequential settings.
2. **Graph representation learning theory:** topology-aware generalization, structural bottlenecks in message passing, and minimal mechanisms that overcome them.
3. **Efficient and reliable inference:** adaptive computation, confidence-aware stopping, and compute-quality tradeoffs for large models and constrained deployments.

Across these directions, I aim to combine theorem-level analysis with theory-grounded empirical diagnostics that test structural predictions in practice.

**I welcome collaborations in graph algorithms, theoretical machine learning, graph learning, and learning under dependence.**
