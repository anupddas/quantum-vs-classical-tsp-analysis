# Comparative Performance Analysis of Quantum vs Classical Algorithms for the Travelling Salesman Problem

## Overview

This repository presents an experimental comparison between classical optimization techniques and quantum computing approaches for solving the Travelling Salesman Problem (TSP). The work focuses on implementation, performance evaluation, and practical limitations of both paradigms using Python and Qiskit.

The project was developed as part of an academic study to explore whether current quantum optimization methods provide measurable advantages over classical algorithms for combinatorial optimization problems.

---

## Problem Statement

The Travelling Salesman Problem (TSP) is a well-known NP-Hard problem that aims to determine the shortest possible route visiting each city exactly once and returning to the origin city. Due to its computational complexity, TSP is frequently used as a benchmark for optimization algorithms.

This project investigates:

* Performance differences between classical and quantum approaches
* Solution quality comparison
* Scalability limitations
* Practical feasibility of quantum optimization

---

## Methodology

The project follows a simple experimental workflow:

1. Generate TSP graph instances
2. Solve using classical algorithms
3. Solve using quantum optimization methods
4. Compare execution time and solution quality
5. Analyze limitations and observations

---

## Implemented Approaches

### Classical Methods
* Brute Force Search
* Dynamic Programming (Held–Karp approach)
* Greedy / Nearest Neighbor heuristic

### Quantum Methods
* Quantum Approximate Optimization Algorithm (QAOA)
* Quatntum Annealing

---

## Technology Stack

**Language**

* Python

**Libraries**

* Qiskit SDK
* NumPy
* NetworkX
* Matplotlib
* SciPy
* Ocean SDK

**Tools**

* Jupyter Notebook
* IBM Quantum Simulator
* Git version control
* DWave Quantum
---

## Repository Structure
quantum-vs-classical-tsp-analysis/
│
├── Analysis/
│
├── Codebase/Core implementations of classical and quantum TSP algorithms.
│
├── LICENSE
│
└── README.md

(Structure may evolve as experiments expand.)

---

## Installation

### Clone the repository


git clone https://github.com/anupddas/quantum-vs-classical-tsp-analysis.git

cd quantum-vs-classical-tsp-analysis


### Create virtual environment (recommended)


python -m venv venv

Windows:
venv\Scripts\activate

Linux/Mac:
source venv/bin/activate


### Install dependencies


pip install qiskit numpy networkx matplotlib scipy jupyter


---

## Running the Project

Open the analysis notebooks:


jupyter notebook


Then run the notebooks inside the **Analysis** directory to reproduce the experiments.

---

## Evaluation Parameters

The comparison focuses on:

* Execution time
* Path optimality
* Computational complexity
* Scalability with node increase
* Practical execution constraints

---

## Key Observations

General trends observed during experimentation:

* Classical algorithms remain more practical for small and medium problem sizes
* Quantum approaches require significant preprocessing and mapping overhead
* Current quantum advantage is limited by hardware and noise constraints
* Hybrid quantum-classical approaches appear promising for future research

---

## Limitations

* Experiments performed primarily on simulators
* Limited graph sizes due to quantum circuit constraints
* Noise models not fully explored
* No real quantum hardware benchmarking yet

---

## Future Work

Possible extensions:

* Testing on IBM Quantum hardware
* Adding metaheuristic algorithms (Genetic Algorithm, Simulated Annealing)
* Hybrid optimization workflows
* Larger dataset benchmarking
* Error mitigation studies

---

## Academic Relevance

This project demonstrates practical exposure to:

* Quantum computing fundamentals
* Combinatorial optimization
* Algorithm analysis
* Experimental comparison methodology
* Scientific computing workflows

---

## Author

Anup Das  
B.Tech Computer Science Engineering

GitHub:
https://github.com/anupddas

---

## License

This project is licensed under the GPL-3.0 License. See the LICENSE file for details.

---

## Notes

This repository is intended for educational and research purposes. Results should be interpreted in the context of current quantum computing limitations.
