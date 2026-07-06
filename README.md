<div align="center">

# Jia Liu

**Engineer & Researcher | Engineering AI for Infrastructure Systems**

Infrastructure Monitoring &middot; Additive Manufacturing Quality Assessment &middot; Mechanics-informed AI &middot; Decision Optimization

<p>
  <img src="https://img.shields.io/badge/Engineering%20AI-research-2F5D7C?style=flat-square" alt="Engineering AI" />
  <img src="https://img.shields.io/badge/Infrastructure%20Systems-monitoring-4B6F8A?style=flat-square" alt="Infrastructure Systems" />
  <img src="https://img.shields.io/badge/Additive%20Manufacturing-quality%20assessment-5F7F65?style=flat-square" alt="Additive Manufacturing" />
  <img src="https://img.shields.io/badge/Decision%20Optimization-SMDP-7A6A3A?style=flat-square" alt="Decision Optimization" />
  <img src="https://img.shields.io/badge/Python-data%20analysis-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/MATLAB-engineering%20modeling-6B7280?style=flat-square" alt="MATLAB" />
</p>

</div>

---

## Research Identity

I work on **engineering AI for infrastructure systems**, with a focus on
connecting monitoring, inspection, and sensing data to reliable engineering
decisions. My interests sit at the intersection of civil infrastructure,
bridge engineering, additive manufacturing quality assessment,
mechanics-informed modeling, and maintenance decision optimization.

The central question behind my work is how engineered systems can move from
raw observations to interpretable state assessment and practical action. I am
especially interested in workflows that combine data-driven representation,
physical reasoning, uncertainty awareness, and decision models.

## Research Pipeline

```mermaid
flowchart LR
    subgraph L1["Observation"]
        A["Sensing / Inspection Data<br/>images / inspection records / sensor data"]
    end

    subgraph L2["Representation"]
        B["Feature Representation<br/>defect indicators / degradation features"]
    end

    subgraph L3["Assessment"]
        C["Quality / State Assessment<br/>layer consistency / bridge condition"]
    end

    subgraph L4["Decision"]
        D["Decision Optimization<br/>SMDP / maintenance strategy"]
    end

    subgraph L5["Feedback"]
        E["Engineering Feedback<br/>quality control / lifecycle management"]
    end

    A --> B --> C --> D --> E
    E -. "updates monitoring, models, and strategies" .-> A

    classDef data fill:#EEF6FF,stroke:#2F5D7C,stroke-width:1.2px,color:#111827;
    classDef model fill:#F5F7F2,stroke:#5F7F65,stroke-width:1.2px,color:#111827;
    classDef decision fill:#FFF7E6,stroke:#8A6D2F,stroke-width:1.2px,color:#111827;
    classDef feedback fill:#F8FAFC,stroke:#6B7280,stroke-width:1.2px,color:#111827;

    class A,B data;
    class C model;
    class D decision;
    class E feedback;
```

This pipeline reflects a decision-oriented view of engineering AI: data are
not the endpoint, but the starting point for condition representation,
uncertainty-aware assessment, and engineering action.

## Research Ecosystem

```mermaid
flowchart TB
    Theme["Engineering AI<br/>for Infrastructure Systems"]

    subgraph Core["Core Research Projects"]
        IMDS["infrastructure-maintenance-decision-support"]
        AM["am-layer-consistency-monitoring"]
    end

    subgraph Extension["Exploratory Extensions"]
        WHSP["wearable-human-state-profiling"]
        HMSF["Human Movement-State Feedback"]
    end

    Theme ==> IMDS
    Theme ==> AM
    Theme -. "state sensing extension" .-> WHSP
    Theme -. "feedback modeling extension" .-> HMSF

    IMDS --> I1["Infrastructure deterioration modeling"]
    IMDS --> I2["Semi-Markov decision process"]
    IMDS --> I3["Maintenance strategy optimization"]

    AM --> A1["Layer-wise quality monitoring"]
    AM --> A2["Vision-based consistency evaluation"]
    AM --> A3["Interpretable quality indicators"]

    WHSP --> W1["Multimodal human-state sensing"]
    HMSF --> H1["Human Movement-State Feedback"]

    classDef theme fill:#F8FAFC,stroke:#111827,stroke-width:2px,color:#111827;
    classDef core fill:#EEF6FF,stroke:#2F5D7C,stroke-width:2px,color:#111827;
    classDef extension fill:#F5F7F2,stroke:#5F7F65,stroke-width:1.2px,color:#111827;
    classDef detail fill:#FFFFFF,stroke:#CBD5E1,stroke-width:1px,color:#111827;

    class Theme theme;
    class IMDS,AM core;
    class WHSP,HMSF extension;
    class I1,I2,I3,A1,A2,A3,W1,H1 detail;
```

## Core Research Directions

### Infrastructure Condition Intelligence

I study methods that convert inspection and monitoring observations into
interpretable condition indicators for bridges and infrastructure systems.
This direction emphasizes deterioration representation, uncertainty awareness,
and maintenance-relevant state assessment.

### Additive Manufacturing Quality Systems

I explore vision-based and data-driven approaches for layer-wise quality
assessment in additive manufacturing. The goal is to evaluate process
consistency from image data and develop quality indicators that support
process monitoring and engineering feedback.

### Mechanics-informed Decision Modeling

My work connects data-driven assessment with engineering mechanics and
decision models. I am particularly interested in stochastic deterioration
modeling, semi-Markov decision processes, and optimization methods that
translate state information into maintenance or control strategies.

## Featured Projects

### [infrastructure-maintenance-decision-support](https://github.com/liujiaresearcher-hash/infrastructure-maintenance-decision-support)

Decision-support modeling for infrastructure maintenance under uncertain
deterioration.

| Field | Summary |
| --- | --- |
| **Problem** | Infrastructure assets deteriorate under uncertainty, while maintenance decisions must balance condition, risk, cost, and long-term performance. |
| **Method** | Semi-Markov decision process modeling for bridge and infrastructure maintenance planning. |
| **Output** | Decision-support logic for evaluating maintenance strategies under uncertain deterioration trajectories. |
| **Research relevance** | Forms the decision-optimization core of my research narrative by linking infrastructure state modeling with maintenance strategy selection. |

### [am-layer-consistency-monitoring](https://github.com/liujiaresearcher-hash/am-layer-consistency-monitoring)

Vision-based monitoring workflow for layer-wise quality consistency in
additive manufacturing.

| Field | Summary |
| --- | --- |
| **Problem** | Layer-wise quality variation in additive manufacturing may affect final part reliability and process stability. |
| **Method** | Image-based consistency evaluation using interpretable layer-level quality indicators. |
| **Output** | A monitoring workflow for extracting visual features and assessing layer consistency. |
| **Research relevance** | Extends engineering AI from civil infrastructure to manufacturing quality assessment while preserving a data-to-assessment-to-feedback logic. |

### [wearable-human-state-profiling](https://github.com/liujiaresearcher-hash/wearable-human-state-profiling)

Exploratory sensing workflow for organizing human-state information in
engineering contexts.

| Field | Summary |
| --- | --- |
| **Problem** | Human state can influence operational performance, safety, and interaction with engineered systems. |
| **Method** | Multimodal sensing organization for human-state estimation and operational state profiling. |
| **Output** | A structured exploratory workflow for converting sensing signals into human-state indicators. |
| **Research relevance** | Broadens the state-assessment theme toward human factors by exploring how wearable sensing signals can be organized into interpretable human-state indicators. |

### [Human Movement-State Feedback](https://github.com/liujiaresearcher-hash/human-movement-state-feedback)

Pose-landmark pipeline for movement-quality indicators, ergonomic state cues,
feedback rationale, and future user-study design.

| Field | Summary |
| --- | --- |
| **Problem** | How can body-tracking data be transformed into interpretable movement-state indicators and user-facing feedback? |
| **Method** | Synthetic 2D pose landmarks; joint/segment kinematics; movement-quality indicators; ergonomic state cues; feedback rationale cards. |
| **Output** | Movement-state summaries, ergonomic cue summaries, feedback design cards, and a future user-study plan. |
| **Research relevance** | Connects pose-based movement-state indicators with embodied interaction, ergonomic-state cues, interpretable feedback mapping, and human-centred work systems. |

Boundary: synthetic 2D pose landmarks only; not a clinical rehabilitation tool, full RULA/REBA assessment, or full biomechanical model.

## Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,matlab,git,github,vscode,md,latex" alt="Python, MATLAB, Git, GitHub, VS Code, Markdown, and LaTeX" />
</p>

| Area | Skills |
| --- | --- |
| **Programming & Data** | Python, MATLAB, data analysis, scientific computing |
| **Engineering Modeling** | Structural engineering, bridge systems, finite element analysis, civil infrastructure assessment |
| **AI / Decision Modeling** | Computer vision for inspection, statistical modeling, stochastic processes, semi-Markov decision processes, maintenance decision optimization |
| **Research & Documentation** | Git, GitHub, VS Code, Markdown, LaTeX, reproducible research documentation |

## Research Vision

My research vision is to develop reliable, interpretable, and
decision-oriented engineering AI systems by integrating monitoring data,
physical knowledge, and optimization models.

Rather than treating AI as a standalone prediction tool, I aim to study how
models can support engineering reasoning: what should be measured, how system
state should be represented, how uncertainty should be handled, and how
assessment results can inform maintenance, manufacturing, or operational
decisions.

## Contact

<p>
  <a href="mailto:liujia.researcher@gmail.com">
    <img src="https://img.shields.io/badge/Email-liujia.researcher%40gmail.com-2F5D7C?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/liujiaresearcher-hash">
    <img src="https://img.shields.io/badge/GitHub-liujiaresearcher--hash-111827?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>
