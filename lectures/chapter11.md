# Chapter 11: QuICScript Builder and Engine

The QuICScript is a 20-qubit quantum program simulator & visualizer that runs within your browser.

It stands for Quantum Interpreted Circuits Scripts, where the BNF notation of a QuICScript quantum program is as follows:

<Program> ::= <Gate sequence> | <Program><Delim><Gate sequence>
<Gate sequence> ::= <Gate> | <Gate><Gate sequence>
<Gate> ::= H | C | N | X | Y | Z | P | p | T | t | I | m
<Delim> ::= , | .

The use of QuICScript allows for efficient description and execution of quantum programs.

## Specs

![Specs](./figures/specs.png)

Exercise: Assignment 9
