---
layout: page
permalink: /schedule/
title: Schedule
description: 
nav: true
nav_order: 2
---

<br>

<div>
<table class="table table-hover" id="standings" style="border-collapse:collapse">
<thead>
<tr class="header" style="background-color:rgb(215, 215, 215); border-top: 1pt solid white; border-bottom: 1pt solid black;">
        <th style="border-top-left-radius: 10px; width: 15%">Time</th>
        <!-- <th>Virtual link</th> -->
        <th style="width: 15%">Type</th>
        <th style="width: 70%; border-top-right-radius: 10px;">Title & Speakers</th>
        <!-- <th style="width: 25% border-top-right-radius: 10px;">Speakers (Affiliations)</th> -->
      </tr>
</thead>
<tbody>
  <tr style="cursor: pointer">
    <td>8:50 - 9:00</td>
    <td>
    Opening Remarks
    <!-- <br>
    [video] -->
    </td>
    <td>
    Organizers
    </td>
  </tr>
  <!-- <tr>
    <td></td>
    <td></td>
    <td>
      TBD
    </td>
  </tr> -->
              
  <tr style="cursor: pointer">
    <td>9:00 - 9:45</td>
    <td>
    Invited Talk
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022177">video</a>] -->
    </td>
    <td>
            <i>Test-Time Scaling, A Foundation for AI Self-Improvement</i>
            <br>
            <b>Azalia Mirhoseini</b> (Stanford University)
            <br><br>
            Pre-training scaling laws have driven much of the progress in AI over the past few years. In this talk, we present test-time compute as a new frontier for AI scaling and self-improvement. We have entered an era where models themselves are powerful sources of intelligence that can indefinitely synthesize new experiences and strategies through thinking, reasoning, and interacting with external environments and tools. Two important enablers of model self-improvement are test-time compute scaling and training on experiences generated at test time. Building on these, we will discuss our recent work on AI self-improvement, including KernelBench, Weaver, SWiRL, and Cartridges, demonstrating why test-time scaling for reasoning represents a significant and largely untapped frontier for general artificial intelligence.
    </td>
  </tr>

  <tr style="cursor: pointer">
    <td>9:45 - 10:00</td>
    <td>
    Contributed Talk 1
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022178">video</a>] -->
    </td>
    <td>
            <i>Reasoning Through Chess: How Reasoning Evolves from Data Through Fine-Tuning and Reinforcement Learning</i>
            <br>
            <b>Lucas Dionisopoulos</b>, Prithviraj Ammanabrolu, Nicklas Majamaki
            <!-- <br><br>
            Imitation learning (IL) aims to mimic the behavior of an expert in a sequential decision making task by learning from demonstrations, and has been widely applied to robotics, autonomous driving, and autoregressive language generation. The simplest approach to IL, behavior cloning (BC), is thought to incur sample complexity with unfavorable quadratic dependence on the problem horizon, motivating a variety of different online algorithms that attain improved linear horizon dependence under stronger assumptions on the data and the learner’s access to the expert. -->
<!-- <br>
            In this talk, we revisit the apparent gap between offline and online IL from a learning-theoretic perspective, with a focus on general policy classes up to and including deep neural networks. Through a new analysis of behavior cloning with the logarithmic loss, we will show that it is possible to achieve horizon-independent sample complexity in offline IL whenever (i) the range of the cumulative payoffs is controlled, and (ii) an appropriate notion of supervised learning complexity for the policy class is controlled. When specialized to stationary policies, this implies that the gap between offline and online IL is not fundamental. We will then discuss implications of this result and investigate the extent to which it bears out empirically. -->
    </td>
  </tr>

  <tr style="cursor: pointer">
    <td>10:00 - 10:15</td>
    <td>
    Contributed Talk 2
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022178">video</a>] -->
    </td>
    <td>
            <i>GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning </i>
            <br>
            <b>Lakshya A Agrawal</b>, Shangyin Tan, Dilara Soylu, Noah Ziems, et al.
            <!-- <br><br>
            Imitation learning (IL) aims to mimic the behavior of an expert in a sequential decision making task by learning from demonstrations, and has been widely applied to robotics, autonomous driving, and autoregressive language generation. The simplest approach to IL, behavior cloning (BC), is thought to incur sample complexity with unfavorable quadratic dependence on the problem horizon, motivating a variety of different online algorithms that attain improved linear horizon dependence under stronger assumptions on the data and the learner’s access to the expert. -->
<!-- <br>
            In this talk, we revisit the apparent gap between offline and online IL from a learning-theoretic perspective, with a focus on general policy classes up to and including deep neural networks. Through a new analysis of behavior cloning with the logarithmic loss, we will show that it is possible to achieve horizon-independent sample complexity in offline IL whenever (i) the range of the cumulative payoffs is controlled, and (ii) an appropriate notion of supervised learning complexity for the policy class is controlled. When specialized to stationary policies, this implies that the gap between offline and online IL is not fundamental. We will then discuss implications of this result and investigate the extent to which it bears out empirically. -->
    </td>
  </tr>
  <!-- <tr>
    <td></td>
    <td></td>
    <td>
      
  </td>
  </tr> -->

  <tr>
        <td>10:15 - 11:30</td>
        <td></td>
        <td><b>Poster Session 1</b></td>
  </tr>

  <tr style="cursor: pointer">
    <td>11:30 - 12:15</td>
    <td>
    Invited Talk
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022179">video</a>] -->
    </td>
    <td>
            <i>Exploration, Extrapolation and Chains of Thought</i>
            <br>
            <b>Aviral Kumar</b> (Carnegie Mellon University)
            <br><br>
            In this talk, I will talk about the central question of exploration in LLM reasoning. I will talk about two notions of exploration: at train time, and at test time. Train time exploration enables us to solve challenging questions where sampling from the base exploration itself is not enough by steering chains of thought towards useful parts of the search space. On the other hand, test-time exploration enables us to implement useful algorithmic strategies in chain-of-thoughts that improve extrapolation and scaling of compute at test time. Taken together, these two axes help us make better use of computation for scaling LLM reasoning.
    </td>
  </tr>
  <!-- <tr>
    <td></td>
    <td></td>
    <td>
      
  </td>
  </tr> -->

  <tr>
        <td>12:15 - 13:45</td>
        <td></td>
        <td>Lunch break</td>
  </tr>

  <tr style="cursor: pointer">
    <td>13:45 - 14:30</td>
    <td>
    Invited Talk
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022179">video</a>] -->
    </td>
    <td>
            <i>Olmo 3 Think: Training a Fully Open Reasoning Model</i>
            <br>
            <b>Nathan Lambert</b> (Allen Institute for AI)
            <br><br>
            This talk covers the crucial details it takes to train 7B to 32B parameter, fully open reasoning models, Olmo-3-Think, to rival Qwen 3, highlighting fresh results, trade-offs, and methods across midtraining, distillation with high-quality thinking SFT data, and reinforcement learning with verifiable rewards. This talk focuses on aspects of the training process, such as model architecture decisions, data sourcing, and training code design that is often not shared by leading models and can enable a resurgence of research with advancements in reinforcement learning, tool-use, and inference-time scaling. The goal of these models, such as through our release of various case-studies in RL-Zero checkpoints, is to seed trusted and innovative reasoning and tool-use research.
    </td>
  </tr>
  <!-- <tr>
    <td></td>
    <td></td>
    <td>
      
  </td>
  </tr> -->

  <tr style="cursor: pointer">
    <td>14:30 - 14:45</td>
    <td>
    Contributed Talk 3
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022178">video</a>] -->
    </td>
    <td>
            <i>OpenThoughts: Data Recipes for Reasoning Models</i>
            <br>
            Etash Kumar Guha, Ryan Marten, Sedrick Keh, Negin Raoof, Georgios Smyrnis, et al.
    </td>
  </tr>

  <tr style="cursor: pointer">
    <td>14:45 - 15:00</td>
    <td>
    Contributed Talk 4
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022178">video</a>] -->
    </td>
    <td>
            <i>Learning Composable Chains-of-Thought</i> <br>
            <b>Fangcong Yin</b>, Zeyu Leo Liu, Liu Leqi, Xi Ye, Greg Durrett
    </td>
  </tr>
  <!-- <tr>
    <td></td>
    <td></td>
    <td>
      
  </td>
  </tr> -->

  <tr>
        <td>15:00 - 16:15</td>
        <td></td>
        <td><b>Poster Session 1</b></td>
  </tr>

  <tr style="cursor: pointer">
    <td>16:15 - 17:00</td>
    <td>
    Invited Talk
    <!-- <br>
    [<a>slides</a>] [<a href="https://slideslive.com/39022179">video</a>] -->
    </td>
    <td>
            <i>Understanding Architectural Constraints on LLM Reasoning Abilities</i>
            <br>
            <b>Michael Hahn</b> (Saarland University)
            <br><br>
            The reasoning capabilities of LLMs have seen enormous progress, but it remains hard to predict when they fail, and how many reasoning tokens they need to solve different problems. I will present two lines of research aiming to make reasoning abilities more predictable via theoretical bounds on the abilities of the underlying architecture — the Transformer. First, I will present our recent work aiming to predict on which algorithmic tasks transformers can generalize to longer inputs, and compare to LLM performance. Second, I will describe our recent work bounding the reasoning cost needed to solve various algorithmic problems with transformers. I will close by discussing problems for further research.
    </td>
  </tr>




  <tr>
        <td>17:00 - 17:15</td>
        <td></td>
        <td>Closing Remarks</td>
  </tr>
</tbody>
</table>
</div>