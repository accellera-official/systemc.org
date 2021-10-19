# SystemC Analog/Mixed-Signal Extensions

The SystemC AMS standard ([IEEE Std. 1666.1-2016][1]) introduces system-level design and modeling of embedded Analog/Mixed-Signal (AMS) systems. The SystemC AMS extensions define a uniform and standardized modeling approach at higher levels of abstraction, that can be used in combination with digital and SystemC-centric design methods, supporting a design refinement methodology for functional modeling, architecture exploration, and virtual prototyping of embedded analog/mixed-signal systems and applications.

![image](/images/systemc-ams-architecture.svg)

## Why SystemC AMS?

The SystemC AMS standard, ratified as [IEEE Std. 1666.1-2016][1], fulfills the need of the electronics industry to have a standardized system-level modeling language for mixed-signal applications based on SystemC and C++. The SystemC AMS standard defines the execution semantics and language constructs for system-level design and modeling of embedded analog/mixed-signal systems at higher levels of abstraction, focusing on modeling accuracy, fidelity and simulation speed.

## What is the difference between SystemC AMS and other HDL languages?

The SystemC AMS extensions focus on the system-level (ESL) and architecture modeling aspects for mixed-signal  applications, such as communcation, RF, automotive and sensor applications. By having AMS extensions for SystemC, users can now create mixed-signal virtual prototypes to make an executable description of the entire system in a C++ based manner, enabling a seamless integration of HW/SW architectures in SystemC, TLM, embedded software in C, and analog or contiuous-time functionality modeled in SystemC AMS.

For abstract mixed-signal modeling, SystemC AMS offers the efficient Timed Data Flow model of computation to describe continuous signals in a discrete-time manner. The use of data flow semantics make the simulation much faster than traditional real-number-modeling approaches which use the inefficient discrete-event (digital) simulator, such as Verilog-AMS wreal or SystemVerilog real nettypess. Timed Data Flow simulation in SystemC AMS applies smart temporal abstraction techniques which reduce the simulation overhead, resulting in a significant speed-up, which is essential for virtual prototyping. This technique is comparable with TLM, but is now introduced for AMS signals.

## Is there a reference implementation available for SystemC AMS?

A [SystemC AMS proof-of-concept implementation][3] is available under Apache 2.0 license, offered by COSEDA Technologies GmbH. It contains a class library in C++, and therefore can be compiled against a SystemC IEEE Std 1666-2011 compatible simulator. 

In addition, commercial simulation environments are available supporting SystemC and SystemC AMS, offereing much more capabilities compared to the reference implementations. For example, commercial tooling supprt enhanced design automation for system-level design, offer modeling libraries and enhanced tracing and debug capabilities. Please contact your local EDA vendor representative whether SystemC AMS is supported.

## How can I learn to use SystemC AMS?

It is recommended is to start reading the SystemC AMS user's guide, which can be downloaded [here][4]. The user's guide explains all fundamentals of the SystemC AMS language and how to use the extensive set of features for AMS behavioral modeling at the system level. The application examples from the SystemC AMS user's guide can be found [here][5].

## Is SystemC AMS an international standard?

Yes. SystemC AMS has been transferred to IEEE, resulting in the release of IEEE Std 1666.1-2016. Thanks to Accellera sponsorship, the IEEE standard is made available under the [IEEE Get Program][2] free of charge. You can download the IEEE Std 1666.1-2016 [here][1].

[1]: https://standards.ieee.org/standard/1666_1-2016.html
[2]: https://ieeexplore.ieee.org/browse/standards/get-program/page
[3]: https://www.coseda-tech.com/systemc-ams-proof-of-concept
[4]: https://www.accellera.org/images/downloads/standards/systemc/Accellera_SystemC_AMS_Users_Guide_January_2020.pdf
[5]: https://www.accellera.org/images/downloads/standards/systemc/application_examples.zip
