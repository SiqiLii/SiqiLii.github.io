---
layout: about
title: About
permalink: /
subtitle: PhD Student · <a href="https://engineering.uci.edu/dept/eecs">UC Irvine EECS</a> · VLA Models for Robotics, LLM Personalization & AI Robustness

profile:
  align: right
  image: img_siqili.jpg
  image_circular: false
  more_info: >
    <p>Engineering Hall 308</p>
    <p>Irvine, CA 92697</p>
    <p><a href="mailto:siqi.li@uci.edu">siqi.li@uci.edu</a></p>
    <p style="font-size: 0.9em; font-style: italic; color: #666;">"Used generative AI to turn myself into Link. Looks cool, but also a great reminder that AI reliability is still very much a problem."</p>

selected_papers: true
social: true

research_pillars:
  - icon: "🤖"
    label: "Vision-Language-Action Models for Robotics"
    url: "/research/vla/"
  - icon: "🧠"
    label: "LLM Personalization"
    url: "/research/llm/"
  - icon: "🛡️"
    label: "AI Robustness"
    url: "/research/adversarial/"
  - icon: "🌍"
    label: "Multilingual & Cross-Cultural AI"
    url: "/research/multilingual/"

announcements:
  enabled: true
  scrollable: true
  limit: 5
---

### Hi! I’m Siqi 👋

I work on **vision-language-action (VLA) models for robotics**, with a focus on dynamic manipulation—tasks where precise timing, velocity, and physical interaction are essential to success.

My research asks a simple but practical question:  
**how do we make VLA models work well in dynamic tasks — moving objects, changing scenes, unexpected interruptions — the kind of conditions real applications actually demand?** I aim to extend their capabilities beyond controlled benchmarks to meet the demands of real-world applications.

I combine **theoretical analysis with hands-on systems engineering**, translating research ideas into working robotic systems and evaluating them in simulation and on real hardware. My approach pairs practical solutions with principled analysis to understand why they work, where they fail, and how to improve them.

I’m a PhD student in **EECS at UC Irvine**, advised by  
[Prof. Yasser Shoukry](https://rcpsl.eng.uci.edu/yshoukry/) in the  
[Resilient Cyber-Physical Systems Lab](https://rcpsl.eng.uci.edu/).  
Previously, I was a visiting researcher at **Caltech**, working with  
[Prof. John Doyle](http://www.cds.caltech.edu/~doyle/) on language-to-robot control.

---

### LLM Personalization

Alongside robotics, I work on making **large language models fit each individual user** — and keep fitting them as the user and the model interact more and more over time.

The vision is simple: every user keeps a **local, private preference memory** on their own device — a batch of their past choices, feedback, and preference statements that stays on their end rather than in the model. At inference time the LLM **retrieves from that memory, RAG-style**, to understand who it is talking to and generate **preference-aligned** responses, without retraining and without shipping personal data to a server.

Along the way I study questions like:

- which signals in a user’s history are actually **stable and informative** (e.g., personality traits), and which are noise
- how to **retrieve the right memories** for a given query rather than simply the most similar ones
- how to **evaluate** whether a personalized response is truly aligned with the user, not just plausible

The goal is an LLM that becomes **more yours the longer you use it** — while the data that makes it yours never leaves your hands.

---

### A Bit More About Me 🌍

I work fluently in **three languages** (Mandarin, English, and German), both conversationally and academically, and I’ve lived and studied across **Asia, Europe, and the US**.

I enjoy travel, food, and building things that work — which is probably why I’m drawn to problems where theory meets reality.

I believe the most interesting AI research is:

- rigorous but not fragile
- principled but hands-on
- serious, yet a little fun

If that resonates, feel free to reach out — I’m always happy to chat.
