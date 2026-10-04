---
layout: page
title: LLM Reasoning & Alignment
permalink: /research/llm/
description: Preference learning, personalization, and long-horizon reasoning in large language models.
nav: false
---

## Overview

How can an LLM understand what a user wants when their preferences are incomplete, noisy, or scattered across conversations?

My research explores **personality as a latent signal behind user preferences**, using it to guide personalized responses and generalize to unseen choices.

---

## Featured Research

### PACIFIC: Personality-Driven Preference Alignment in LLMs

**Status:** Research at UC Irvine | Co-first author

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> Personality traits can help organize preference evidence and identify which context is useful for personalized decisions.
</div>

**What we're building:**

- **PACIFIC benchmark:** 1,200 synthetic preference–query pairs across 20 domains, annotated with Big Five personality traits.

- **Persona-aware retrieval:** A contrastively fine-tuned dual-encoder retriever that selects personality-consistent preferences for LLM responses.

- **Controlled evaluations:** Experiments examining trait alignment, noisy context, and personality guidance.

**Key result:**
On PACIFIC, Gemma-3-4B-IT achieved 76% answer-choice accuracy with trait-aligned, personality-labeled preferences, compared with 29.25% using mixed-trait preferences

**Why it matters:**
Personalization depends on retrieving useful evidence and applying it appropriately. This work connects **user modeling, representation learning, and retrieval-augmented generation.**

---

## Future Research Directions

1. **Preference generalization** — How can past interactions inform recommendations in unfamiliar domains?
2. **Robust user modeling** — How should models handle uncertain or contradictory preference evidence?
3. **Adaptive personalization** — How can user representations evolve as preferences change?

---

## Paper & Resources

- [Read the PACIFIC paper](https://arxiv.org/abs/2602.07181)
- [Explore the dataset](https://huggingface.co/datasets/TylerZ0931/PACIFIC-big-five-trait-preferences)

---

<div class="back-link">
  <a href="{{ '/' | relative_url }}">← Back to home</a>
</div>
