# Lab reports and computing coursework

Selected experimental and computational work from my MPhys Physics degree at the University of Bath. Candidate numbers redacted.

---

### [Measurement of the Linear Thermal Expansion Coefficient of Five Metals by a Capacitance Method](Measurement of the Linear Thermal Expansion Coefficient of Five Metals by a Capacitance Method.pdf)
*March 2026*

A 50 cm rod expands roughly 0.5 mm over a 50 °C rise, too small for a mechanical gauge. A parallel-plate capacitor was used as the displacement sensor, calibrated against 1/C rather than C so the relationship is linear and admits least-squares fitting. Resolution was approximately 8.3 μm.

Steel agreed with literature to 0.3σ; copper, aluminium and brass showed offsets of 3.6 to 6σ. Because those offsets varied in sign as well as magnitude, a single fixed offset such as plate tilt could not explain them, pointing instead to non-uniform heating along the rod — which also explains steel's agreement, having the lowest thermal conductivity of the five.

The unknown rod was identified as tin on the combined evidence of expansion coefficient, density and appearance, rather than on the expansion coefficient alone.

---

### [Measuring the Hubble Constant](Measuring%20the%20Hubble%20Constant.ipynb)
*Python notebook*

Measuring the local Hubble constant by building the distance ladder from scratch: calibrating the Cepheid period–luminosity relation on HST observations of LMC variables, using galaxies hosting both Cepheids and Type Ia supernovae to fix the supernova absolute magnitude, then fitting a Hubble diagram to a large supernova sample.

The fit over supernovae within 400 Mpc gives H₀ = 70.56 ± 0.18 km/s/Mpc, sitting between the Riess et al. (2022) and Planck (2020) values.

Repeating the fit over 400–4000 Mpc instead gives 57.69 ± 0.15 — a large shift from a change in sample selection alone, and the most interesting result in the notebook. It shows the inferred value depends heavily on which part of the ladder is used, and that a quoted statistical uncertainty of ±0.18 does not reflect the true spread of plausible answers.

---

### [Optics Computing Coursework](Optics%20Computing%20Coursework.pdf)
*April 2026*

Numerical methods in Python without library shortcuts. Wien's displacement law solved by Newton-Raphson with a central-difference derivative, converging in four iterations to give the displacement constant as 2.898 × 10⁻³ m·K. Bessel functions evaluated by the extended trapezium rule and validated against known values before use. The Airy diffraction pattern for an f/10 lens computed from those, with the r = 0 singularity handled by the analytical limit 2J₁(x)/x → 1.

---

### [Time of Contact in an Elastic Collision](Time%20of%20Contact%20in%20an%20Elastic%20Collision.pdf)
*Poster · joint work with Hannah Le Pelley*

Contact time between colliding steel spheres measured using a Newton's cradle rig with an electrical contact circuit and a digital storage oscilloscope. Log-log fitting gave an exponent of −0.204 ± 0.023 against Hertz's predicted −0.200, with prefactors within 9.4% and 6.6% of theory.

---

These are coursework submissions, included as examples of experimental method, uncertainty analysis and scientific writing.
