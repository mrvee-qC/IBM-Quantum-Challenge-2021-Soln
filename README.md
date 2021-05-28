# IBM-Quantum-Challenge-2021-Soln
My version of solutions for the IBM Quantum Challenge 2021 held on May 2021. Solution is as is without any modification. May need code cleanup.

Scores for exercises:
- Exercise 1: 
- 
Toffoli gate
Tommaso Toffoli devised a reversible version of classical computing's AND and NAND gates—now called the Toffoli, or controlled-controlled-NOT gate. This is a universal gate for classical computation, meaning that any program can be built from many instances of this gate. Drawing on the existing work on reversible computing, the quantum implementation of the Toffoli gate became one of the first building blocks for quantum computing. Though not universal for quantum computation on its own, its classical universality makes it very important for tasks such as building quantum oracles.

Problem: Construct a Toffoli gate using the basis gates (CX, RZ, SX and X gates) of IBM Quantum systems.

Estimated time to complete: 0.1 - 1 hour

Score = 72

- Exercise 2:
- 
- Shor's algorithm
Peter Shor showed that quantum computers can factor numbers exponentially faster than any classical computer can. Shor's algorithm proved that a quantum computer could have important applications beyond simulating physics, and would be a worthwhile direction to pursue for computation overall. Quantum computers large enough to factor large numbers—such as the large numbers that the RSA encryption scheme uses to encode data—are likely many years away. However, IBM researchers were able to demonstrate hardware factoring the number 15 as early as 2001.

Problem: Factor number 35 using Shor's algorithm.

Estimated time to complete: 1 - 2 hours

Score = 48

- Exercise 3:
- 
Quantum error correction
Shor's algorithm gave quantum computers a worthwhile use case—but the inherent noisiness of quantum mechanics meant that building hardware capable of running such an algorithm would be a huge struggle. In 1995, Shor released another landmark paper: a scheme that shared quantum information over multiple qubits in order to reduce errors. Today, error correction schemes are one of the most important areas of quantum computing research and development.

Problem: Implement a small quantum error correction code.

Estimated time to complete: 1 - 2 hours

Score = 169

- Exercise 4:
- 
- Transmon qubits
A team of physicists based at Yale debuted a new type of qubits based on superconducting circuits called transmon qubits. Building on understanding of noise sources on earlier variants of superconducting qubits, transmon qubits's design significantly reduced its sensitivity to charge noise, resulting in longer coherence time. Transmon qubits serve as the backbone of IBM's quantum systems today.

Problem: Using Qiskit Pulse, study the behavior of transmon qubits in IBM Quantum systems.

Estimated time to complete: 1 - 4 hours

Score = Completed

- Exercise 5:
-
Variational quantum eigensolver
During the last decade, quantum computers matured quickly—and began to realize Feynman's initial dream of a computing system that could simulate the laws of nature in a quantum way. A 2014 paper first authored by Alberto Peruzzo introduced the Variational Quantum Eigensolver (VQE), an algorithm meant for finding the ground state energy of a molecule, with much shallower circuits than other approaches. And, in 2017, the IBM Quantum team used the VQE algorithm to simulate the ground state energy of lithium hydride molecule.

Problem: Using VQE in Qiskit Nature, find the smallest ansatz with high chemical accuracy to simulate the ground state energy of lithium hydride molecule

Estimated time to complete: 3 - 10 hours

Score = 3

Final Rank for last exercise =  1 
