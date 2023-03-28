# Profile

*Numerical Simulation* of Spin Chain

Julia: https://github.com/yujitach/ed (collaboration) and https://github.com/yinhslin/ed (personal)

C++: https://github.com/tzu-chen/Chain

"Numerical Evidence for a Haagerup Conformal Field Theory": https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.128.231603

Summary: Compute the spectrum of a special (Haagerup) quantum spin chain, and examine scale (conformal) invariance in the long chain limit.

Key techniques: (1) Lanczos algorithm for finding the smallest eigenvalues of matrix, (2) Factorization of dense matrix operators into series of sparse matrix operators, (3) Density matrix renormalization group (DMRG) which approximates the eigenvectors by matrix products.

#

*Semidefinite Optimization* and *Monte Carlo* Simulation of Lattice Spin System

"Bootstrapping the Ising Model on the Lattice": https://arxiv.org/abs/2206.12538

Summary: Constrain correlation functions by performing semidefinite optimization, and compare with Monte Carlo. Close connection between spin system and random walk.

Key techniques: (1) Semidefinite programming, (2) Monte Carlo (Metropolis), (3) QR decomposition (numerically stable Gram-Schmidt).

#

*Semidefinite Optimization* Refined by Category Theory

Mathematica: https://github.com/yinhslin/catboot

"Modular Bootstrap Revisited": https://link.springer.com/article/10.1007/JHEP09(2018)061

"Bootstrapping Non-Invertible Symmetries" https://arxiv.org/abs/2302.13900

Summary: 

Key techniques: (1) Semidefinite programming, (2) Category theory (fusion and modular tensor categories).

#

Large-Scale Analytic Computation

Mathematica and Julia: https://github.com/yinhslin/bps-counting-code

"Words to Describe a Black Hole" https://link.springer.com/article/10.1007/JHEP02(2023)109

Summary: Reformulate the action of a non-linear operator into a matrix operator on large (up to 10^5 dimensional) vector spaces, compute the nullspace and column space of the matrix to find vectors describing black holes.

Key techcniques: (1) QR decomposition (numerically stable Gram-Schmidt), (2) Combinatorics in building products of matrix traces, (3) Non-commutative algebraic manipulations.
