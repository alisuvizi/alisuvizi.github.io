---
title: "Swift-Healer: Firmware-Reconfigurable Self-Healing for Remote Glitch-Injection on Autonomous Navigation Systems"
collection: publications
permalink: /publication/2026-swift-healer/
date: 2026-06-22
venue: "ACM Great Lakes Symposium on VLSI (GLSVLSI 2026)"
paperurl: "https://doi.org/10.1145/3787109.3815273"
citation: "Ali Suvizi, Joshua Iwu, Kostas Amberiadis, and Guru Venkataramani. Swift-Healer: Firmware-Reconfigurable Self-Healing for Remote Glitch-Injection on Autonomous Navigation Systems. Proceedings of the Great Lakes Symposium on VLSI (GLSVLSI), pp. 679–684, 2026."
excerpt: "A firmware-reconfigurable self-healing architecture implemented on a Xilinx Zynq-7000 FPGA/SoC to protect autonomous navigation systems against remote clock and voltage glitch-injection attacks."
---

Swift-Healer presents a firmware-reconfigurable self-healing architecture for improving the reliability of autonomous navigation systems under remote clock and voltage glitch-injection attacks.

The architecture combines proactive fault prediction, reactive detection, and firmware-controlled recovery. It was implemented and evaluated on a **Xilinx Zynq-7000 FPGA/SoC**, integrating a pipelined Sobel accelerator, ARM firmware, and hardware reconfiguration.

**Key Results:**

- **Fault prediction:** F1-score of 0.87, predicting glitches up to two control cycles ahead.
- **Accelerator performance:** 0.03 ms per frame for 128 × 128 image processing.
- **Hardware recovery:** 0.005–5 ms, depending on the recovery mechanism.
- **Recovered accuracy:** Approximately 0.96 F1-score for edge detection.
- **Hardware platform:** Xilinx Zynq-7000 FPGA/SoC.

**Authors:** Ali Suvizi, Joshua Iwu, Kostas Amberiadis, and Guru Venkataramani.

**Publication:** ACM Great Lakes Symposium on VLSI (GLSVLSI), 2026.

[Read the published paper](https://doi.org/10.1145/3787109.3815273)
