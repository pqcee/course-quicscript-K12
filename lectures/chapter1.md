# Chapter 1: The Qubit

Qubits are the fundamental units of information in quantum computing, analogous to classical bits in classical computing. They can be stored in "quantum memory" and processed by a "quantum processor." In quantum information theory, we abstract qubits for practical programming. But what exactly is a qubit?
A qubit is like a classical bit, but it can exist in a superposition of both states simultaneously, thanks to the principles of quantum mechanics. Instead of using "0" and "1" to label its two states, we represent them as follows:

|0⟩ and |1⟩

These vectors are an abstract way to describe the states of a qubit. We can combine them using linear combinations, introducing coefficients (called amplitudes) like this:

α|0⟩ + β|1⟩

'α' and 'β' are complex numbers. They represent the probability amplitudes of the qubit being in the state |0⟩ and |1⟩, respectively. Qubits can exist in a superposition of these states, where 'α' and 'β' can be both positive and negative. This property allows for quantum interference, a key element in quantum computing's power.

![Bloch Sphere](/figures/bloch_sphere.png)

Source: [Research Gate](https://www.researchgate.net/figure/The-Bloch-sphere-provides-a-useful-means-of-visualizing-the-state-of-a-single-qubit-and_fig1_335028508)
