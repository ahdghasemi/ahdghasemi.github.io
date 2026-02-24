---
layout: about
title: About
permalink: /
subtitle: |
  <p class="text-success"><font size="2">
  Foundations of ML under dependence <br/>
  Minimax learning theory, graph learning, generative modeling, and efficient inference
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

I am a Postdoctoral Research Fellow and Adjunct Faculty in Electrical & Computer Engineering at the University of Massachusetts Amherst. My research is in the **foundations of machine learning**, with an emphasis on **statistical complexity, minimax analysis, and structure-aware learning theory**. I study how **dependence structure, topology, and problem geometry** change the effective difficulty of estimation, generalization, and sampling, and how these changes should inform algorithm and system design.

My work spans two linked threads: **(i)** foundations of learning under dependence (including minimax lower bounds, regime characterization, and structure-aware complexity, especially for graph-structured learning), and **(ii)** efficient and reliable inference in modern ML systems, including large-model inference and resource-constrained settings. I also build theory-grounded evaluation pipelines and diagnostics in networked/autonomous environments as stress tests for deployable learning methods.

<div style="max-width: 680px; margin: 18px 0 12px 0; display: flow-root; box-sizing: border-box;">
  <div style="
    background: #f6f8fa;
    border: 1px solid #e5e7eb;
    border-left: 4px solid #22c55e;
    padding: 12px 14px;
    border-radius: 10px;
    box-sizing: border-box;
  ">
    <div style="font-size: 0.92rem; font-weight: 700; margin-bottom: 6px;">
      Research focus
    </div>
    <div style="font-size: 0.92rem; line-height: 1.45;">
      I study <b>structure-dependent statistical and algorithmic complexity</b> in modern ML,
      with emphasis on <b>learning under dependence</b>, <b>minimax limits</b>, and
      <b>efficient inference / sampling under compute constraints</b>.
    </div>
  </div>
</div>

### Quick pathways
- **Theory-focused overview (GNNs, minimax learning theory, generative modeling theory):** [Open]({{ '/research-theory/' | relative_url }})
- **Systems / CPS / Edge AI overview (deployable ML, autonomy, resource-aware inference):** [Open]({{ '/research-systems/' | relative_url }})


Much of my work starts from a simple observation: classical i.i.d.-based intuition often fails in the settings that matter most for modern ML, including graph-structured data, sequential dependence, and constrained inference. In these regimes, nominal sample size can be a poor proxy for effective information, and performance may be limited by dependence, mixing, or computational budget rather than model capacity alone. My approach is to identify the relevant structural regime, prove sharp lower/upper bounds where possible, and use those results to design diagnostics, algorithms, and evaluation protocols that remain meaningful in practice.

### Active projects and proof points

- **Minimax sample complexity of GNNs under dependence/topology (ICLR 2026):** I developed minimax lower bounds and structural regime characterizations for message-passing GNNs, identifying when generalization follows classical sample-size behavior versus when graph-induced dependence and mixing constraints dominate the effective sample complexity.

- **Efficient inference and confidence-guided computation for large models (CGES):** We developed **Confidence-Guided Early Stopping**, a Bayesian stopping rule for budgeted inference that halts sampling when posterior evidence crosses a threshold (or a hard budget binds). Across five reasoning benchmarks, CGES reduces model calls by **69.4%** while matching self-consistency accuracy.

- **Low-rank / compact graph inference for deployable ML:** I work on low-rank and constrained training for graph models to make inference cost controllable under latency/energy/memory limits, including large compression gains with modest performance degradation and tunable deployment tradeoffs.

- **NSF CPS AERIAL (Co-PI):** I lead work on trustworthy and budget-aware learning-and-control and digital-twin validation protocols for UAV swarm autonomy, with emphasis on reliability metrics, stress testing, and evaluation under operational constraints.

### Research agenda
My current research agenda centers on **structure-aware complexity in modern machine learning**, with three connected directions:

1. **Learning and inference under dependence:** minimax limits, regime characterization, and effective sample-size phenomena in graph and sequential settings.
2. **Generative modeling theory:** score estimation complexity, error propagation to sampling quality, and statistical-computational tradeoffs in diffusion-based generation.
3. **Efficient and reliable inference:** adaptive computation, confidence-aware stopping, and compute-quality tradeoffs for large models and constrained deployments.

Across these directions, I aim to combine theorem-level analysis with theory-grounded empirical diagnostics that distinguish regimes and test predicted scaling behavior. 

### Teaching
I teach ML, generative models, DSP, image processing, and data science foundations, with an emphasis on linking theory to reproducible engineering practice. My goal is to help students move from technical familiarity to research-grade reasoning: specifying assumptions, building meaningful baselines, debugging under shift and partial observability, and justifying accuracy–reliability–cost tradeoffs.
My UMass evaluations reflect strong execution and clarity (**recent instructor effectiveness 4.7/5.0**, with **5.0/5.0** on preparation and use of class time in a recent offering). 

### Students, collaborators, and funding
I am building research around shared interfaces that make systems dependable in practice: **reliability contracts, telemetry/monitoring, and trace-based evaluation suites** spanning Networking/IoT, embedded/SoC, and autonomy.  
I currently mentor PhD and undergraduate researchers and regularly collaborate across ML systems and wireless/autonomy. 

**I welcome collaborations in foundations of machine learning, learning under dependence, graph learning, generative modeling theory, and efficient inference for large models.**
