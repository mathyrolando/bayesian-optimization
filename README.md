# Bayesian Optimization from Scratch

Implementation of Bayesian optimization in Julia, built as part of a 
course project on optimization methods.

## What is Bayesian Optimization

A strategy for optimizing black-box functions that are expensive to evaluate.
Instead of trying every possible input, it builds a probabilistic model 
(a Gaussian process) to decide intelligently where to sample next.

## What this project implements

- Gaussian process regression as surrogate model
- Acquisition function (Expected Improvement)
- Optimization loop from scratch, without external BO libraries

## How to run

1. Install Julia (v1.x)
2. Install dependencies:
```julia
   using Pkg
   Pkg.instantiate()
```
3. Open and run `bayesian_optimization.ipynb`

## Results

[Una o dos líneas de qué observaste o qué función optimizaste]

## References

[Si usaste algún paper o recurso, lo ponés acá]
