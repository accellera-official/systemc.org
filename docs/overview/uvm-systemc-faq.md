toc: false

# UVM-SystemC Frequently Asked Questions
<br>
## What is UVM-SystemC?

UVM-SystemC is a new standard to develop structured verification environments in SystemC/C++, following the Universal Verification Methodology (UVM). UVM-SystemC is defined in a language reference manual (LRM) and supported by a proof-of-concept implementation, implemented as a class library based on C++ and SystemC.

## What is the objective of the public review period?

Accellera solicits feedback on the UVM-SystemC standard defined in the LRM. Furthermore, feedback is welcome highlighting discrepancies between the standard and the proof-of-concept implementation.

## Does UVM-SystemC support constrained randomization?

The UVM-SystemC proof-of-concept implementation does not contain a constraint solver for randomization. Instead, an add-on library for randomization and constraints is required, such as CRAVE.

## Where can I find UVM-SystemC examples?

The UVM-SystemC release contains some basic examples showing the capabilities of the standard and proof-of-concept implementation.

## What do I need to run UVM-SystemC?

UVM-SystemC requires a C++ compiler and a SystemC library compatible with IEEE Std. 1666-2011, for example the Accellera SystemC 2.3.3 reference implementation, which can be found [here](https://www.accellera.org/downloads/standards/systemc).

## Is UVM in SystemC compatible with UVM in SystemVerilog?

The UVM-SystemC language definition aims to be fully compatible with the Accellera UVM standard in SystemVerilog. The development of UVM-SystemC is based on Accellera UVM 1.2. Due to some reserved keywords in C++, a few functions and methods differ. In addition, the use of C++ and SystemC language concepts are promoted, resulting in more elegant and powerful functionality, for example using Transaction Level Modeling (TLM). The differences between UVM-SystemC and UVM-SystemVerilog are clearly indicated in the LRM.

## Is UVM-SystemC compatible with UVM 1.2 or IEEE 1800.2?

Please check the UVM-SystemC language reference manual (LRM) for the exact definition of the API. The LRM can be found in the `docs` directory of the UVM-SystemC proof-of-concept implementation.

## Can I mix Verification IP developed in UVM-SystemC with VIP created in UVM-SystemVerilog?

The UVM-SystemC release does not address multi-language concepts. Additional libraries are required to interface between the SystemC and SystemVerilog verification components. Please contact your local EDA solution provider whether they can offer a multi-language interface. Accellera is also addressing the need to standardize the multi-language concept, as part of the [Multi-language Verification Working Group](https://www.accellera.org/activities/working-groups/multi-language). 

## Can I create register models in UVM-SystemC?

Yes, the current version of UVM-SystemC does contain the register abstraction layer to create register models. Please contact your local EDA solution provider whether they can offer an automated register generation flow using register descriptions in IP-XACT or SystemRDL.

## Is UVM-SystemC supported by commercial EDA tools?

Please contact your local EDA solution provider to check if UVM-SystemC is supported. As UVM-SystemC is built on top of SystemC, most SystemC IEEE Std. 1666-2011 compatible simulators should be able to incorporate UVM-SystemC.

## Can I verify my SystemC virtual prototype with UVM-SystemC?

Yes, any SystemC representation can be combined with the UVM-SystemC verification environment.

## Can I verify my RTL design with UVM-SystemC?

Including your RTL design (in Verilog, SystemVerilog or VHDL) requires mixed-language support. Please contact your local EDA solution provider to check if UVM-SystemC can be combined with your RTL design.

## Is there a User’s Guide for UVM-SystemC?

The release package of UVM-SystemC contains a tutorial presentation, which contains examples showing how to create UVM-SystemC components, test benches, and tests.

## Will UVM-SystemC become an IEEE standard?

Accellera will host the development of UVM-SystemC standard and proof-of-concept implementation, to ensure it develops into a mature and stable standard. As soon as certain quality and stability level is reached, Accellera will consider contributing UVM-SystemC to the IEEE Standards Association. It is expected that this will take some years.

## Is UVM-SystemC open source?

Yes, the UVM-SystemC language reference manual as well as the proof-of-concept library are released under the Apache 2.0 open source license.

## Where can I find more information on UVM-SystemC?

The latest UVM-SystemC proof-of-concept implementation can be downloaded [here](https://www.accellera.org/downloads/drafts-review).
Please visit the [SystemC Verification Working Group](https://www.accellera.org/activities/working-groups/systemc-verification) page for more information or post your questions and findings in the Accellera [forums](http://forums.accellera.org). 

## How can I contribute to this initiative?

Accellera members can contribute to this project by joining the SystemC Verification Working Group. If your company is not member, you can find out more about Accellera membership [here](https://www.accellera.org/about/join).

## What is the timeline for the next release?

Releases are created when defined milestones are reached. Ongoing major activities are the integration and testing of the register layer and constraint randomization capabilities. Additional support and contributions are highly appreciated. The Working Group’s plan is to release regular updates including bug fixes and new functionality, but this is highly dependent on the progress and number of active contributors to the development.
