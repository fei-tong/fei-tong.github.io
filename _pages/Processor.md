---
layout: archive
title: "开源高性能处理器及SoC架构"
permalink: /Processor/
author_profile: true
---

## ETH-PULP

### 标量处理器(Scalar)：[Ariane(CVA6)](https://github.com/openhwgroup/cva6) ![语言](https://img.shields.io/badge/语言-systemverilog_(IEEE1800_2005)-CAD09D.svg) 

* [Ariane(CVA6) Guide](https://cva6.readthedocs.io/en/latest/03_cva6_design/index.html)

<img src='/images/ariane_overview.png'>


### 向量处理器(Vector)：[Ara](https://github.com/pulp-platform/ara) ![语言](https://img.shields.io/badge/语言-systemverilog_(IEEE1800_2005)-CAD09D.svg) 

<img src='/images/ara.png'>


### 相关论文

[Ariane(CVA6)](https://arxiv.org/pdf/1904.05442.pdf)<br>
[CVA6 RISC-V Virtualization](https://arxiv.org/pdf/2302.02969.pdf)<br>
[Ara](https://arxiv.org/pdf/1906.00478.pdf)


## BAR-Chipyard

### 标量处理器(Scalar)：[Rocket-core](https://github.com/chipsalliance/rocket-chip) ![语言](https://img.shields.io/badge/语言-Chisel-FF1010.svg)

### 乱序超标量处理器(SuperScalar OoO)：[SonicBOOM(BOOMv3)](https://github.com/riscv-boom/riscv-boom) ![语言](https://img.shields.io/badge/语言-Chisel-FF1010.svg)

* [BOOM Guide](https://docs.boom-core.org/en/latest/)

<img src='/images/boom-pipeline-detailed.webp' width='70%'>

### 向量处理器(Vector)：[Hwacha](https://github.com/ucb-bar/hwacha) ![语言](https://img.shields.io/badge/语言-Chisel-FF1010.svg)

* [Hwacha ISA-Architecture](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2015/EECS-2015-262.pdf)
* [Hwacha Microarchitecture](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2015/EECS-2015-263.pdf)

<img src='/images/hwacha-rocc.png' width='24%'>
<img src='/images/hwacha.png' width='75%'><br>
<img src='/images/VXU.png' width='49%'>
<img src='/images/VMU.png' width='49%'>

### 矩阵处理器(Matrix)：[Gemmini](https://github.com/ucb-bar/gemmini) ![语言](https://img.shields.io/badge/语言-Chisel-FF1010.svg)

*  [Gemini Guide](https://github.com/ucb-bar/gemmini/blob/master/README.md)

<img src='/images/gemmini-system.png' width='40%'>
<img src='/images/gemmini-systolic-array.png' width='59%'>


## Interconnect Bus
* [$\text{ARM}^© \text{AMBA}$](https://developer.arm.com/Architectures/AMBA)

<img src='/images/AMBA.png'>