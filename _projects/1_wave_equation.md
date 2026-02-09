---
layout: page
title: Time Domain Scattering of the Wave Equation
description: Convolution Quadrature methods for solving time-dependent scattering problems
img: assets/img/NJIT.gif
importance: 1
category: research
---

Another project which ties into the section below, is solving the exterior time-dependent scattering problem on a Lipshitz domain. This problem can be formulated as solving the exterior wave equation, which has typically been done by an integral formulation of a retarded potential.

Another, more robust, way to solve this problem is through a procedure known as convolution quadrature (CQ). The beautiful aspect of CQ is that it transforms a time-dependent wave equation into many decoupled time harmonic, frequency dependent, Helmholtz problems. Meaning that all of the tools and theory of the section below can be used in solving time dependent scattering. The novelty here is in combining the Nyström collocation scheme with the CQ method, yielding a very fast and accurate solution in both time and space.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/NJIT.gif" title="Wave equation scattering simulation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Time-domain scattering simulation using convolution quadrature methods.
</div>
