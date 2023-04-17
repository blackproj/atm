# Model checking for a very simple Automated Teller Machine - Generic Access Control 
![Made with love in Italy](https://madewithlove.now.sh/it?colorB=%231472a4) [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/Naereen/badges/)

Basic Automated Teller Machine (ATM) model checking


* Several state of system are accepted:
    * Welcome (Default state)
    * Grant
    * Deny
* User actions permitted:
    * Ask amount
    * Print balance
    * Abort

## Getting Started

* Model checking is an automatic verification technique for finite-state concurrent and reactive systems. It is developed to verify if assertions on a system are true or false.
* This project aim to provide a model of a basic ATM validated through NuSMV (New Symbolic Model Checker). This model checker is useful for the analysis of synchronous finite-state and infinite-state systems [link](https://nusmv.fbk.eu/).
* Specifications are expressed in Linear Temporal Logic (LTL) form.
* NuSMV is a very powerful tool cause will check each specification automatically, informing whether it is satisfied or producing a trace (when possible) to demonstrate its violation.
* In the first step it is necessary to define a proper model of a finite-state machine for the intended system.
* After that is required to translate the model in the associated system description language.

## Installation
* Download latest version.
* Unpack and launch the proper binary of NuSMV

## Documentation
* Full documentation is provided only on Italian. FSM used is also included (manual folder).

## Examples

NuSMV can be used either interactively or in batch mode. To check a model against a set of specifications, you need to write the specification and system description at the bottom of a file with the .smv extension and then type the command:
    /path_of_binary/NuSMV.exe ATM.smv

## License

This project is licensed under the MIT License - see the LICENSE file for futher details.

_For any questions or doubts, feel free to contact me at gabriele.patta@outlook.com_