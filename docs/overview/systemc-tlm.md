# SystemC Transaction Level Modeling (TLM) 

Transaction-level Modeling (TLM) standard interfaces for SystemC provides an essential framework needed for model exchange within companies and across the IP supply chain for architecture analysis, software development and performance analysis, and hardware verification. It explicitly addresses virtual prototyping in which SystemC models can easily be exchanged and arranged within a system. By providing a strong modeling foundation for virtual prototyping, the standard enables optimal reuse of models and modeling effort across different use cases.

TLM focuses on the modeling of systems based on memory-mapped busses and on-chip communication networks. Use cases have been categorized according to a range of criteria, leading to standard interfaces differentiated by loosely-timed (LT) and approximately-timed (AT) modeling styles.

The extended APIs provide a fundamental, general-purpose interoperability layer. A specific payload, to be used in conjunction with these interfaces, helps achieve a higher degree of interoperability when generically modeling memory-mapped bus-based components.

Several TLM features boost simulation performance — enabling what is called "speed interoperability" in addition to "model interoperability" for SystemC virtual platforms. Temporal decoupling allows initiator models, such as instruction set simulators, to run ahead of the SystemC kernel and synchronize only periodically to significantly reduce the required number of costly context switches. The direct memory interface allows interconnect models to be bypassed, facilitating high-speed access to modeled memory. A dedicated transaction debug interface ensures that debugging is an integral part of a system model while enabling debug activity without interference with the system simulation.

SystemC TLM is integral part of the SystemC langauge standard defined in [IEEE Std 1666-2011][1].

<img style="width:90%" src="/images/systemc-tlm-layers.svg">

## Resources

 * [SystemC Standard, Language Reference Manual, IEEE Std 1666-2011][1]
 * Video: [System-Level Modeling for Today and Tomorrow with SystemC][2]
 * Book: [Transaction Level Modeling with SystemC][3]

[1]: https://standards.ieee.org/standard/1666-2011.html
[2]: https://vimeo.com/158713775
[3]: https://link.springer.com/book/10.1007/b137175