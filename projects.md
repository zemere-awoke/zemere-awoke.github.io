---
layout: page
title: Projects
permalink: /projects/
---


  
### Recent Projects

#### 1. LIAN（莲花）: Intelligent code security analysis [source code: [GITEE](https://gitee.com/fdu-ssr/lian), [GITHUB](https://github.com/yang-guangliang/lian)]

LIAN is a next-generation static analysis platform that enables deep semantic understanding of code across multiple programming languages, including C, LLVM IR, Java, Python, JavaScript, PHP, TypeScript, Go, Rust MIR, and ArkTS. By unifying diverse languages into a common General Intermediate Representation (GIR), LIAN supports a rich set of precision-oriented analyses:

  - control flow analysis
  - call tree reconstruction
  - Context-, field-, and flow-sensitive program state analysis
  - Precise data flow and taint tracking for vulnerability detection
  - Seamless integration with AI LLMs


#### 2. YIAN（易安）: Memory-safe language design and implementation

YIAN rethinks systems programming by guaranteeing complete memory safety, without relying on the *unsafe* escape hatches and garbage collection. Built on a novel pointer model, YIAN enforces spatial and temporal memory safety while preserving low-level control and performance. 

YIAN targets safety-critical domains such as operating systems, embedded firmware, and secure AI runtimes, where reliability cannot be compromised by errors and bugs.

#### 3. QING: High-performance AI system stack for RISC-V

QING is a full-stack hardware-aware AI computing framework co-designed with the YIAN language to enable efficient, safe, and portable AI workloads on RISC-V architectures. QING eliminates the abstraction gap between high-level AI models and heterogeneous hardware. Currently targeting RISC-V, QING's architecture is designed for extensibility. Future versions will support cross-architecture portability and emerging AI accelerators.
