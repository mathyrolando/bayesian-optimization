# Bayesian Optimization from Scratch

Implementation of Bayesian Optimization in Julia, built from 
the ground up without external BO libraries.

## What this project implements

- Gaussian Process regression with RBF (squared exponential) kernel
- Analytic gradient of the negative marginal log-likelihood (NLML)
- Hyperparameter optimization via L-BFGS with multiple restarts
- Expected Improvement acquisition function
- Full optimization loop benchmarked on standard test functions

## Why from scratch

The goal was to understand every component deeply rather than 
calling a library. This meant deriving the NLML gradient analytically
and implementing Cholesky-based inference for numerical stability.

## How to run

1. Install Julia (v1.x)
2. Open and run `Tp-final-optimizacion.ipynb`

## References

[Papers o recursos que usaste]
