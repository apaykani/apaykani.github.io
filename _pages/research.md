---
layout: page
title: Research
permalink: /research/
description: Four connected themes at the interface of combustion science and machine learning.
nav: true
nav_order: 2
---

Our research advances data-driven and physics-based methods for future energy conversion and propulsion systems in four themes:

---

## Reactive Flows & Combustion Modelling

Combustion still delivers most of the world's transport energy, and it will remain central to aviation, shipping and heavy transport for decades. Making that combustion clean requires the ability to predict it — accurately, and at a computational cost that permits design iteration.

We develop high-fidelity and reduced-order modelling frameworks for chemically reactive flows, with a focus on the coupling between turbulence, chemistry and radiation. Recent work has addressed radiative corrections to laminar flame-speed determination in spherically propagating flames, quasi-dimensional combustion modelling for computational optimisation of fuel blends, and non-equilibrium reactive plasmas as a route to combustion enhancement.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research_combustion.jpg" title="Reactive flow simulation" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Add a representative figure at <code>assets/img/research_combustion.jpg</code>.
</div>

**Representative work:** Faghih *et al.*, *Combustion and Flame* (2023) · Paykani *et al.*, *Fuel* (2021)

---

## Scientific Machine Learning for Chemical Kinetics

Detailed chemical mechanisms are the computational bottleneck in reacting flow simulation. Stiff kinetics can consume the overwhelming majority of the runtime in a large-eddy simulation, which is why most industrial combustion design still relies on drastically simplified chemistry.

We build machine learning surrogates that integrate the chemical source term directly, and critically that know when they are wrong. Our work spans Gaussian-process frameworks for probabilistic source-term integration, on-the-fly uncertainty-aware deep ensembles that adapt during simulation, and deep neural operators for stiff kinetics. The emphasis throughout is on structure preservation and calibrated uncertainty rather than raw regression accuracy: a surrogate that silently extrapolates is worse than no surrogate at all.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research_sciml.jpg" title="Uncertainty-aware surrogate" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

**Representative work:** Üstün & Paykani, *Proceedings of the Combustion Institute* (2025) · Üstün & Paykani, *International Journal of Hydrogen Energy* (2024)

---

## Sustainable Fuels: Hydrogen & Ammonia

Ammonia and hydrogen are the leading zero-carbon energy carriers for heavy transport, but both present hard combustion problems — ammonia burns slowly and produces NO<sub>x</sub>; hydrogen burns fast and is prone to instability. Blends offer a path through, and predicting their behaviour is a prerequisite for engine and turbine design.

We characterise and model the combustion of ammonia, hydrogen, methane and syngas blends, combining chemical kinetic analysis with data-driven prediction of laminar burning velocity across wide composition and thermodynamic ranges. Current work extends to liquid-ammonia direct-injection spray characteristics, in partnership with Kyushu University, and to the exhaust and contrail implications of cracked ammonia in aviation.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research_fuels.jpg" title="Ammonia/hydrogen flames" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

**Representative work:** Mashruk *et al.*, *Energy & Fuels* (2024) · Üstün *et al.*, *Fuel* (2024) · Paykani *et al.*, *Progress in Energy and Combustion Science* (2022)

---

## Thermal Management of Electric Machines

Electric traction motors are thermally limited, not electromagnetically limited. Power density in EV powertrains is constrained by how quickly heat can be removed from the windings — which makes cooling design a first-order determinant of vehicle performance.

We investigate direct oil-jet cooling of hairpin end-windings using combined CFD and experimental methods, including multi-nozzle impinging-jet configurations and parametric optimisation of nozzle geometry, flow rate and impingement angle. The work is conducted with industrial partners and has produced validated design guidance for next-generation traction motors.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/research_thermal.jpg" title="Oil-jet cooling of hairpin windings" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

**Representative work:** Maddumage *et al.*, *IEEE Transactions on Transportation Electrification* (2025) · Maddumage *et al.*, *Applied Thermal Engineering* (2025)
