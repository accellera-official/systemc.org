# SystemC for Verification 

Beyond SystemC’s built-in capabilities for system-level design and modeling, verification extensions are prodived to create a scalable verification infrastructure supporting verification at a higher level of abstraction, compatible with industry recognized methodologies such as the Universal Verification Methodology (UVM).

While the verification needs in SystemC evolve and integration with other languages is more and more frequent, additions to the existing capabilities are required. For example, these additions will also focus on coverage analysis and temporal assertion checking mechanisms and their interfacing and/or integration into the SystemC language. Standardizing these additions is crucial to allow seamless migration of models from the environment of one EDA tool supplier to another. This integration process also includes the analysis and evaluation of interfaces to existing Accellera verification approaches like UVM and their seamless integration into a C/C++ or SystemC-based verification process.

## SystemC Verification Library (SCV)

The  SystemC Verification (SCV) library provides a common set of APIs that are used as a basis to verification activities with SystemC, such as generation of values under constraints, transaction recording, etc. These APIs are implemented in all major SystemC simulators available on the market. 

The SystemC Verification Library 2.0.1 was released in December 2017. This release contains an implementation of the verification extensions for Accellera SystemC 2.3.2 and is compatible with IEEE 1666-2011. Examples and support for recent compilers is also included. [The document can be accessed here][1]. NOTE: There is no active development of the SCV library, the implementation is in maintenance mode. 

<img style="width:90%" src="/images/uvm-systemc-architecture.svg">

## UVM in SystemC (UVM-SystemC)

The UVM-SystemC library provides an implementation of the Universal Verification Methodology (UVM) in SystemC/C++. The UVM-SystemC class library enables the development of scalable and reusable verification collateral for system-level verification and testing. The aim of UVM-SystemC is to be API compatible with UVM in SystemVerilog, to faciliate seamless integration and exchange of Verification IP (VIP) between system-level and IP-level test benches.

See also: [UVM-SystemC Frequently Asked Questions](/overview/systemc-verification/uvm-systemc-faq/)

### Constrained Randomization library (CRAVE)

To introduce constrained randomization features, the external CRAVE library can be used in combination with UVM-SystemC. The syntax of CRAVE has been designed to naturally fit with C++ and SystemC. The CRAVE library includes modern BDD-based and SAT/SMT-based constraint solvers.

### Functional Coverage library (FC4SC)

To enable coverage-driven verification, the functional coverage library FC4SC can be used. FC4SC offers declaration of covergroups, bins, and coverpoints to enable type- and instance-based functional converage. The FC4SC library will store the coverage results in the Unified Coverage Interoperability Standard (UCIS) format, enabling seamless inclusion in various EDA solutions available on the market.    

## Resources

 * [SystemC Verification Library (SCV) 2.0.1 ][2]
 * [UVM-SystemC Library 1.0-beta4][3]
 * [CRAVE][4]
 * [FC4SC][5]

[1]: https://www.accellera.org/downloads/standards/systemc
[2]: https://www.accellera.org/images/downloads/standards/systemc/scv-2.0.1.tar.gz
[3]: https://www.accellera.org/images/downloads/standards/systemc/uvm-systemc-1.0-beta4.tar.gz
[4]: http://www.informatik.uni-bremen.de/agra/systemc-verification/crave.html
[5]: https://github.com/amiq-consulting/fc4sc
