---
layout: page
title: Theory-Focused Research
permalink: /research-theory/
nav: true
nav_order: 3
description: Foundations of ML, GNN theory, generative modeling theory, and complexity under dependence
---

My theory-focused work studies the **foundations of machine learning under dependence**, with emphasis on **statistical complexity, minimax analysis, lower bounds, and structure-aware learning theory**. A recurring goal is to identify regimes where classical i.i.d.-based intuition breaks down, prove sharp lower and upper bounds in those regimes, and derive algorithmic consequences for learning and sampling.

### Current themes

- **Minimax learning theory for graph-structured learning (GNNs):** I study how graph topology, dependence, and mixing properties affect the effective sample complexity of message-passing neural architectures. My recent ICLR 2026 paper develops minimax lower bounds and structural regime characterizations for ReLU message-passing GNNs, showing that realistic slowly mixing graphs can induce significantly harder structure-driven rates than classical sample-size scaling would suggest.

- **Structure-aware complexity in generative modeling:** I am extending this line of work toward the **science and theory of generative modeling**, especially:
- complexity of score estimation in diffusion-based models,
- error propagation from score estimation to sampling quality,
- and statistical-computational tradeoffs in sequence-structured settings.

A central theme is that dependence structure (e.g., graph topology or sequence dependence) can govern both statistical and algorithmic difficulty.

- **Efficient inference and compute-quality tradeoffs:** I also study how inference-time budget constraints interact with estimation and decision quality in large models, including confidence-guided stopping and adaptive computation. This provides a practical bridge between complexity theory and deployment-time behavior.

### Representative papers
- **ICLR 2026 (accepted):** *Minimax Sample Complexity of Graph Neural Networks: Lower Bounds and Structural Effects*
- **CGES (under review / arXiv):** *Confidence-Guided Early Stopping for Efficient Inference*

### Methodological perspective
I combine rigorous theorem development with theory-grounded empirical diagnostics designed to distinguish between competing scaling laws and structural regimes.
