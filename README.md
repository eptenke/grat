# grat
GRAT Robotics Assembly Toolkit

Bots that make bots

## What is GRAT?

GRAT aims to be a robotic platform for assembling and disassembling other open source robotic projects.

Compilers that can compile their own code ([self hosted](https://en.m.wikipedia.org/wiki/Self-hosting_(compilers))) revolutionized software.  Compilers offered a single specification across multiple platforms, enabling collaboration and interoperability.  Linkers assemble parts that compilers produce.  Make resolves dependencies.  And so on.  We can now initiate a complex build with a single command that downloads and builds hundreds of other programs and libraries.

GRAT is a bot that makes bots.  A self hosted assembly bot will enable one to keep up with updates in various open hardware projects, facilitating collaboration and interoperability between different bot projects.  How can we autoupdate our bots without being able first to automatically assemble and disassemble them?

## Why?

Firstly, because it is hard to keep up with developments in the open source hardware world.  There are barriers to entry in terms of technical knowhow and monetary resources that a bootstrapping process could circumvent, much like bootstrapping BSD ports onto a given architecture.  GRAT would help one evaluate proposed commits to robotics projects, keep up to date with the current branches of various projects, and generally be the indispensable compiler and linker we have come to rely upon in the software world.  Eventually repositories enabled by GRAT would allow dependency checking and automatic download and build, just as BSD ports have been enabled by gcc.

Secondly, because robotics are threatening jobs worldwide, and this project aims to stand in the gap, democratizing robotics, enabling desktop manufacturing on a wide scale, and generally bringing the equity gains from using and owning robotics into the common user's grasp.  Coupled with such projects as RepRap for printing, and FarmBot for agriculture, we start being able to meet very real needs in a manageable way.  As such, this project must be open source, free of corporate control, as the people's means to supply for itself, even if currency may be hard to come by.

Thirdly, because we need privacy and personal security.  It is hard to introduce backdoors into open source code, since many eyes can detect and rollback such attempts.  Control over our things is how to ensure continuing privacy and personal security in an age where it seems everything in the IoT is spying on us, or at least storing off our data in bulk.  This need not be the case if we build our own.

Eventually, in the far future, GRAT could enable a suite of bots, each doing its job well: the main assembler/disassembler to compile and update bots, a linker to attach and detach modules at runtime (mobility chassis, toolhead switches, etc...), a recycler to melt down plastic for printer feed (or equivalents for other materials), space and shelving formatters, ID taggers, motor winders, automatic chemistry or DNA labs, and so on.

## How do I get started?

This project is beginning with assisted prints.  The first step will be to remove prints from the print bed, scrape the bed, and then start the next gcode.  Next step might be command line slicing with slic3r, if we need to add a structure for automatic print removal.

See the [Contributing.md](https://github.com/eptenke/grat/blob/master/CONTRIBUTING.md)

See [the GRAT wiki](https://github.com/eptenke/grat/wiki) for more information on getting started.
