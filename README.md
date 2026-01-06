This repository contains the complete Python code used for all numerical analyses and figures in the manuscript
“A minimal dynamical model linking early embryonic asymmetry to hemispheric lateralization.”

The code implements a minimal nonlinear dynamical system describing coupled hemispheric developmental dynamics with weak intrinsic asymmetry and reciprocal inhibition. All simulations are fully self-contained and require no external datasets.

Contents

analysis.py
Runs all simulations reported in the paper, computes summary statistics (mean ± SD, N=100), and reproduces Figures 2 and 3.

Key outputs

Time courses of L(t), R(t), and dominance index D(t) (Figure 2)

Stability analysis of the symmetric internal equilibrium and critical coupling βc = α/3 (Figure 3)

Batch statistics for bias, noise robustness, and convergence behavior (Results Section)

Requirements

Python ≥ 3.8

NumPy

Matplotlib

Usage
