---
layout: page
title: Programmable Accelerator Architecture
description: GPU kernel, scheduler, and prefetcher optimization with C++ and CUDA.
img:
importance: 1
category: design
related_publications: false
---

This design project optimized programmable accelerator execution for CNN workloads and many-thread GPU behavior.

Highlights include CUDA kernels for convolution and GEMM, optimized image filtering and pooling pipelines, CTA-level schedulers that improved IPC and reduced L1/L2 cache miss rates, and a many-thread-aware prefetcher validated with a CUDA micro-benchmark.
