# Chapter 10: T gate: Phase shift π/4

The T-gate is a unitary operator that introduces a phase shift of π/4 to a quantum state. When you apply the T-gate to a quantum state represented as vectors (|0⟩ and |1⟩), it has the following effect:

![Linear Algebra](./figures/T-gate.png)

T-gate doesn't change the |0⟩ state, but it introduces a phase factor of e^(iπ/4) to the |1⟩ state. This phase shift is equivalent to a 45-degree rotation about the Z-axis.

Matrix representation:

![Matrix](./figures/T-gate2.png)

_Note: The number of qubits required in the circuit for this gate is 1._

The T-gate is often used in quantum algorithms for creating specific phase relationships, and it's particularly important in quantum error correction codes and quantum algorithms such as the Quantum Phase Estimation algorithm.

Exercise: Assignment 8
