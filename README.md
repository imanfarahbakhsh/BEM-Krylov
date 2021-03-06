# BEM-Krylov
Solving the linear system of equations with nonsymmetric, dense, and typically ill-conditioned
matrices can be viewed as a key subject in BEM. Applying direct methods like Gauss elimination,
Gauss-Jordan, LU decomposition, and so on, will be computationally expensive for the
large scale system of equations and a rule of thumb shows that iterative methods become more
efficient. In the present code, some Krylov subspace methods as biconjugate
gradient (BiCG), conjugate gradient squared (CGS) and bi-conjugate gradient stabilized
(BiCGSTAB) have been used to solve the dense system of equations arisen from BEM for solving the Laplace equation.
