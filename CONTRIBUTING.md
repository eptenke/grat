# Contributing to OpenGRAT

## Get on the Mailing List
The OpenGRAT community can communicate through this google group:
https://groups.google.com/forum/#!forum/opengrat

## Design Guidelines
* KISS.  Literally.  Keep the bots stupid.  Intelligent bots take way more programming and testing.  Whatever we can do to take the need for smarts out can be a gain in robustness, maintainability, and raw capability.  For example:
** Marking grip points in the design of an object
** Marking QR codes on objects to identify them

## Priorities/Roadmap

### Arm Selection

The first priority is evaluating the current robotic arm projects for a likely candidate.  Research and analysis are being collected in the [Robotic Arms wiki page](https://github.com/eptenke/grat/wiki/RoboticArms)

### Assembly Analysis

We will need to think about the basic tasks of bot assembly, and what that might eventually look like.  There is no need that an assembler/disassembler end up as a robotic arm.  It seems a good fit, but perhaps we can imagine something better.  Arm selection above is merely for bootstrapping.  This asks more the question of what we want our bot to look like.

Bots need not be the only thing a grat can assemble.  Perhaps there is commercial value in assembling other things (eg Ikea).  How might that inform assembly design?

