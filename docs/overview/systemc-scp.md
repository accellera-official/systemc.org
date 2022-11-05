# SystemC Common Practices (SCP) 

The SystemC Common Practices project provides peer-reviewed, standards compliant, basic infrastructure that you can use in your SystemC projects.

The emphasis is to show how the other SystemC standards can best be used, and provide a common set of basic components.

Each component in the SCP project can be used individually, or they may be used together. The intention is that all components are interoperable and work on standard SystemC simulators.

The Accellera SCP working group meets regularly and the SCP project is updated frequently with new contributions. If you have some code you think others would find useful, please be in touch!

Current components include:
 * TLM Extensions 
    - A growing list of extensions from which to build specfic bus features, or debug and tracing features
 * Report and logging
    - Enables logging using the SPDLOG library (see https://github.com/gabime/spdlog)
    - Flexible colouring and formatting options
    - Thread safe
    - captures SC_REPORT as well as providing a convenient streaming interface.
    - Streaming interface is extremely efficient

We have plans to extend the extension interface and also
 - [ ] Extend list of extensions to cover more bus types (including cache coherency and self-discovery type busses)
 - [ ] Register implementation
 - [ ] Synchronisation library that supports multi-threading
 - [ ] RPC transport for both TLM and Signal interfaces to connect multi-process simulation.
 
<img style="width:90%" src="/images/systemc-scp-layers.svg">

## Resources

 * [SystemC Common Practices on GitHub][1]
   
[1]: https://github.com/accellera-official/systemc-common-practices
