---
layout: page
permalink: /cfp/
title: Call for Papers
description: Author instructions for FoRLM 2025
nav: true
nav_order: 2
---

**We welcome contributions that advance the scientific foundations of reasoning in language models**, such as by:
- Deeper conceptual understanding through scientific experimentation and theoretical analysis (including negative results)
- Developing formal frameworks that model reasoning
- Creating well-defined, interpretable testbeds for evaluating reasoning behavior
- Designing principled algorithmic interventions, and evaluating them rigorously

<span style="color:red">**Submission deadline:** Wednesday, September 3, 2025</span>

**Submission instructions (TLDR):** Submissions may have at most 9 content pages (within that range, all lengths are welcome), excluding references and supplementary material.
Papers will be submitted to <a href="https://openreview.net/">(TBD) this OpenReview portal</a>.
Works that have been published at archival venues, including NeurIPS 2025, will be removed from consideration.


#### Topics of Interest

Topics (each with a short list of examples) include, but are not limited to:

1. **Models of Reasoning**
<br>
*Frameworks, theories, and analysis of reasoning phenomena, problems, and solution methods*
  - Novel paradigms for generalization (e.g., compositional, length, diversity, multi-task)
  - Behaviors such as backtracking, "aha moments," increasing length of reasoning trace
  - Abstractions of reasoning problems, e.g., formal theorem proving as graph problems
  - Characterizing effective inductive biases (e.g., pivotal tokens)

2. **Principled Algorithmic Interventions**
<br>
*Methods targeting core reasoning challenges, grounded in theoretical and empirical insights*
  - Innovations in pre-training, post-training, reinforcement learning algorithms
  - Incorporating or learning different forms of feedback --- verifiers, rewards, process rewards
  - Exploration
  - (Automated) Design and collection of demonstrations and reasoning traces

3. **Diagnostics and Evaluations:**
<br>
*Dedicated benchmarks, metrics, and scientific methods that isolate and probe reasoning behaviors*
  - Tasks, metrics, and datasets, especially interpretable ones, that target behaviors or challenges in reasoning
  - Tasks that simulate components of language model development "at scale," such as pre-training
  - Scientific evaluation of reasoning models and algorithms
  - Mechanistic interpreatbility and understanding

4. **Representational and Architectural Questions in Reasoning:** How model architectures, internal representations, and generation methods enable or limit reasoning abilities
  - Representation learning, feature acquisition, compositional generalization in reasoning
  - The effect of depth, dimension, and chain-of-thought on transformer capabilities for reasoning problems (e.g., search in proof trees)
  - Alternative architectures like state-space models, text diffusion models, deep equilibrium models


5. **Training Paradigms and the Emergence of Reasoning** How parts of the LM development pipeline---pre-training, supervised finetuning, reinforcement learning, test-time methods, even data---interact to elicit reasoning capabilities.
  - The relationship between pre-training and post-training
  - Examining the effect of different posttraining methods (e.g., expert iteration, RL, SFT) on improving or distorting reasoning behaviors during finetuning
  - How to integrate test-time methods (or which to integrate) in order to best support post-trained models
  - Curriculum and continual learning
  - Self-improvement and self-verification

#### Important dates

- **Submission deadline:** Wednesday, September 3, 2025, AoE
- **Author notification:** Monday, September 22, 2025, AoE
- **Workshop date:** Saturday, December 6, 2025


#### Submission Instructions

**Format:** Submitted papers may have at most 9 content pages, excluding references and supplementary material.
Within those constraints, all page lengths are welcome.
Previously published papers, including those at NeurIPS 2025, will not be permitted (see "Dual Submission Policy" below).

**Style files:** Submissions must use the <a href="https://media.neurips.cc/Conferences/NeurIPS2025/Styles.zip"> NeurIPS 2025 style files </a>.

**Submitting your paper:** Please upload your submission as a single PDF to <a href="https://openreview.net/">(TBD) this OpenReview portal</a>. 

**Anonymization:** Reviews will be double-blind. Please ensure that submissions do not contain author names (should be handled automatically by the NeurIPS style files) or other identifying information.

#### Dual Submission Policy

We do not permit submissions that have been published at archival venues, including NeurIPS 2025.
This ensures that ForLM 2025 best facilitates the presentation and discussion of fresh contributions best suited to the workshop's format.

This policy is in accordance with the
<a href="https://neurips.cc/Conferences/2025/CallForWorkshopsGuidance">NeurIPS 2025 workshop guidances</a>, which state that "workshops are not a venue for work that has been previously published in other conferences on machine learning or related fields. Work that is presented at the main NeurIPS conference should not appear in a workshop, including as part of an invited talk."

