---
layout: page
title: Vision-Language-Action Models
permalink: /research/vla/
description: Verification and progress monitoring for VLA-based robot policies.
nav: false
---

## Overview

Vision-Language-Action (VLA) models enable robots to follow natural language instructions by grounding language in visual observations and producing actions. But how do we know when these policies are failing?

My research develops **verification frameworks** that monitor task progress and detect failure modes in real-time.

---

## Current Projects

### Progress-Monitored Verification for VLA Models

**Status:** Ongoing research at UC Irvine

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> External verifiers can estimate task progress and re-rank VLA action outputs under ambiguity.
</div>

**What we're building:**
- Verifier-augmented framework to estimate task progress during execution
- Failure mode detection for VLA-based robot policies
- Modular evaluation pipeline across simulated manipulation tasks

**Why it matters:**
VLA models can fail silently — producing confident but incorrect actions. Progress monitoring enables early intervention before cascading failures.

---

### Human Natural Language to Robotic Control

**Status:** Completed at Caltech (2022-2024) | Advisor: Prof. John Doyle

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> LLMs + Model Predictive Control can bridge natural language and low-level robot control.
</div>

**What we built:**
- Human-robot collaboration framework for natural language to robotic control
- Integration of LLM task planning with MPC trajectory optimization
- Visual-language model feedback loop for improved robot performance

---

## Research Questions I'm Exploring

1. **Compositional verification** — Can we verify complex tasks by composing simpler sub-task verifiers?
2. **Learning from failures** — How can VLA models improve from detected failure modes?
3. **Sim-to-real transfer** — Do verification methods trained in simulation transfer to real robots?

---

<div class="back-link">
  <a href="{{ '/' | relative_url }}">← Back to home</a>
</div>
