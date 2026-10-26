# CFD-ThermalHydraulics
LES study of mass &amp; heat transfer resolution for large-scale fire propagation on solid fuel plates — Internship at ASNR / CEA Cadarache
# Study of the resolution of mass and heat transfer for large-scale simulation of fire propagation on solid fuel plates

**Internship Report**  
ASNR Fire and Explosion Laboratory (LIE), CEA Cadarache  

**Author:** Shampreethi Satish Prabu  
**Supervisor:** Germain Boyer  
**Period:** 09/03/2026 – 08/09/2026

## Abstract
This work establishes numerical resolution requirements and grid-fidelity guidelines for Large Eddy Simulation of wall-bounded buoyant reactive flows. Starting from non-reactive Differentially Heated Vertical Channel (DHVC) benchmarks at Rayleigh numbers up to 2 × 10⁷, a comprehensive sensitivity matrix is constructed (grid refinement, wall stretching, convective schemes, SGS models). The validated methodology is then applied to a turbulent vertical wall fire configuration, with detailed analysis of boundary-layer dynamics in viscous units (y⁺), heat-flux partitioning, and comparison against experimental data.

## Key Results
- The WALE SGS model provides superior near-wall behaviour compared with classical Smagorinsky formulations.
- Clear recommendations are given on core grid size (Δs), wall stretching (r_wall), and y⁺ targets for reliable prediction of convective and total wall heat flux.
- Practical LES quality metrics (Pope energy resolution ≥ 0.95, Celik Δ/η_K ≤ 25) were achieved on affordable meshes.

## Contents of this repository
- Full internship report (PDF)


## Keywords
Large Eddy Simulation • Buoyant boundary layers • Vertical wall fires • Near-wall heat transfer • Grid convergence • Nuclear fire safety • CALIF³S

---
*Internship carried out at the Fire and Explosion Laboratory (LIE), ASNR / CEA Cadarache.*
