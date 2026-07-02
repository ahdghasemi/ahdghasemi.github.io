---
layout: page
title: Theory Research
permalink: /research-theory/
nav: true
nav_order: 3
description: Foundations of graph learning, GNN theory, minimax complexity, and learning under dependence
---

My theory-focused work studies the **foundations of machine learning under dependence**, with emphasis on **statistical complexity**, **minimax analysis**, **lower bounds**, and **structure-aware learning theory**. A recurring goal is to identify regimes where classical i.i.d.-based intuition breaks down, characterize the resulting statistical limits, and derive consequences for learning, inference, and sampling.

### Current themes

- **Minimax learning theory for graph-structured models:** I study how graph topology, dependence, and mixing properties affect the effective sample complexity of message-passing architectures. My recent ICLR 2026 paper develops minimax lower bounds and structural regime characterizations for ReLU message-passing GNNs, showing that slowly mixing graphs can induce substantially harder rates than classical sample-size scaling would suggest.

- **Locality, structure, and decision-making:** I am interested in when local graph representations and message-passing architectures are sufficient for learning on structured decision-making problems. A central question is how graph geometry, dependence, and problem stability affect whether learned policies generalize across instance sizes and distributions.

- **Inference-time complexity and compute-quality tradeoffs:** I study how budget constraints at inference time interact with estimation and decision quality in large models, including confidence-guided stopping and adaptive computation. This provides a bridge between formal complexity questions and deployment-relevant behavior.

- **Structure-aware complexity in generative modeling:** I also study how dependence structure affects statistical and computational difficulty in generative modeling, including score estimation in diffusion-based models, error propagation from score estimation to sampling quality, and sequence-structured settings.

### Selected papers
- **ICLR 2026 (accepted):** *Minimax Sample Complexity of Graph Neural Networks: Lower Bounds and Structural Effects*
- **CGES (under review / arXiv):** *Confidence-Guided Early Stopping for Efficient and Accurate Self-Consistency*

### Methodological perspective
I combine rigorous theorem development with theory-grounded empirical diagnostics designed to distinguish competing scaling laws, identify structural regimes, and test whether observed behavior matches theoretical predictions.
