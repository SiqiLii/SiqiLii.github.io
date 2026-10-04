---
layout: page
title: Vision-Language-Action Models
permalink: /research/vla/
description: Verification and progress monitoring for VLA-based robot policies.
nav: false
---

## Overview

Vision-Language-Action (VLA) models connect visual perception and language understanding to robotic actions. But dynamic manipulation requires more than knowing where to move—robots must also control **how fast to move and when to act**.

My research develops **velocity-aware VLA models** for tasks such as tossing, sliding, pushing, and catching objects. I combine model architecture design, theoretical analysis, and real-robot implementation to improve performance on tasks where motion and timing determine success.


---

## Current Projects

### Velocity-Aware VLA Models for Dynamic Manipulation

**Status:** Research at UC Irvine | Advisor: Prof. Yasser Shoukry, Prof. Unnat Jain

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> Explicit, synchronized prediction of joint positions and velocities gives robots richer motion targets for dynamic manipulation.
</div>

**What we're building:**

- Dual-expert architecture: Augment a VLA backbone with a dedicated velocity expert to jointly predict robot joint positions and velocities
- Aligned action generation: Couple position and velocity generation through a shared noisy interpolant to encourage temporally consistent predictions
- Robot execution pipeline: Integrate predicted positions and velocities with low-level control for dynamic task execution
- Simulation and real-world evaluation: Test on tasks including bottle tossing, cube sliding, bread flipping, ball pushing, bottle handover, and catching a dropped ball

**Theoretical foundations:**
We study why discrete position targets alone can underspecify dynamic motion, how differentiating approximate position trajectories can amplify velocity errors, and the conditions under which coupled position–velocity prediction supports temporal alignment.

**Why it matters:**
In dynamic manipulation, reaching the right position is only part of the problem. A push that is too fast can send an object past its target; one that is too slow may never get it there. Explicit velocity prediction helps VLA policies specify the motion needed to complete these tasks.

---

### Human Natural Language to Robotic Control

**Status:** Completed at Caltech (2022-2024) | Advisor: Prof. John Doyle

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> Combining LLM task planning with Model Predictive Control connects natural language instructions to executable robot motion.
</div>

**What we built:**

- Human-robot collaboration framework for natural language to robotic control
- Integration of LLM task planning with MPC trajectory optimization
- Visual-language model feedback loop for improved robot performance

**Connection to my current research:**
This work shaped my interest in connecting high-level reasoning with low-level physical execution—a challenge I now address through velocity-aware VLA models.



---

<div class="back-link">
  <a href="{{ '/' | relative_url }}">← Back to home</a>
</div>
