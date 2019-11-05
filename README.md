# grat
GRAT Robotics Assembly Toolkit

## What is GRAT?

GRAT aims to be a robotic platform for assembling and disassembling other open source robotic projects.

In the early days of programming, the first compilers revolutionized programming, allowing collaboration on a far greater scale than previously.  A compiler that could create a compiler, as well as compile other programs, allowed one to work at a higher symbolic level, leaving assembler work for those portions that truly required optimization.  Programs could be developed for multiple platforms, and developers from these multiple platforms could work together on the same codebase.

The current state of open source hardware is analogous to programming directly in machine code.  GRAT aims to be a robot assembler/disassembler, enabling one to keep up with updates in various open hardware projects.  We have come to expect being able to "make; make install" for software, and it can create the software with little intervention.  We want to do the same for robotics projects, and we believe that such a robot compiler would bring open source robotics and its collaboration to an unparalleled new level.

## Why?

Firstly, because it is hard to keep up with developments in the open source hardware world.  There are barriers to entry in terms of technical knowhow and monetary resources that a bootstrapping process could circumvent, much like bootstrapping BSD ports onto a given architecture.  GRAT would help one evaluate proposed commits to robotics projects, keep up to date with the current branches of various projects, and generally be the indispensable compiler and linker we have come to rely upon in the software world.  Eventually repositories enabled by GRAT would allow dependency checking and automatic download and build, just as BSD ports have been enabled by gcc.

Secondly, because robotics are threatening jobs worldwide, and this project aims to stand in the gap, democratizing robotics, enabling desktop manufacturing on a wide scale, and generally bringing the equity gains from using and owning robotics into the common user's grasp.  Coupled with such projects as RepRap for printing, and FarmBot for agriculture, we start being able to meet very real needs in a manageable way.  As such, this project must be open source, free of corporate control, as the people's means to supply for itself, even if currency may be hard to come by.

Eventually, in the far future, GRAT could enable a suite of bots, each doing its job well: the main assembler/disassembler to compile and update bots, a linker to attach and detach modules at runtime (mobility chassis, toolhead switches, etc...), a recycler to melt down plastic for printer feed (or equivalents for other materials), space and shelving formatters, ID taggers, motor winders, automatic chemistry or DNA labs, and so on.

## How do I get started?

Currently GRAT has no code.  We need help!

The first goal is to create a GRAT: a minimally self-compiling compiler.  Basic tools toward this end will be a 3D printer and a programmable robotic arm.  The first GRAT will likely be a modified open source programmable robotic arm project.  

Good candidates should be desktop-sized, affordable, open source, and programmable.  An Annin AR2 might be a good first place to look.  The AR2 and AR3 have project goals in line with ours, and are touted to put robotics within grasp of the common user.  They're also supposedly printable, though aluminum construction may be preferred.  If plastic extrusion is possible for an AR2 parts, this might be a good starting place.  However, it is quite expensive.

Other options include the Thor arm or the BCN3D Moveo.  Both are open source, printable, and more affordable, but the question is whether they're powerful enough.

pyBot might be an excellent choice.  It is very inexpensive ($87).  The reverse kinematics are solved and handled, ans you can specify trajectories.  Programmed in python.  Completely open source.  But will 3 degrees of freedom be enough?  Will its SCARA format be sufficient?  

Eventually, it should be possible to spend $300 for a minimal arm and printer, download the bootstrapper instructions, and bootstrap a grat, from which you can build any other robotics project.  We are currently nowhere close, but that is the goal.
