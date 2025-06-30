---
title:          " Efficient Absorbing Boundary Conditions for Conservation Laws: Application to the Piston Problem of Gas Dynamics"
date:           2024-05-01 00:01:00 +0800
selected:       true
pub:            "arXiv preprint"
pub_date:       "2024"
abstract: >-
  In this work, we address the imposition of outflow boundary conditions for one-dimensional conservation laws. While a highly accurate numerical solution can be obtained in the interior of the domain, boundary discretization can lead to unphysical reflections. We investigate and implement some classes of relaxation methods and far-field operators to deal with this problem without significantly increasing the size of the computational domain. Relations are established between these techniques, and extensions of them are explored. In particular, we introduce a simple and robust relaxation method with a matrix-valued weight function that selectively absorbs outgoing waves. As a challenging model problem, we consider the Lagrangian formulation of the Euler equations for an isotropic gas with inflow boundary conditions determined by an oscillating piston.
cover:          /assets/images/covers/2024_munoz.png
authors:
- Carlos Muñoz-Moncayo
links:
  Code: https://github.com/carlosmunozmoncayo/abcs-piston
  Paper: https://arxiv.org/pdf/2405.11588
---