# Hybrid Route Optimization using Quantum and Classical Algorithms

## Overview

This project explores route optimization using both quantum and classical approaches and compares their execution performance. A hybrid methodology was implemented by applying Grover’s quantum search algorithm alongside the classical Dijkstra shortest path algorithm to evaluate efficiency differences in solving routing problems.

The goal was to analyze whether quantum-inspired search techniques could provide advantages over traditional algorithms under simulated conditions.

---

## Objectives

* Implement route optimization using a classical algorithm (Dijkstra).
* Develop a quantum-based search model using Grover’s algorithm.
* Compare execution time and performance between the two approaches.
* Analyze efficiency under different input conditions.

---

## Technologies Used

* Python
* Qiskit
* Quantum Simulators
* Jupyter Notebook
* NumPy / Matplotlib (for analysis and visualization)

---

## Methodology

### Classical Approach

The classical implementation uses Dijkstra’s algorithm to compute the shortest path between nodes in a weighted graph. This method guarantees an optimal solution with deterministic execution time complexity.

### Quantum Approach

The quantum implementation applies Grover’s search algorithm principles to explore possible routing solutions more efficiently by reducing the search space probabilistically. The model was executed using quantum simulation environments provided by Qiskit.

---

## Performance Comparison

Execution time was recorded for both approaches under similar input conditions to evaluate performance differences.

Key observations:

* Classical algorithms performed consistently for smaller datasets.
* Quantum search demonstrated potential advantages in search space reduction under specific conditions.
* Simulation overhead impacts real-world execution performance.

---

## Results

Execution time comparison was performed between the classical and quantum implementations under similar input conditions.

* The classical approach using Dijkstra’s algorithm required approximately **42 seconds** to compute the optimal route.
* The quantum-based approach utilizing Grover’s algorithm completed the search in **less than 1 second** within the simulation environment.

These observations indicate a significant reduction in execution time using the quantum search method for the tested scenario, demonstrating the potential efficiency advantages of hybrid quantum-classical optimization techniques. However, performance may vary depending on problem size, hardware constraints, and simulation overhead.

