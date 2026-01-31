---
layout: page
title: Adversarial Robustness
permalink: /research/adversarial/
description: Building AI systems that are robust to adversarial attacks and distribution shifts.
nav: false
---

## Overview

Modern vision-language models achieve remarkable performance on standard benchmarks, but remain vulnerable to adversarial perturbations and distribution shifts. My research develops **provably-guaranteed detection methods** and robust training procedures.

---

## Current Projects

### KoALA: KL-L0 Adversarial Detector via Label Agreement

**Status:** Under review at ICLR 2026 | [arXiv](https://arxiv.org/abs/2510.12752)

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> Combining KL divergence with L0-based label agreement enables formal detection guarantees.
</div>

**What we did:**
- Designed a dual-head detector that flags inputs when prediction heads disagree
- Established formal detection guarantees with rigorous mathematical proofs
- Validated on ResNet-18 and CLIP (ViT-B/32) across standard adversarial benchmarks

**Why it matters:**
Most adversarial detection methods lack formal guarantees — they work empirically but can be bypassed by adaptive attacks. KoALA provides provable bounds on detection performance.

---

## Research Questions I'm Exploring

1. **Certified robustness for VLMs** — Can we extend randomized smoothing to vision-language models?
2. **Distribution shift detection** — How do we distinguish adversarial inputs from natural distribution shifts?
3. **Robust fine-tuning** — Does adversarial training transfer across modalities?

---

## Related Publications

{% bibliography --query @*[keywords~=adversarial] %}

---

<div class="back-link">
  <a href="{{ '/' | relative_url }}">← Back to home</a>
</div>
