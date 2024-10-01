# Chapter 12: Real-World Quantum Circuits

While still in its early stages, quantum computing holds enormous promise for solving complex problems that are difficult for classical computers. Several real-world quantum circuits have emerged, demonstrating the practical applications of quantum computing in various fields. Here are two:

## Quantum Fourier Transform

**Application**: Finance and Cryptography

**Description**: In quantum computing, the quantum Fourier transform (QFT) is a linear transformation on quantum bits, and is the quantum analogue of the discrete Fourier transform. The quantum Fourier transform is a part of many quantum algorithms, notably Shor's algorithm for factoring and computing the discrete logarithm, the quantum phase estimation algorithm for estimating the eigenvalues of a unitary operator, and algorithms for the hidden subgroup problem.

Source: https://en.wikipedia.org/wiki/Quantum_Fourier_transform

## Grover's Algorithm

**Application**: Unstructured Search

**Description**: Grover's algorithm is designed to search for a specific item from an unsorted list, using fewer steps than classical search algorithms. Here's how it works:

1. Initialize the qubits: Start by putting the qubits into an equal superposition using Hadamard gates, which ensures that all possible states are equally likely.

2. Apply the oracle function: This oracle marks the state corresponding to the correct answer by flipping its phase.

3. Amplitude amplification: This is the key part of Grover's algorithm. After the oracle marks the correct answer, Grover’s diffusion operator increases the amplitude (or likelihood) of the correct state and decreases the amplitude of others.

4. Repeat: The amplification process is repeated a certain number of times to maximize the chance of measuring the correct state. The number of repetitions depends on the size of the search space.

5. Measure: Once the correct state has a high probability, a measurement is made, and the output will most likely be the correct state.

Grover's algorithm provides a quadratic speedup over classical algorithms for search problems.

Source: https://learning.quantum.ibm.com/course/fundamentals-of-quantum-algorithms/grovers-algorithm
