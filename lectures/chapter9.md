# Chapter 9: P gate: Phase shift (aka S gate)

In QuICScript, the P-gate is denoted with the letter 'P' which comes from it's name 'Phase." Whereas, As opposed to 'S' if you are referring to the Nielsen and Chuang book. Denoting phase gate by 'P' comes from its name Phase. It performs a specific operation on a single qubit in a quantum circuit. When you apply the P gate to a quantum state represented as (|0⟩ and |1⟩), it has the following effect:

![Linear Algebra](./figures/P-gate.png)

In simpler terms, the P gate leaves the |0⟩ state unchanged and introduces a phase shift π/2 (90 degrees) to the |1⟩ state (i.e., multiplying by the imaginary unit "i"). This is the Matrix representation:

![Matrix](./figures/P-gate2.png)

_Note: The number of qubits required in the circuit for this gate is 1._

The P gate is often used to introduce relative phase differences between the |0⟩ and |1⟩ states. The phase shift gate is used in quantum algorithms such as quantum phase estimation algorithm and the quantum Fourier transform.

Exercise: Assignment 7
