Student: Patrina Pun

Mentor: Dr. Puspita Chatterjee


# Week 5

**Dates:** 07-29 to 08-05

## Goals

- I will dive further into Noisy Intermediate-Scale Quantum (NISQ) computing and inject noise into quantum simulations to model realistic hardware errors.
- I will document my findings and observations. 

## Approach and Implementation

- To better understand Noisy Intermediate-Scale Quantum (NISQ) computing, I explored how different quantum noise models affect circuit performance by implementing noisy simulations in Qiskit using Google Colab. I prompted an AI assistant for guidance on injecting depolarizing noise into a quantum circuit and comparing the noisy simulation against the ideal, noise-free results. I researched several common quantum noise models, including depolarizing noise, bit-flip, phase-flip, and amplitude damping, and investigated their effects on circuits containing Hadamard (H) and controlled-NOT (CX) gates. When initial simulations did not produce noticeable errors, I experimented with modifying measurement operations and circuit configurations to observe more pronounced noise effects. Through these simulations, I gained a deeper understanding of how different noise models impact quantum computations while reinforcing foundational quantum computing concepts. I documented my observations in a Google document.


## Results

-  I observed that each of the four NISQ noise models produced different effects on the quantum circuits.
Amplitude damping introduced errors in simulations containing both the Hadamard (H) gate and the controlled-NOT (CX) gate.

- The depolarizing noise model and bit-flip noise primarily introduced errors in circuits containing the CX gate, while the Hadamard gate simulations remained largely unchanged.
 
-The phase-flip noise model did not produce observable errors in either the Hadamard or CX gate simulations under the tested conditions.

-I further investigated why each noise model produced different outcomes by examining how the underlying error mechanisms interact with specific quantum gates and quantum states. This helped me better understand the behavior of NISQ systems and the impact of different sources of quantum noise on circuit performance.

## Notes


