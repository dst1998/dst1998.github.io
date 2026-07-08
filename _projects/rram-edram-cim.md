---
layout: page
title: RRAM-eDRAM Compute-in-Memory
description: Floating-point CIM engine with fusion macros and 3D-MAC dataflow.
img:
importance: 2
category: research
related_publications: true
---

This project develops a floating-point compute-in-memory engine with RRAM-eDRAM fusion macros and a multiply-accumulate-compute dataflow for edge AI acceleration.

The design eliminates alignment-induced accuracy loss, reduces area overhead, and improves throughput through a pipelined accumulator, power-aware synthesis with a multi-Vt library, decoupled gain-cell eDRAM read/write ports, and interleaved access across RRAM/eDRAM macros.

The engine achieved 38.5 TFLOPS/W energy efficiency at 600 MHz, 1.75% accuracy degradation with Tiny-ViT on CIFAR-10, and up to 4.84x/8.48x figure-of-merit gains over prior SRAM/RRAM baselines.
