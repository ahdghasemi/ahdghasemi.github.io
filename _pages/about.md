---
layout: about
title: About
permalink: /
subtitle: |
  <p class="text-success"><font size="2">
  Dependable Edge AI for Networked Autonomy <br/>
  Budget-aware inference, graph learning, and protocol-driven evaluation under shift
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


I am a Postdoctoral Research Fellow and Adjunct Faculty in Electrical & Computer Engineering at the University of Massachusetts Amherst. My research builds **dependable Edge AI systems** for **networked, resource-constrained platforms** (IoT/embedded/CPS and multi-agent autonomy), where decisions must be made under hard constraints on **latency, energy, and memory**, and where **dependence, partial observability, and distribution shift** are the default operating conditions. 

<div style="
  background: #f6f8fa;
  border: 1px solid #e5e7eb;
  border-left: 4px solid #22c55e;
  padding: 12px 14px;
  border-radius: 10px;
  margin-top: 18px;
  margin-bottom: 12px;
">
  <div style="font-size: 0.92rem; font-weight: 700; margin-bottom: 6px;">
    Research thesis (in one line)
  </div>
  <div style="font-size: 0.92rem; line-height: 1.45;">
    I build <b>dependable Edge AI</b> by making <b>reliability measurable at decision time</b> under <b>hard compute budgets</b> and <b>distribution shift</b>.
  </div>
</div>

Most ML pipelines still lean on two convenient assumptions: near-i.i.d. evaluation and unconstrained inference. In deployed edge autonomy, both assumptions break. My work designs for the real regime directly by co-designing:  
**(i)** dependence-aware reliability signals, **(ii)** computation-aware inference controllers, and **(iii)** protocol-driven validation so systems can report calibrated uncertainty and cost, defer when warranted, and avoid silent failure. 

### Active projects and proof points
- **NSF CPS AERIAL (Co-PI; Thrust 2 Lead):** I lead budget-aware learning-and-control and digital-twin validation protocols that report reliability in operational units (e.g., constraint violations and energy-per-decision) using replayable traces, targeting UAV swarm autonomy in a search-and-rescue setting. 
- **TinyGNN + Low-rank training for deployable graph inference:** I develop compact graph inference primitives that make decision-time cost controllable. A low-rank message-passing architecture achieves up to **60× model size reduction** with only ~**2%** best-case performance drop, enabling HW/SW co-design via tunable rank/precision knobs. 
- **Budgeted test-time inference for foundation models (CGES):** We co-developed **Confidence-Guided Early Stopping**, a Bayesian stopping rule that uses confidence as evidence and halts sampling when posterior mass crosses a threshold (or a hard budget binds). Across five reasoning benchmarks, CGES reduces model calls by **69.4%** while matching self-consistency accuracy.   
- **Foundations: minimax sample complexity for GNNs under dependence/topology:** I develop minimax limits that characterize when graph topology makes learning intrinsically label-inefficient, yielding diagnostics that predict when more labels help versus when gains require changing mixing geometry. 

### Future research directions
My program advances a single goal: **dependable Edge AI under dependence and hard budgets**, through three composable thrusts:
1. **Computation-aware inference controllers** (adaptive rank/precision/sampling depth with explicit accuracy–efficiency tradeoffs).   
2. **Protocol-driven validation + lightweight monitoring** (replayable stress tests, operational metrics like Joules/decision, and label-free drift monitors). {index=9}  
3. **Dependence-aware learning foundations** (evaluation and uncertainty for relational/time-varying streams; topology-aware diagnostics). 

### Teaching (and why students don’t hate it)
I teach ML, generative models, DSP, image processing, and data science foundations. My goal is to turn technical knowledge into durable engineering ability: students learn to specify requirements, build baselines, debug under shift/partial observability, and deliver reproducible artifacts that justify accuracy–reliability–cost tradeoffs. 
My UMass evaluations reflect strong execution and clarity (**overall instructor effectiveness 4.7/5.0**, with **5.0/5.0** on preparation and use of class time in a recent offering). 

### Students, collaborators, and funding
I am building research around shared interfaces that make systems dependable in practice: **reliability contracts, telemetry/monitoring, and trace-based evaluation suites** spanning Networking/IoT, embedded/SoC, and autonomy.  
I currently mentor PhD and undergraduate researchers and regularly collaborate across ML systems and wireless/autonomy. 

**If you are interested in dependable ML systems for edge autonomy, resource-aware graph learning, or budgeted inference for foundation models, feel free to reach out.**
