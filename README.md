# Profile

*Numerical Simulation* of Spin Chain

Julia: https://github.com/yujitach/ed (collaboration) and https://github.com/yinhslin/ed (personal)

C++: https://github.com/tzu-chen/Chain

"Numerical Evidence for a Haagerup Conformal Field Theory": https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.128.231603

Summary: Compute the spectrum of a special (Haagerup) quantum spin chain, and examine scale (conformal) invariance in the long chain limit.

Key techniques: (1) Lanczos algorithm for finding the smallest eigenvalues of matrices, (2) Factorization of dense matrix operators into products of sparse matrix operators, (3) Density matrix renormalization group (DMRG) to approximate eigenvectors by "matrix product states".

#

*Monte Carlo* Simulation and *Semidefinite Optimization* of Lattice Spin System (Close Connection to *Random Walk*)

"Bootstrapping the Ising Model on the Lattice": https://arxiv.org/abs/2206.12538

Summary: Bound correlation functions by performing semidefinite optimization, and compare with Monte Carlo.

Key techniques: (1) Monte Carlo (Metropolis) simulation of correlation functions, (2) Semidefinite programming for deriving rigorous bounds, (3) QR decomposition (numerically stable Gram-Schmidt) to solve large systems of overly-constrained linear equations.

#

*Semidefinite Optimization* of Low-Dimensional System using *Category Theory*

Mathematica: https://github.com/yinhslin/catboot

"Modular Bootstrap Revisited": https://link.springer.com/article/10.1007/JHEP09(2018)061

"Bootstrapping Non-Invertible Symmetries" https://arxiv.org/abs/2302.13900

Summary: Bound spectra of low-dimensional scale-invariant (conformal) systems using semidefinite optimization together with the underlying categorical structure described by fusion and modular tensor categories.

Key techniques: (1) Semidefinite programming for deriving rigorous bounds, (2) Category theory describing symmetries of low-dimensional systems.

#

Large-Scale Analytic Computation

Mathematica and Julia: https://github.com/yinhslin/bps-counting-code

"Words to Describe a Black Hole" https://link.springer.com/article/10.1007/JHEP02(2023)109

Summary: Reformulate the action of a non-linear operator into a matrix operator on large (up to 10^5 dimensional) vector spaces, compute the nullspace and column space of the matrix to find vectors describing black holes.

Key techcniques: (1) QR decomposition (numerically stable Gram-Schmidt) to reveal the rank of large matrices, (2) Heavy combinatorics in building products of matrix traces, while taking into account cyclicity and trace relations, (3) Non-commutative algebraic manipulations.
