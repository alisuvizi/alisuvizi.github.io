---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Professional Profile

I am a Ph.D. researcher in Computer Engineering at **The George Washington University (GWU)**, working under the supervision of **Prof. Guru Prasadh Venkataramani**.

My research focuses on **computer architecture, hardware-software co-design, FPGA/SoC systems, chiplet-based architectures, and heterogeneous computing**. I am particularly interested in designing computing systems that are reliable, energy-efficient, and capable of supporting emerging AI and high-performance computing workloads.

My work spans physical FPGA/SoC implementations, embedded firmware, computer architecture simulation, machine learning, and accelerator optimization. My research has appeared in ACM and IEEE venues, including ACM ICS, ACM GLSVLSI, IEEE TCAD, and IEEE Cloud Summit.

**Contact:** [Email](mailto:ali.suvizi@gwu.edu) | [Google Scholar](https://scholar.google.com/citations?user=FnYbKDAAAAAJ) | [GitHub](https://github.com/alisuvizi) | [LinkedIn](https://www.linkedin.com/in/alisuvizi/)

---

## Download My Resume

I am a Ph.D. researcher specializing in computer architecture,
hardware-software co-design, FPGA/SoC systems, chiplet-based
architectures, hardware reliability, and AI acceleration.

My resume provides an overview of my technical expertise,
research experience, projects, publications, and professional
achievements.

**[Download My Resume (PDF)](/files/Ali_Suvizi_Resume.pdf)**

For a more detailed overview of my academic background,
publications, research experience, teaching, and professional
service, please see the complete CV below.

---

## Education

### The George Washington University
**Ph.D. in Computer Engineering** | Washington, DC, USA

*August 2023 – Present (Expected December 2027)*

- Advisor: Prof. Guru Prasadh Venkataramani
- Research: Computer architecture, reliable FPGA/SoC systems, chiplet-based architectures, hardware-software co-design, and AI acceleration.
- GPA: 3.85/4

### Amirkabir University of Technology (Tehran Polytechnic)
**M.Sc. in Computer Engineering – Computer Systems Architecture** | Tehran, Iran

*2019 – 2022*

- Advisor: Prof. Morteza Saheb Zamani
- Thesis: A Parallel Computational Architecture for High-Speed Solving of Hydraulic Equations Using Cellular Automata.
- GPA: 17.30/20

### Shahed University
**B.Sc. in Computer Engineering – Hardware** | Tehran, Iran

*2014 – 2018*

- Advisor: Dr. Majid Bayat
- Thesis: Intelligent Management of Water Resources in Agriculture.
- GPA: 16.30/20

---

## Research Interests

- Computer Architecture and High-Performance Computing
- Hardware-Software Co-Design and System-Level Optimization
- FPGA/SoC Design, Embedded Systems, and Reconfigurable Computing
- Chiplet-Based Architectures and Networks-on-Chip
- Hardware Reliability, Security, and Self-Healing Systems
- AI and Machine Learning Accelerators
- Heterogeneous Digital-Photonic Computing
- Energy-Efficient Computing and Memory Systems

---

## Research Experience

### Graduate Research Assistant
**The George Washington University, Washington, DC**

*August 2023 – Present*

Advisor: Prof. Guru Prasadh Venkataramani

- Design and evaluate computer architectures and hardware-software systems for reliable, efficient, and high-performance computing.
- Develop FPGA/SoC prototypes integrating hardware accelerators, embedded firmware, and runtime recovery mechanisms.
- Investigate fault-tolerant and self-healing architectures for autonomous systems and AI workloads.
- Model and evaluate chiplet-based systems, on-chip/inter-chiplet communication, and workload scheduling.
- Develop C/C++ system-level simulation infrastructure for heterogeneous digital-photonic acceleration.
- Investigate performance, energy, and memory-efficiency tradeoffs in hardware accelerators and GPU-based AI systems.
- Contribute to collaborative research supported by NSF and ONR programs.

### Graduate Researcher
**Integrated Systems Design Automation Research Laboratory, Amirkabir University of Technology**

*2019 – 2022*

Advisor: Prof. Morteza Saheb Zamani

- Developed parallel computing architectures for solving computationally intensive numerical problems.
- Designed cellular-automata-based parallel algorithms and FPGA-oriented architectures for hydraulic analysis.
- Investigated hardware parallelism, numerical acceleration, and energy-efficient computing.
- Evaluated computational performance against established software simulation frameworks.

### Undergraduate Research
**High-Performance Computing Laboratory, Shahed University**

- Investigated process migration and resource management in distributed exascale systems.
- Contributed to the ExaMig Matrix research on selecting migration destinations in distributed computing environments.

---

## Selected Research Projects

### Swift-Healer: Firmware-Reconfigurable Self-Healing for Autonomous Navigation Systems
**ACM GLSVLSI 2026 | FPGA/SoC Hardware Implementation**

- Designed and deployed a firmware-reconfigurable self-healing system on a **Xilinx Zynq-7000 FPGA/SoC**.
- Integrated ARM-based firmware, a programmable-logic image-processing accelerator, and hardware reconfiguration.
- Developed proactive GRU-based glitch prediction, reactive fault detection, and automated recovery policies.
- Achieved **0.87 prediction F1-score**, **0.03 ms accelerator latency per frame**, and **0.005–5 ms recovery time** across healing mechanisms.
- Investigated resilience against remote clock and voltage glitch-injection attacks.

[Published Paper](https://doi.org/10.1145/3787109.3815273)

### Auto-Healer: Self-Healing Hardware for Autonomous Driving Perception
**ACM ICS 2025 | FPGA and Fault-Tolerant Architectures**

- Developed a chiplet-inspired self-healing architecture for fault-tolerant CNN-based perception systems.
- Integrated hardware redundancy, synchronization, checkpointing, and automated recovery mechanisms.
- Demonstrated mean repair times of approximately **40 ns for transient faults** and **120 ns for permanent faults** in the evaluated architecture.
- Investigated hardware reliability and real-time recovery for safety-critical autonomous applications.

[Published Paper](https://doi.org/10.1145/3721145.3725755)

### Heterogeneous Digital-Photonic Computing
**Ongoing Research | C/C++, SST, BYOD, RISC-V**

- Develop and evaluate digital-photonic accelerator architectures for AI and matrix-computation workloads.
- Extend the BYOD system-level simulator using SST and C++ to model digital control, memory movement, photonic computation, and accelerator integration.
- Study data movement, scheduling, buffering, and digital-photonic execution overheads.
- Evaluate representative neural-network workloads and investigate architectural optimization opportunities.

### Firmware Compatibility in Multi-Vendor Chiplet Systems
**Ongoing Research | Chiplet Architecture and System Reliability**

- Investigate runtime incompatibilities introduced by firmware updates in heterogeneous multi-vendor chiplet systems.
- Develop architectural concepts for runahead execution, hardware-interface contract checking, and safe firmware activation.
- Study transaction ordering, protocol behavior, timing, ownership, and system-level recovery.
- Explore approaches for preventing firmware-induced failures and reducing recovery downtime.

### Chiplet-Based Scheduling and Information Freshness
**IEEE Cloud Summit 2026 | Best Paper Award**

- Investigated scheduling policies for chiplet-based hardware under real-time workload constraints.
- Studied the tradeoffs between Age of Information (AoI), task latency, and deadline compliance.
- Developed and evaluated an adaptive scheduling approach for chiplet-based computing systems.
- Examined performance effects of Network-on-Interposer communication latency.

### Processing-in-Memory and FPGA Acceleration for Edge AI
**IEEE Cloud Summit 2024**

- Evaluated Processing-in-Memory (PIM) and FPGA platforms for latency-sensitive DNN inference.
- Analyzed inference latency, energy consumption, and data freshness in edge-server applications.
- Reported up to **92x speedup** for the evaluated simulated PIM configuration and **0.02 ms inference latency** for an FPGA configuration.

[Published Paper](https://doi.org/10.1109/Cloud-Summit61220.2024.00007)

### Energy-Efficient LLM Fine-Tuning
**IEEE Open Journal of the Computer Society, 2025**

- Investigated scalable and power-efficient LLM fine-tuning on a single GPU.
- Evaluated low-rank adaptation (LoRA), reduced-precision computation, memory management, and GPU power capping.
- Analyzed memory usage, throughput, and performance-energy tradeoffs using modern language models.

[Published Article](https://doi.org/10.1109/OJCS.2025.3580498)

---

## Publications

For the complete publication list and paper details, see my [Publications page](/publications/) or [Google Scholar](https://scholar.google.com/citations?user=FnYbKDAAAAAJ).

### Conference Papers

1. **Ali Suvizi**, Joshua Iwu, Kostas Amberiadis, and Guru Venkataramani. "[Swift-Healer: Firmware-Reconfigurable Self-Healing for Remote Glitch-Injection on Autonomous Navigation Systems](https://doi.org/10.1145/3787109.3815273)." *ACM Great Lakes Symposium on VLSI (GLSVLSI)*, pp. 679–684, 2026.

2. Ege Dogan, **Ali Suvizi**, Egemen Erbayat, Suresh Subramaniam, and Guru Venkataramani. "Exploring Information-Freshness v. Task-Latency Tradeoffs for Schedulers in Chiplet-based Hardware." *IEEE Cloud Summit*, pp. 104–109, 2026. **Best Paper Award**.

3. **Ali Suvizi** and Guru Venkataramani. "[Auto-Healer: Self-Healing Hardware for Perception Stage Faults in Autonomous Driving Systems](https://doi.org/10.1145/3721145.3725755)." *ACM International Conference on Supercomputing (ICS)*, pp. 1064–1078, 2025.

4. **Ali Suvizi**, Suresh Subramaniam, Tian Lan, and Guru Venkataramani. "[Exploring In-Memory Accelerators and FPGAs for Latency-Sensitive DNN Inference on Edge Servers](https://doi.org/10.1109/Cloud-Summit61220.2024.00007)." *IEEE Cloud Summit*, pp. 1–6, 2024.

### Journal Articles

1. Morteza Adelkhani, **Ali Suvizi**, Farzaneh Arzaghi, Sara Zamani, Mohammad Salehi, and Muhammad Shafique. "[LPCR: Information-Theory-Based Low-Power Code Reordering for Serial Links in Network-on-Chip](https://doi.org/10.1109/TCAD.2025.3560223)." *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*, vol. 44, no. 11, pp. 4155–4166, 2025.

2. Kailash Gogineni, **Ali Suvizi**, and Guru Venkataramani. "[LLMs on a Budget: System-Level Approaches to Power-Efficient and Scalable Fine-Tuning](https://doi.org/10.1109/OJCS.2025.3580498)." *IEEE Open Journal of the Computer Society*, vol. 6, pp. 987–1000, 2025.

3. **Ali Suvizi**, Ruhollah Ahmadi, Morteza Saheb Zamani, and Mohammad Reza Meybodi. "[A Parallel Computational Approach for Energy-Efficient Hydraulic Analysis of Water Distribution Networks Using Learning Automata](https://doi.org/10.1016/j.suscom.2025.101135)." *Sustainable Computing: Informatics and Systems*, vol. 46, article 101135, 2025.

4. Shakiba Rezaie, Ehsan Mousavi Khaneghah, Mario Francesco Pavone, Mahdi Hajirajabi, Reza Safari, **Ali Suvizi**, and Amirhosein Reyhani ShowkatAbad. "[OutExaRD: Enhancing Resource Discovery for Support Dynamic and Interactive Events on Out-of-Distributed Exascale Systems](https://doi.org/10.1007/s44227-025-00059-y)." *International Journal of Networked and Distributed Computing*, vol. 13, article 18, 2025.

5. **Ali Suvizi**, Azim Farghadan, and Morteza Saheb Zamani. "[A Parallel Computing Architecture Based on Cellular Automata for Hydraulic Analysis of Water Distribution Networks](https://doi.org/10.1016/j.jpdc.2023.03.009)." *Journal of Parallel and Distributed Computing*, vol. 178, pp. 11–28, 2023.

6. Ehsan Mousavi Khaneghah et al., including **Ali Suvizi** (published as Ali Soveizi). "[ExaMig Matrix: Process Migration based on Matrix Definition of Selecting Destination in Distributed Exascale Environments](https://doi.org/10.32010/26166127.2018.1.1.20.41)." *Azerbaijan Journal of High Performance Computing*, vol. 1, no. 1, pp. 20–41, 2018.

### Preprints and Submitted Manuscripts

1. Arsalan Ali Malik, **Ali Suvizi**, Guru Venkataramani, and Aydin Aysu. "[Emulated Integrity Replica: Enabling Self-Healing on FPGA SoCs via Hierarchical Twins](https://arxiv.org/abs/2607.12298)." *arXiv:2607.12298*, 2026. **Submitted to IEEE Transactions on Dependable and Secure Computing (TDSC); under review.**

---

## Honors and Awards

- **Best Paper Award**, IEEE Cloud Summit, 2026.
- **University Fellowship**, The George Washington University.
- Research conference travel support and academic recognition.

---

## Teaching Experience

### Amirkabir University of Technology

**Teaching Assistant**
- Advanced Computer Architecture — supervised by Dr. Hamed Farbeh.
- Low-Power IC Design — supervised by Dr. Mahmoud Momtazpour.
- Memory Technologies — supervised by Dr. Hamed Farbeh.

**Laboratory Instruction**
- Microprocessor Laboratory — supervised by Dr. Hamed Farbeh.
- Logic Circuits Laboratory — supervised by Dr. Morteza Saheb Zamani.

Responsibilities included assisting with lectures and laboratory sessions, preparing assignments, supporting student projects, and grading coursework and examinations.

---

## Academic and Professional Service

### Peer Reviewer

Contributed peer reviews to academic journals and publications in computer engineering, computer architecture, hardware systems, and related fields, including:

- IEEE Micro
- IEEE Computer
- IEEE Computer Architecture Letters (CAL)
- IEEE Transactions on Sustainable Computing (TSUSC)
- IEEE Access
- Journal of Hardware and Systems Security
- Other peer-reviewed journals in computer engineering and related fields

Research reviewing areas include computer architecture, hardware reliability, accelerators, AI systems, security, and emerging computing technologies.

---

## Technical Skills

**Programming and Scripting**
- C, C++, Python, Bash, Java, MATLAB, and Assembly

**Hardware Design and FPGA Development**
- VHDL, Verilog, RTL design, FPGA prototyping, High-Level Synthesis (HLS), partial reconfiguration, and hardware debugging
- Xilinx Vivado, Vitis, Vivado HLS, ModelSim, and Zynq-7000 FPGA/SoC platforms
- AXI interfaces, DMA, embedded firmware, ARM, and RISC-V systems

**Computer Architecture and Simulation**
- Computer architecture modeling, chiplet-based systems, Networks-on-Chip, memory systems, and accelerator design
- gem5, Structural Simulation Toolkit (SST), BYOD, performance analysis, and architectural evaluation

**AI, Machine Learning, and Accelerators**
- PyTorch, TensorFlow, CNNs, GRUs, quantization, and model optimization
- GPU computing, Processing-in-Memory, and digital-photonic accelerator modeling

**Parallel and High-Performance Computing**
- OpenMP, CUDA, parallel algorithms, heterogeneous computing, and performance optimization

**Development and Research Tools**
- Linux, Git, GitHub, Docker, LaTeX, and Overleaf

---

## Selected Earlier Engineering Projects

- FPGA-based implementation of convolutional neural networks using VHDL.
- Quantized neural-network implementation and evaluation using Python.
- Hardware implementation of the MIPS processor, including forwarding and Tomasulo-style scheduling.
- Physical Unclonable Function (PUF)-based protection for FPGA neural-network implementations.
- Parallel matrix computation using OpenMP.
- VLSI placement optimization using quadratic and simulated annealing approaches.

---

## Research Collaboration and Opportunities

I am interested in research collaborations and industry opportunities involving **computer architecture, FPGA/SoC development, chiplet-based systems, hardware reliability, heterogeneous accelerators, and AI computing**.

For research discussions or collaboration opportunities, please contact me at [ali.suvizi@gwu.edu](mailto:ali.suvizi@gwu.edu).
