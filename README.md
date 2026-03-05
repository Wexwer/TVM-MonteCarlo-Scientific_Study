# Time Value of Money Under Uncertainty

## Overview

This project explores how uncertainty affects project valuation using
Monte Carlo simulation and mathematical modeling.

Future cash flows are treated as random variables, allowing us to analyze
the full distribution of Net Present Value (NPV) rather than a single estimate.

The project combines concepts from:

- Linear Algebra
- Probability Theory
- Statistics
- Numerical Simulation

## Key Ideas

The Net Present Value can be written as:

$ NPV = wᵀ CF $

where:

- CF is the vector of cash flows
- w is the vector of discount weights

When cash flows are random variables with covariance matrix Σ, the variance
of NPV becomes:

$ Var(NPV) = wᵀ Σ w $

This result is validated using Monte Carlo simulation.

## Main Components

### The project includes:

1. Deterministic Time Value of Money model
2. Monte Carlo simulation with triangular distributions
3. Statistical analysis of NPV distribution
4. Convergence analysis
5. Linear algebra formulation of risk
6. Correlated cash flow simulation
7. Model validation and robustness checks

