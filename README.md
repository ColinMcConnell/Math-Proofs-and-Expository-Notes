# Math Proofs and Expository Notes
**Colin McConnell** · Independent study, 2026

Proofs and expository notes written while teaching myself undergraduate mathematics through MIT OpenCourseWare and textbooks, including multivariable calculus, linear algebra, differential equations, real analysis, complex analysis, and abstract algebra.

*The mathematical arguments are my own; I used AI tools to help with LaTeX typesetting and organizing the final write-ups.*

## Contents

### Real Analysis

**1. Rearrangements of the Alternating Harmonic Series**
A proof that the alternating harmonic series 1 − 1/2 + 1/3 − 1/4 + ⋯ can be rearranged to converge to any real number (a case of the Riemann rearrangement theorem). I worked out this proof on my own before reading the textbook's version in Stephen Abbott's *Understanding Analysis*, Chapter 2.
- [Proof (PDF)](Riemann_Rearrangement_Theorem.pdf)

**2. Uniformly Lipschitz Sequences: Pointwise Convergence Implies Uniform Convergence**
If functions on [a, b] share a common Lipschitz constant, pointwise convergence is automatically uniform and the limit is Lipschitz; a counterexample shows both conclusions fail without the common constant. *Source: MIT OCW 18.100B (Spring 2025), Problem Set 10, Problem 5.*
- [Proof (PDF)](Uniformly_Lipschitz_Convergence.pdf)

**3. Square-Summable Sequences**
Constructs the space of square-summable sequences, proves the triangle inequality, and shows the standard basis vectors have no convergent subsequence, so a closed, bounded set need not be compact in infinite dimensions. *Source: MIT OCW 18.100B (Spring 2025), Problem Set 7, Problems 1–2.*
- [Proof (PDF)](Square_Summable_Sequences.pdf)

### Complex Analysis

**4. When f² Stays Near 1, the Real Part of f Has Constant Sign**
If f is analytic on a region and |f² − 1| < 1, then Re f is either positive throughout or negative throughout, using continuity and connectedness. *Source: Ahlfors, Complex Analysis, 3rd ed., p. 72, Ex. 3 (MIT OCW 18.112).*
- [Proof (PDF)](Real_Part_Constant_Sign.pdf)

**5. A Logarithmic Integral by Residues**
Shows ∫₀^∞ (log x)/(1 + x²) dx = 0 using a branch of the logarithm and an indented semicircular contour, with the imaginary part recovering ∫₀^∞ dx/(1 + x²) = π/2 as a check. *Source: Ahlfors, Complex Analysis, 3rd ed., p. 161, Ex. 3(h) (MIT OCW 18.112).*
- [Solution (PDF)](Log_Integral_Residues.pdf)

### Algebra

**6. The Discrete Dirichlet Problem**
Proves a maximum principle for discrete harmonic functions on a lattice and uses it to show that the discrete Dirichlet problem always has exactly one solution, a discrete analogue of determining an electrostatic potential from its boundary values. *Source: Artin, Algebra, 2nd ed., Ch. 1, Ex. M.11 (MIT OCW 18.701).*
- [Proof (PDF)](Discrete_Dirichlet_Problem.pdf)
