# SystemC Configuration, Control and Inspection (CCI) 

The SystemC Configuration, Control and Inspection (CCI) standard enables greater interoperability of SystemC models within the SystemC ecosystem. 
It allows tools and models to work together to provide valuable user-level capabilities. 
The first phase of this standard addresses model configuration. The roadmap includes checkpointing and register introspection.

The SystemC CCI Working Group addressed several key concerns while defining the CCI 1.0 standard. 
Of critical importance is the ability to interact with tools for which a portable value representation has been provided, 
along with information about configuration parameters, including a description and flexible metadata. 
Among the fundamental features in the standard are avoiding name clashes with elements of the SystemC object hierarchy, 
looking up and accessing configuration parameters, restricting access to parameters, preloading configuration settings, 
callbacks for parameter creation/destruction as well as value access, traceability of parameter value updates, and 
support for user-defined parameter value types

<img style="width:90%" src="/images/systemc-cci-layers.svg">

## Resources

 * [Download SystemC CCI 1.0][1]
 * [SystemC CCI reference implementation on GitHub][4]
 * Video tutorial: [SystemC Design and Verification - Solidifying the Abstraction Above RTL][2] delivered at DVCon U.S. 2017. Part 2 of this video tutorial delves into the CCI configuration standard.
 * [CCI Working Group Update][3] delivered as part of the "Deploying SystemC for Complex System Prototyping and Validation" tutorial at DVCon 2013
  
[1]: https://www.accellera.org/downloads/standards/systemc/
[2]: https://vimeo.com/479408883
[3]: https://www.accellera.org/images/community/systemc/about-systemc-cci/CCI_WG_Update_2-25-2013.pdf
[4]: https://github.com/accellera-official/cci