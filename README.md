<img src="assets/flow.svg" width="100%" alt="NACA 4412 at 7 degrees angle of attack, streamlines flowing past it">

# Lukas Beck

Aerodynamics and CFD for solar cars.

```
Studies  →  BSc Mechanical Engineering, ETH Zürich · 5th semester
Focus    →  Aerodynamics → CFD · aeroshell design / surface modelling
Team     →  aCentauri Solar Racing — Aerodynamics subteam
Compute  →  ANSYS Fluent on the ETH Euler cluster (Slurm)
Tools    →  Python · Siemens NX · PyAnsys
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ansys Fluent](https://img.shields.io/badge/ANSYS_Fluent-FFB71B?style=flat-square&logoColor=black)
![PyFluent](https://img.shields.io/badge/PyAnsys_%2F_PyFluent-CC4B00?style=flat-square)
![Siemens NX](https://img.shields.io/badge/Siemens_NX-009999?style=flat-square&logo=siemens&logoColor=white)
![CFD](https://img.shields.io/badge/CFD_%7C_RANS-1a4d6d?style=flat-square)
![Slurm](https://img.shields.io/badge/Slurm_%7C_HPC-2C5F8A?style=flat-square)

---

## What I work on

```
Aeroshell design
  Surface modelling of the solar car body, with drag and
  crosswind behaviour as the design driver.

CFD and pipeline workflow
  RANS simulations on the ETH Euler cluster, and the tooling
  around them: mesh and solver setup, job submission, force
  report evaluation. Most of the effort goes into making that
  loop faster and more reproducible to run.
```

<img src="assets/residuals.svg" width="460" alt="Solver residuals converging over iterations">

---

## Repositories

| Repo | What it is |
|---|---|
| `aero_cfd_automation` | AirWrap — the aCentauri CFD pipeline. Workflow optimisation with PyAnsys / PyFluent. |
| `FinESC` | Real-time simulator for extremum-seeking control of the morphing fin, without a wind sensor. |
| `NXScripts` | NXOpen journal that builds NACA 4-digit profiles inside Siemens NX. |
