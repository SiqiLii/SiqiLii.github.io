---
layout: page
title: LLM Reasoning & Alignment
permalink: /research/llm/
description: Preference learning, personalization, and long-horizon reasoning in large language models.
nav: false
---

## Overview

Large language models can follow instructions, but struggle with **long-horizon reasoning**, **preference consistency**, and **personalization**. My research develops methods to align LLMs with individual user preferences through reinforcement fine-tuning.

---

## Current Projects

### LLM Preference Following and Personalization

**Status:** Ongoing research at UC Irvine

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> Dynamic preference memory enables personalization without full model retraining.
</div>

**What we're building:**
- Personality-prediction method that infers user persona from dialogue history
- Reinforcement fine-tuning (RFT) for long-context preference following
- Dynamic preference memory module with per-turn updates and conflict resolution

**Why it matters:**
Current LLMs treat all users the same. Personalization requires understanding individual preferences, resolving conflicts, and adapting over time — all without expensive retraining.

---

## Research Questions I'm Exploring

1. **Preference stability** — How do we maintain consistent preferences across long conversations?
2. **Preference conflicts** — When user preferences contradict, how should the model arbitrate?
3. **Efficient personalization** — Can we personalize with parameter-efficient methods (LoRA, adapters)?

---

## Related Reading

- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073) — Anthropic's approach to preference learning
- [Direct Preference Optimization](https://arxiv.org/abs/2305.18290) — Simplifying RLHF
- [Self-Rewarding Language Models](https://arxiv.org/abs/2401.10020) — LLMs as their own reward models

---

<div class="back-link">
  <a href="{{ '/' | relative_url }}">← Back to home</a>
</div>
