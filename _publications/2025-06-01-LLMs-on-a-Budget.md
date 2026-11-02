---
title: "LLMs on a Budget: System-Level Approaches to Power-Efficient and Scalable Fine-Tuning"
collection: publications
permalink: /publication/2025-llms-on-a-budget/
date: 2025-06-01
venue: "IEEE Open Journal of the Computer Society, volume 6 (2025)"
paperurl: "https://doi.org/10.1109/OJCS.2025.3580498"
citation: "Kailash Gogineni, Ali Suvizi, and Guru Venkataramani. LLMs on a Budget: System-Level Approaches to Power-Efficient and Scalable Fine-Tuning. IEEE Open Journal of the Computer Society, vol. 6, pp. 987-1000, 2025."
excerpt: "A system-level study of memory efficiency, performance, and GPU power-management tradeoffs when fine-tuning large language models on a single GPU."
---

This study investigates system-level techniques for more efficient **large language model (LLM) fine-tuning** on resource-constrained GPU platforms.

### Key Contributions

- Analyzed techniques including **LoRA**, mixed-precision computation, activation checkpointing, and offloading.
- Studied fine-tuning performance and resource requirements for LLaMA-3.1, Phi-3, and Gemma models using an NVIDIA RTX 4090.
- Reported **more than 40% reduction in memory usage** in evaluated configurations.
- Evaluated GPU power capping; changing the configured cap from **450 W to 300 W** resulted in approximately **5.55% average throughput reduction** in the reported study.

**Authors:** Kailash Gogineni, Ali Suvizi, and Guru Venkataramani.

**Publication:** IEEE Open Journal of the Computer Society, vol. 6, pp. 987-1000, 2025.

[Read the published article](https://doi.org/10.1109/OJCS.2025.3580498)
