---
layout: page
title: Notes
permalink: /blog/
---

Working notes on theory, computation, and research practice.
Informal — written to think, not to impress.

---

**[Fold formation in tape springs: a Donnell shell perspective](Blog/fold-formation/)**
*2025-11 · theory*

The ploy region — the transition zone between the straight arm and the fold —
is where the interesting mechanics live. Notes on Donnell shell scaling for fold
width, the moment–curvature relation, and why the transition sharpens with
increasing pre-curvature.

---

**[Translating elastic lubrication BVPs from MATLAB to Python](Blog/lubrication-python/)**
*2025-09 · code*

Notes from translating the shooting-method code in Rallabandi (2021, *JFM*)
into Python. Key issues: scoping, `np.trapezoid`, `CubicSpline` ordering,
and adding an outer secant loop for the pressure-driven extension.

---

**[Building a sedimentation tracking pipeline in MATLAB](Blog/sedimentation-pipeline/)**
*2025-06 · code / experiment*

Tracking a settling sphere across video frames: edge detection, `imfill`,
`regionprops`, adaptive velocity extraction with `movstd` and
`findchangepts`, Savitzky–Golay smoothing, and publication-quality plots
with the Crameri colormap.

---

**[oomph-lib vs FEniCSx for FSI: a first comparison](Blog/fenics-oomph/)**
*2025-03 · numerics*

Both libraries can handle the collapsible channel benchmark. Notes on setup
friction, community support, and what each is good at when the physics is
elastic lubrication rather than large-deformation solid mechanics.
