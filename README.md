# COE745 — Linear Algebra, Optimization and Data-Driven Control

Mini-projects and research-oriented implementations developed for the graduate course **COE745**, covering topics in:

- Linear Algebra
- Optimization
- Least Squares Problems
- Graph-Based Modeling
- Numerical Linear Algebra
- Data-Driven Control
- Dynamical Systems
- Optimal Control

The repository combines rigorous mathematical derivations, geometric interpretations, and computational implementations using Python and scientific computing libraries.

---

# Projects

## M4 — Leveraging and Portfolio Risk

This project investigates portfolio allocation using affine combinations between risky assets and cash positions.

The project explores the geometric and statistical interpretation of portfolio allocation under different exposure strategies, including leverage, hedging, and short-selling.

### Main Topics

- Expected Return
- Portfolio Risk (Standard Deviation)
- Leveraging
- Short-Selling
- Hedging
- Affine Geometry of Portfolios
- Quadratic Risk Scaling
- Risk-Return Tradeoff
- Variance Interpretation as Signal Energy

---

## M8 — Graph-Based Localization via Least Squares

This project formulates and solves a graph localization problem using least squares optimization and Dirichlet energy concepts.

The objective is to estimate unknown node locations in a graph while minimizing geometric inconsistency between connected nodes.

### Main Topics

- Graph Laplacians
- Dirichlet Energy
- Least Squares Optimization
- Convex Optimization
- Geometric Interpretation
- Network Visualization
- Energy Minimization
- Graph Embedding

---

## A13 — Data-Driven Minimum-Energy Control for Linear Systems

Implementation and analysis based on the paper:

> Baggio, G., Katewa, V., & Pasqualetti, F.  
> *Data-Driven Minimum-Energy Controls for Linear Systems*  
> IEEE Control Systems Letters, 2019.

This project investigates how minimum-energy control inputs can be computed directly from experimental data without explicitly identifying the system matrices.

The work connects controllability theory, pseudoinverse-based optimization, subspace methods, and numerical linear algebra.

### Main Topics

- Controllability
- Controllability Gramian
- Moore-Penrose Pseudoinverse
- Subspace Methods
- Data-Driven Control
- Numerical Conditioning
- Spectral Properties
- Minimum-Energy Control
- Least Squares Geometry
- System Identification Concepts

---

# Technologies

The projects are implemented primarily in Python using scientific computing and control-oriented libraries.

### Main Libraries

- Python
- NumPy
- SciPy
- Matplotlib
- Python-Control
- NetworkX
- Jupyter Notebook

---

# Objectives

The main objective of this repository is to connect:

```math
Linear\ Algebra
\rightarrow
Optimization
\rightarrow
Geometry
\rightarrow
Dynamical\ Systems
\rightarrow
Data\text{-}Driven\ Control
```

through rigorous mathematical modeling, geometric interpretation, and computational implementation.

Particular emphasis is placed on:

- vector space interpretation;
- least squares formulations;
- pseudoinverse methods;
- spectral analysis;
- numerical conditioning;
- and data-driven approaches to dynamical systems.

---

# Mathematical Perspective

The repository emphasizes the interplay between:

- Geometry of vector spaces
- Affine and linear transformations
- Optimization under constraints
- Spectral decompositions
- Energy minimization
- Dynamical system representations
- Data-driven learning of control laws

Several projects explicitly connect classical linear algebra concepts with modern control and machine learning methodologies.

---

# References

## Linear Algebra

- Gilbert Strang — *Linear Algebra for Everyone*
- Gilbert Strang — *Introduction to Linear Algebra*

## Systems and Control

- Kailath — *Linear Systems*
- Zhou, Doyle & Glover — *Robust and Optimal Control*

## Generalized Inverses and Optimization

- Ben-Israel & Greville — *Generalized Inverses*
- Stephen Boyd — *Convex Optimization*

## Data-Driven Control

- Baggio et al. — *Data-Driven Minimum-Energy Controls for Linear Systems*

---

# Notes on AI Usage

AI tools were used as auxiliary support for:

- text organization,
- structural refinement,
- preliminary mathematical interpretation,
- and formatting assistance.

All mathematical derivations, implementations, numerical validations, analyses, and interpretations were reviewed, verified, and developed by the authors.

---

# Authors

| Name | Academic Position |
|---|---|
| Bismark Brandi Sigolo | M.Sc. Student in Robotics Engineering |
| Jonas Tobias Ulbrich | Ph.D. Student in Robotics Engineering |
| Rickson Gomes Monteiro | M.Sc. Student in Robotics Engineering |

---

# Institution

Federal University of Rio de Janeiro (UFRJ)  
Graduate Program in Robotics Engineering