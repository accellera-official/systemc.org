# SystemC

**The language for System-level design, modeling and verification**

SystemC™ addresses the need for a system design and verification language that spans hardware and software. It is a language built in standard C++ by extending the language with the use of class libraries. The language is particularly suited to model system's partitioning, to evaluate and verify the assignment of blocks to either hardware or software implementations, and to architect and measure the interactions between and among functional blocks. Leading companies in the intellectual property (IP), electronic design automation (EDA), semiconductor, electronic systems, and embedded software industries currently use SystemC for architectural exploration, to deliver high-performance hardware blocks at various levels of abstraction and to develop virtual platforms for hardware/software co-design. SystemC has been standardized by the Open SystemC Initiative (OSCI) and [Accellera Systems Initiative][1] and ratified as [IEEE Std. 1666™-2011][2].

![image](/images/systemc-architecture.svg)

## Why SystemC?

An SoC is literally a system on a chip, consisting of both silicon and embedded software. Its design involves complex algorithm and architecture development and analysis similar to that performed in system design – a trade-off process that determines critical metrics, such as SOC performance, functionality, and power consumption.

Consequently, design tools must deliver orders-of-magnitude improvement in productivity at both architectural and implementation (RT and physical) levels. Moreover, tools must support a methodology that enables the early development of embedded application and system software, long before the availability of the RTL design or silicon prototype. Failure to achieve the requisite improvements in design productivity would result in missed market windows, and exploding design costs.

SystemC is a single, unified design and verification language that expresses architectural and other system-level attributes in the form of open-source C++ classes. It enables design and verification at the system level, independent of any detailed hardware and software implementation, as well as enabling co-verification with RTL design. This higher level of abstraction enables considerably faster, more productive architectural trade-off analysis, design, and redesign than is possible at the more detailed RT level. Furthermore, verification of system architecture and other system-level attributes is orders of magnitude faster than that at the pin-accurate, timing-accurate RT level.

The SystemC community consists of a large and growing number of system design companies, semiconductor companies, intellectual property providers, and EDA tool vendors who have joined together to support and promote the standard.

## SystemC Transaction Level Modeling (TLM)

The Transaction Level Modeling standard defines interfaces for SystemC, providing an essential framework for model exchange within companies and across the IP supply chain for architecture analysis, software development and performance analysis, and hardware verification. It explicitly addresses virtual prototyping in which SystemC models can easily be exchanged and arranged within a system, enabling the optimal reuse of models and modeling effort across different use cases.

[More information about SystemC TLM](/overview/systemc-tlm/)

## SystemC Analog/Mixed-Signal (AMS)

The SystemC AMS standard defined in [IEEE Std. 1666.1-2016][3] introduces system-level design and modeling of embedded Analog/Mixed-Signal (AMS) systems. SystemC AMS provides unique capabilities for the design and modeling of embedded analog/mixed-signal applications at higher levels of design abstraction. The SystemC AMS extensions define a uniform and standardized modeling approach that can be used in combination with digitally-oriented ESL design methods, supporting a design refinement methodology for functional modeling, architecture exploration, and virtual prototyping of embedded analog/mixed-signal systems.

[More information about SystemC AMS](/overview/systemc-ams/)

## SystemC Configuration, Control and Inspection (CCI)

The goal of Configuration, Control and Inspection (CCI) is to improve efficiency and ROI for model creators and tool providers. They CCI standards will allow suppliers to instrument models so that a rich user experience is enabled, and they will allow industry tools to leverage this instrumentation to provide powerful debug and analysis capabilities. The CCI working group is currently defining standards for the exchange of information between SystemC models and tools.

[More information about SystemC CCI](/overview/systemc-cci/)

## SystemC Verification (UVM-SystemC, SCV)

The UVM-SystemC library provides an implementation of the Universal Verification Methodology (UVM) in SystemC. The UVM-SystemC class library enables the development of scalable and reusable verification collateral for system-level verification and testing.

The SystemC Verification (SCV) library provides a common set of APIs that are used as a basis to verification activities with SystemC (generation of values under constraints, transaction recording, etc.). These APIs are implemented in all major SystemC simulators available on the market.

[More information about SystemC Verification](/overview/systemc-verification/)

## Resources

* [Download SystemC/TLM standard, IEEE 1666-2011][1] 
* [SystemC/TLM reference implementation on GitHub][4]

[1]: https://accellera.org
[2]: https://standards.ieee.org/standard/1666-2011.html
[3]: https://standards.ieee.org/standard/1666_1-2016.html
[4]: https://github.com/accellera-official/systemc
