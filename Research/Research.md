---
layout: page
title: Research
permalink: /research/
---

Experimental and theoretical fluid mechanics at low Reynolds number.

---

## Sedimentation dynamics

How does a sphere settle through a viscous fluid near boundaries or in
stratified environments? I combine high-speed video tracking with scaling
analysis and curve fitting to extract terminal velocity behaviour and
transient power-law regimes.

*Methods: MATLAB image processing, edge detection, `regionprops`,
Savitzky–Golay smoothing, power-law and exponential fitting.*

---

## Elastic lubrication theory

When a thin elastic sheet is suspended near a rigid wall in a viscous flow,
the coupling between lubrication pressure and sheet deformation creates a
rich family of solutions. I study the governing BVP structure — originally
posed by Rallabandi (2021, *J. Fluid Mech.*) — and extensions to
pressure-driven configurations.

*Methods: MATLAB/Python BVP solvers, shooting method, `scipy.integrate`,
asymptotic matching.*

---

## Curved elastic structures in viscous fluids

Tape springs and elastic ribbons adopt curved rest shapes and exhibit
snap-through instabilities when bent. I study how such structures interact
with surrounding viscous flow — curling and deployment dynamics mediated
by fluid drag.

*Theory: Donnell shell theory, fold formation, ploy-region transition,
FSI at low Re.*

---

## Numerical methods

I have compared **oomph-lib** and **FEniCSx** for fluid–structure interaction
benchmarks, including the collapsible channel problem and its relation to
elastic lubrication physics.

---

All analysis code is shared openly on [GitHub](https://github.com/jishnume).
Papers are listed on the [Publications](../publications/) page.
