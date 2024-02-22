# QHACK2024
Project done for the open hackathon phase of the QHACK2024 event by the team "Qubits By The Nalon"

## Objective
The main goal of this study is to explore ways of reducing the number of qubits required by a quantum algorithm. This task could have very beneficial consequences as it would improve the capabilities of said algorithm in the current era of NISQ computers, in which the number of available resources, in this case, qubits, are somewhat limited.
In order to do this, we will be using several cutting-edge techniques that have been developed in recent studies, such as circuit cutting, and cat qubits.

## Algorithm
In this case, we have opted for Grover’s algorithm, which is a well known and established option in the field, as well as a fitting choice for quantum computing enthusiasts that gravitate more towards a beginner level.
Grover's algorithm is a quantum algorithm primarily used for searching a specific entry in an unsorted list of items, providing a significant quantum advantage over classical algorithms.
It efficiently searches an unsorted list, offering a quadratic speedup over classical algorithms. This means that while a classical algorithm would require, on average, N/2 steps to search for an item in a list of N elements, Grover's algorithm would require approximately the square root of N steps. This is achieved using quantum operations such as the Hadamard transform and the inversion about the mean.

## Study
The different tests and its outputs can be seen in the notebooks "Grover_CatQubits.ipynb" and "Grover_Cutting.ipynb"
