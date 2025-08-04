# Deep learning for optimal switching control problems

This repository presents the results of a research internship carried out at the **LPSM (Laboratoire de Probabilités, Statistique et Modélisation)**, as part of the third year of study at **ESPCI Paris – PSL**.

## Project overview

The objective of this project is to numerically solve stochastic optimal switching problems with a finite time horizon, using deep learning techniques.

The approach combines:
- Discretization of the stochastic dynamics using the Euler–Maruyama scheme;
- Backward resolution of the discrete Bellman equation;
- Two neural networks:
  - One for approximating conditional expectations;
  - One for learning the optimal switching policy.

The method is tested on synthetic examples in dimension one and two, and compared to a finite-difference solver to assess its accuracy and robustness.
