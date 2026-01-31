---
layout: page
title: Multilingual & Cross-Cultural AI
permalink: /research/multilingual/
description: Retrieval-augmented methods for rare vocabulary and cross-lingual transfer.
nav: false
---

## Overview

Multilingual AI systems often fail on **rare words**, **domain-specific terminology**, and **low-resource languages**. My research develops retrieval-augmented methods that enable models to "look things up" during inference.

---

## Current Projects

### Retrieval-Augmented Speech Translation

**Status:** Published at EMNLP 2024 | [Paper](https://aclanthology.org/2024.emnlp-main.708/)

<div class="research-area">
  <span class="area-marker">→</span>
  <strong>Key insight:</strong> Cross-modal retrieval (speech-to-speech) outperforms text-based retrieval for rare word translation.
</div>

**What we built:**

- Knowledge-based retrieval-augmented end-to-end speech translation
- Cross-modal retriever: speech-to-speech, speech-to-text, text-to-text
- Zero-shot terminology translation for open-domain recognition

**Results:**

- **17.6% improvement** in rare word accuracy with gold examples
- **8.5% improvement** with retrieved examples
- Speech-to-speech retrieval shows higher robustness to unseen speakers

**Why it matters:**
Rare words (names, technical terms, neologisms) are where translation systems fail most catastrophically. Retrieval provides a path to reliable terminology handling without massive retraining.

---

## Research Questions I'm Exploring

1. **Cross-lingual retrieval** — Can we retrieve relevant examples across language pairs?
2. **Domain adaptation** — How do retrieval-augmented methods transfer to new domains?
3. **Efficient indexing** — How do we scale retrieval to millions of examples?

---

## Related Publications

{% bibliography --query @*[keywords~=translation] %}

---

<div class="back-link">
  <a href="{{ '/' | relative_url }}">← Back to home</a>
</div>
