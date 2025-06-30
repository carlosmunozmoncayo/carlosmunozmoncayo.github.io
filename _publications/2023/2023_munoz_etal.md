---
title:          " Comparative Study of Iterative Riemann Solvers for the Shallow Water and Euler Equations"
date:           2023-05-12 00:01:00 +0800
selected:       true
pub:            "Communications in Applied Mathematics and Computational Science"
pub_date:       "2023"
abstract: >-
  We investigate the achievable efficiency of exact solvers for the Riemann problem for two systems of first-order hyperbolic PDEs: the shallow water equations and the Euler equations of compressible gas dynamics. Many approximate solvers have been developed for these systems; exact solution algorithms have received less attention because the computation of the exact solution typically requires an iterative solution of algebraic equations, which can be expensive or unreliable. We investigate a range of iterative algorithms and initial guesses. In addition to existing algorithms, we propose simple new algorithms that are guaranteed to converge and to remain in the range of physically admissible values at all iterations. We apply the existing and new iterative schemes to an ensemble of test Riemann problems. For the shallow water equations, we find that Newton’s method with a simple modification converges quickly and reliably. For the Euler equations we obtain similar results; however, when the required precision is high, a combination of Ostrowski and Newton iterations converges faster. These solvers are slower than standard approximate solvers like Roe and HLLE, but come within a factor of two in speed. We also provide a preliminary comparison of the accuracy of a finite volume discretization using an exact solver versus standard approximate solvers.
# cover:          /assets/images/covers/2023_mayorga_etal.png 
authors:
- Carlos Muñoz-Moncayo#
- David I. Ketcheson
- Manuel Quezada de Luna
links:
  Paper: https://msp.org/camcos/2023/18-1/p05.xhtml
---