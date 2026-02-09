---
layout: page
title: High Accuracy Nyström Discretization
description: Numerical methods for solving the exterior Helmholtz equation on Lipschitz domains
img: assets/img/example.png
importance: 2
category: research
---

Part of my research has been focused on solving the exterior Helmholtz equation in two-dimensional Lipschitz domains. The solution of these types of problems are usually formulated in terms of a layer-representation from potential theory, whereby one needs to solve an integral representation on the boundary of the Lipschitz domain for an unknown density that will inform the solution everywhere in the exterior of the domain. Few analytic layer-representation solutions exists, which means that a numerical scheme is needed to solve the Helmholtz equation on arbitrary Lipschitz domains. One such method that has been used in my research is a Nyström boundary discretization, coupled with a high order quadrature scheme that is capable of handling large wavenumbers.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/example.png" title="Nyström discretization example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    High-order Nyström method for solving the Helmholtz equation on complex geometries.
</div>
