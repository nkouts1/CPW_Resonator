# CPW resonator on Si with Al metallization (50 Ω target)

This repository contains a short report, a slide deck, and a COMSOL model for the design and simulation of a coplanar waveguide (CPW) quarter-wave resonator on high-resistivity silicon with aluminum metallization, targeting ~50 Ω characteristic impedance.

## Contents
- `docs/CPW_resonator.pdf` — report (theory, fabrication flow, and COMSOL setup/results).
- `docs/CPW_resonator-presentation.pdf` — presentation slides.
- `comsol/cpw_numeric_tem_port.mph` — COMSOL Multiphysics model file (numeric TEM ports).

## Design summary (from the report)
- Substrate: high-resistivity Si, \(\varepsilon_r\approx 11.45\).
- CPW geometry used in simulations: \(W=250\,\mu m\), \(S=150\,\mu m\), substrate thickness 400 \(\mu m\).
- Quarter-wave resonator length: \(L=3.0\,mm\) (targeting ~10 GHz with \(\varepsilon_{eff}\approx 6.2\)).
- Simulated impedance from numeric port: \(Z_0\approx 51.3\,\Omega\) (close to 50 Ω).

## Reproducing / opening
1. Open `comsol/cpw_numeric_tem_port.mph` in COMSOL Multiphysics.
2. Inspect the electromagnetic waves / frequency domain and eigenfrequency studies.
3. Run the numeric port TEM field analysis to extract \(Z_0\) and S-parameters.

## Citation
If you use this repository in academic work, consider citing it via the included `CITATION.cff`.

## Author
Nikos Koutsopoulos (June 2025)
