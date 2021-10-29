# SystemC Projects

This page gives an overview of open-source SystemC projects.
Please [let us know][1] if a project is missing or needs update.

## Models

This is a list of SystemC models for use in virtual platforms:

| Name             | Description                                                                             | License                                      |
| :--------------- | :-------------------------------------------------------------------------------------- | :------------------------------------------- |
| [NVIDIA Deep Learning Accelerator (NVDLA)][2] | SystemC TLM2.0-compatible virtual platform                 | NVIDIA Open NVDLA License and Agreement v1.0 |
| [Virtual Components Modeling Library (VCML) Models][3] | The VCML productivity library contains many component models (ARM, RISC-V, Virtio, ...) | Apache 2.0                                   |
| [Virtual Components Modeling Library (VCML) NVDLA Model][4]  | VCML integration of the NVDLA model                                                     | Apache 2.0                                   |
| [VPV-Peripherals][12]    | Library of example SystemC/TLM peripherals for various SoCs based on the SCC library    | Apache 2.0                                   |

## Productivity Libraries

Productivity libraries contain common resources that are required for building SystemC TLM2.0 virtual platforms.

| Name                         | Description                                                                            | License                      |
|:---------------------------- | :------------------------------------------------------------------------------------- | :--------------------------- |
| [SystemC-Components (SCC)][5] | A light weight productivity library for SystemC and TLM 2.0 based modeling tasks using C++11 provides common functions, components and modules often needed in SystemC based models | Apache 2.0 |
| [Virtual Components Modeling Library (VCML)][6]  | Sockets, Tracing, Registers, GDB server, Logging, Session Protocol, Component Models, Network backends, TLM2.0 protocols | Apache 2.0 |

## Virtual Platforms

This is a list of open-source Virtual Platforms (VPs):

| Name            | Description                              | Workloads                                  | License      |
| :-------------- | :--------------------------------------- | :----------------------------------------- | :----------- |
| [ARMv8 Virtual Platform (AVP64)][7]      | OCX QEMU-based ARMv8 multi-core VP       | CoreMark, Dhrystone, Linux, Xen hypervisor | MIT          |
| [HIFIVE1-VP][8] | DBT-RISE-based RISC-V VP                 | FreeRTOS                                   | BSD 3-Clause |
| [OpenRISC 1000 Multicore Virtual Platform (OR1KMVP)][9]    | OR1KISS-based multi-core OpenRISC1000 VP | Linux                                      | Apache 2.0   |
| [TGC-VP][10]    | The Scale4Edge ecosystem RISC-V VP | FreeRTOS | Apache 2.0 |

## Python Integration

| Name       | Description                                                                                                              | License    |
| :--------- | :----------------------------------------------------------------------------------------------------------------------- | :--------- |
| [PySysC][11] | A Python package to make SystemC usable from Python. It supports composition of a SystemC/TLM model as well as running the simulation. | Apache 2.0 |


[1]: https://github.com/accellera-official/systemc.org/issues
[2]: https://github.com/nvdla/vp
[3]: https://github.com/janweinstock/vcml/tree/master/src/vcml/models
[4]: https://github.com/aut0/vcml-nvdla
[5]: https://github.com/Minres/SystemC-Components
[6]: https://github.com/janweinstock/vcml
[7]: https://github.com/aut0/avp64
[8]: https://git.minres.com/VP/HIFIVE1-VP
[9]: https://github.com/janweinstock/or1kmvp
[10]: https://github.com/Minres/TGC-VP
[11]: https://github.com/accellera-official/PySysC
[12]: https://github.com/VP-Vibes/VPV-Peripherals
