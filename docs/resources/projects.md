# SystemC Libraries & Projects

This page gives an overview of open-source SystemC libraries and projects.
Please [let us know][1] if a project or library is missing or needs update.

<br>
## Models

This is a list of SystemC models for use in virtual platforms:

| Name             | Description                                                                             | License                                      |
| :--------------- | :-------------------------------------------------------------------------------------- | :------------------------------------------- |
| [NVIDIA Deep Learning Accelerator (NVDLA)][2] | SystemC TLM2.0-compatible virtual platform                 | NVIDIA Open NVDLA License and Agreement v1.0 |
| [ParaNut Processor][24] | Customizable, highly scalable, and RISC-V compatible processor architecture for FPGA-based systems | BSD-2-Clause
| [Virtual Components Modeling Library (VCML) Models][3] | The VCML productivity library contains many component models (ARM, RISC-V, Virtio, ...) | Apache-2.0                                   |
| [Virtual Components Modeling Library (VCML) NVDLA Model][4]  | VCML integration of the NVDLA model                                                     | Apache-2.0                                   |
| [VPV-Peripherals][12]    | Library of example SystemC/TLM peripherals for various SoCs based on the SCC library    | Apache-2.0                                   |
| [DRAMSys][36]    | SystemC TLM-AT Model of DRAM Subsystems (DDR, LPDDR, HBM, ...)   | BSD                                   |

<br>
## Productivity and Utility Libraries

The Productivity and utility libraries contain common resources, building blocks, and utilities that can be used for creation of SystemC-based virtual platforms, supporting different use cases such as software development, Architecture exploration, and High-Level Synthesis. 

| Name                         | Description                                                                            | License                      |
|:---------------------------- | :------------------------------------------------------------------------------------- | :--------------------------- |
| [High-Level Synthesis Libs (HLSLibs)][13] | Repository for the unlimited length integer and fixed-point AC types usable with SystemC, plus math, DSP and ML building blocks, as well as SystemC MatchLib | Apache-2.0 |
| [sc-during][26] | Parallel programming on top of SystemC/TLM | LGPLv2.1 |
| [SingleSource library][31] | The SingleSource library consists of [communication channels][32] which implements functional interfaces similar to TLM 1.0. The channels support cycle accurate mode for simulation and synthesis (the implementation complies with SystemC synthesizable standard). The channels also have a fast simulation mode to be used in architecture exploration, performance evaluation and virtual prototyping. There are multiple examples of channels usage given [here](https://github.com/intel/systemc-compiler/tree/main/designs/single_source) | Apache-2.0 |
| [SystemC-Components (SCC)][5] | A light weight productivity library for SystemC and TLM 2.0 based modeling tasks using C++11 provides common functions, components and modules often needed in SystemC based models | Apache-2.0 |
| [Virtual Components Modeling Library (VCML)][6]  | Sockets, Tracing, Registers, GDB server, Logging, Session Protocol, Component Models, Network backends, TLM2.0 protocols | Apache-2.0 |
| [GUI-VP Kit][35]  | Interactive Graphical Application Development Kit, providing a quick-to-create and easy-to-use platform for experimenting with Linux on the [RISC-V VP++][34] | *Not specified* |

<br>
## Virtual Platforms and Virtual Prototypes

This is a list of open-source Virtual Platforms and Virtual Prototypes (VPs):

| Name            | Description                              | OS / Workloads                             | License      |
| :-------------- | :--------------------------------------- | :----------------------------------------- | :----------- |
| [RISC-V VP++][34] | RISC-V VP++ is an open-source, RISC-V virtual prototype based on SystemC TLM | Bare-metal, RTOS, or Linux with interactive graphical applications that are network-capable | MIT |   
| [ARMv8 Virtual Platform (AVP64)][7]      | OCX QEMU-based ARMv8 multi-core VP       | CoreMark, Dhrystone, Linux, Xen hypervisor | MIT          |
| [GreenSocs A53 VP][17] | ARM Cortex A53 multi-core VP (registration required) | Linux | GPLv2 |
| [GreenSocs N1 VP][18] | ARM Neoverse N1 multi-core VP (registration required) | Linux | GPLv2 |
| [GreenSocs RISC-V64 VP][19] | 64-bit RISC-V multi-core VP (registration required) | Linux | GPLv2 |
| [HIFIVE1-VP][8] | DBT-RISE-based RISC-V VP                 | FreeRTOS                                   | BSD-3-Clause |
| [OpenRISC 1000 Multicore VP (OR1KMVP)][9]    | OR1KISS-based multi-core OpenRISC1000 VP | Linux                                      | Apache-2.0   |
| [SymEx-VP][25]      | A concolic testing framework for RISC-V embedded software with support for SystemC peripherals.       | RIOT, Zephyr, NuttX, Zig | GPLv3          |
| [TGC-VP][10]    | The Scale4Edge ecosystem RISC-V VP | FreeRTOS | Apache-2.0 |
| [TLMBoy][30] | Game Boy VP | | Apache-2.0 |
| [Xilinx Zynq-7000][16] | QEMU based Xilinx Zynq-7000 SoC connected SystemC TLM 2.0  |  | MIT |

<br>
## Compilers, parsers, and source-to-source transformations 

| Name       | Description                                                                                                              | License    |
| :--------- | :----------------------------------------------------------------------------------------------------------------------- | :--------- |
| [Recoding Infrastructure for SystemC (RISC)][20] | Framework for analysis and agressive parallel simulation of embedded system models described in SystemC | BSD-3-Clause |
| [SystemC compiler][14] | Compiler which translates synthesizable SystemC design to synthesizable SystemVerilog design | Apache-2.0 |
| [systemc-clang][29] | Static analysis framework for RTL and TLM SystemC models including a HDL synthesis plugin that generates Verilog | systemc-clang |
| [Verilator][15] | Compiler and simulator which translates Verilog/SystemVerilog to SystemC | LGPLv3  |

<br>
## Simulators

| Name          | Description                               | License |
| :------------ | :---------------------------------------- | :------ |
| [SystemC][50] | SystemC Reference Implementation | Apache-2.0 |
| [SystemC-AMS][51] | SystemC-AMS Proof-of-concept implementation | Apache-2.0 |

<br>
## Python Integration

| Name       | Description                                                                                                              | License    |
| :--------- | :----------------------------------------------------------------------------------------------------------------------- | :--------- |
| [PySysC][11] | A Python package to make SystemC usable from Python. It supports composition of a SystemC/TLM model as well as running the simulation. | Apache-2.0 |

<br>
## Verification 

| Name       | Description                                                                                                              | License    |
| :--------- | :----------------------------------------------------------------------------------------------------------------------- | :--------- |
| [Assertions][33] | These SystemC assertions are intended to be used in simulation to check design correctness. These assertions are translated into equivalent SystemVerilog assertions (SVA) using the [SystemC compiler][31] | Apache-2.0 |
| [CRAVE][27] | Constrained RAndom Verification Environment | Apache-2.0 |
| [FC4SC][28] | Functional Coverage for SystemC | Apache-2.0 |
| [UVM-Connect][23] | UVM-based library that provides TLM1 and TLM2 connectivity and object passing between SystemC and SystemVerilog UVM models and components | Apache-2.0 |
| [UVM-ML][22] | Universal Verification Methodology Multi-Language (UVM-ML) Open Architecture supporting UVM-SV, UVM-e, and UVM-SC | Apache-2.0 |
| [UVM-SystemC][21] | Accellera implementation and standard of the Universal Verification Methodology (UVM) in SystemC | Apache-2.0 |

[1]: https://github.com/accellera-official/systemc.org/issues
[2]: https://github.com/nvdla/vp
[3]: https://github.com/machineware-gmbh/vcml/tree/main/src/vcml/models
[4]: https://github.com/aut0/vcml-nvdla
[5]: https://github.com/Minres/SystemC-Components
[6]: https://github.com/machineware-gmbh/vcml
[7]: https://github.com/aut0/avp64
[8]: https://github.com/Minres/HIFIVE1-VP
[9]: https://github.com/janweinstock/or1kmvp
[10]: https://github.com/Minres/TGC-VP
[11]: https://github.com/accellera-official/PySysC
[12]: https://github.com/VP-Vibes/VPV-Peripherals
[13]: https://hlslibs.org/
[14]: https://github.com/intel/systemc-compiler
[15]: https://github.com/verilator/verilator
[16]: https://github.com/Xilinx/systemctlm-cosim-demo
[17]: https://git.greensocs.com/platforms/greensocs-cortex-a53
[18]: https://git.greensocs.com/platforms/greensocs-neoverse-n1
[19]: https://git.greensocs.com/platforms/greensocs-riscv64
[20]: http://www.cecs.uci.edu/~doemer/risc.html
[21]: https://www.accellera.org/images/downloads/standards/systemc/uvm-systemc-1.0-beta4.tar.gz
[22]: https://forums.accellera.org/files/file/65-uvm-ml-open-architecture/
[23]: https://verificationacademy.com/topics/verification-methodology/uvm-connect
[24]: https://github.com/hsa-ees/paranut
[25]: https://github.com/agra-uni-bremen/symex-vp
[26]: https://gitlab.com/moy/sc-during
[27]: https://github.com/accellera-official/crave
[28]: https://github.com/accellera-official/fc4sc
[29]: https://github.com/anikau31/systemc-clang
[30]: https://github.com/not-chciken/TLMBoy
[31]: https://github.com/intel/systemc-compiler/wiki/SingleSource-library
[32]: https://github.com/intel/systemc-compiler/tree/main/components/common/sctcommon
[33]: https://github.com/intel/systemc-compiler/wiki/Immediate-and-temporal-assertions-in-SystemC
[34]: https://github.com/ics-jku/riscv-vp-plusplus
[35]: https://github.com/ics-jku/GUI-VP_Kit
[36]: https://github.com/tukl-msd/DRAMSys

[50]: https://github.com/accellera-official/systemc
[51]: https://www.coseda-tech.com/systemc-ams-proof-of-concept
