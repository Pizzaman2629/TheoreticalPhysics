# Theoretical Physics

This repository acts as a portfolio documenting self-studies, simulations and research projects for theoretical/computational physics.

> 📝 **Note:** For self-studies, this repository only contains the topics that were covered on my tablet and not on paper.

---

## 📌 Table of Contents
* [🔬 Research Projects](#-research-projects)
  * [Feynman Integrals using PINNs](#feynman-integrals-using-pinns)
* [📽️ Quick Glimpse of Simulations](#️-quick-glimpse-of-simulations)
  * [OSIRIS PIC Simulations](#osiris-pic-simulations)
  * [PINNs for Fluids & FIs](#pinns-for-fluid-simulations--feynman-integrals)
  * [CFD Simulations](#cfd-simulations)
* [📚 Central Documents for Self-Study Evidence](#-central-documents-for-self-study-evidence)
  * [1.) Quantum Field Theory](#-1-quantum-field-theory)
  * [2.) General Relativity](#-2-general-relativity)
  * [3.) Plasma Physics](#-3-plasma-physics)
  * [4.) String Theory](#-4-string-theory)

---

## 🔬 Research Projects

### Feynman Integrals using PINNs
This is an **ongoing** research project focused on solving Feynman Integrals (FIs) using Physics-Informed Neural Networks (PINNs). 

**Primary Document:** [`Ongoing Literature Review for FI-PINNs.pdf`](./Ongoing%20Literature%20Review%20for%20FI-PINNs.pdf)  
This document serves as a literature review and manuscript for the project. It is updated regularly and currently covers:
* **Graph Theory for FIs:** Basics of graph theory including Spanning trees and forests.
* **Reduction Techniques:** Integration by Parts (IBPs) and Laporta's Algorithm.
* **Future Work:** Algebraic Geometry, Lie Groups, proofs for Master Integrals, Matrix-Tree theorem for Laplacians, and alternative FI representations.

<p align="center">
  <img width="800" alt="Feynman Integral Spanning Trees" src="https://github.com/user-attachments/assets/a344d753-3939-4a3a-a36e-14c0dce0a8cb" />
  <br><em>Spanning Trees and Forests for a Feynman Integral. Taken from Weinzierl's Review.</em>
</p>

---

## 📽️ Quick Glimpse of Simulations

### OSIRIS PIC Simulations
<img width="600" alt="dispersion_relation_2D_Fine" src="https://github.com/user-attachments/assets/9b3d7017-8344-42c7-8031-1bd3a5afca4f" />

This simulation was run with a fine PIC mesh as part of a mesh-independence study to investigate the Weibel instability in 2D. The full documentation for this simulation project is located in the [Plasma Physics Folder](./Plasma/).

### PINNs for Fluid Simulations & Feynman Integrals
| Fluid Flow Fronts | Feynman Integral Reproduction |
| :--- | :--- |
| ![flow_fronts](https://github.com/user-attachments/assets/ad1c9523-c33b-43b3-bcad-296bd8ee85ae) | <img width="400" src="https://github.com/user-attachments/assets/da6f065d-12da-45f4-857e-bf9371b6349c" /> |
| This is a GIF of flow-fronts propagating as predicted by the PINN model. It is part of a manuscript currently being written up for peer-review so the documentation for this will be added as soon as that is complete. | This is a figure from our attempts at reproducing the results from [this paper](https://link.springer.com/article/10.1007/JHEP07(2024)124) for the massless box case. These were later proved successful and were taken as an initial starter for ongoing research on simulating Feynman Integrals with PINNs. |

### CFD Simulations
| Rocket Aerodynamics | Formula Student Cooling |
| :--- | :--- |
| <img width="500" src="https://github.com/user-attachments/assets/7aeca18f-7a97-4ca1-8f11-5b345567783e" /> | <img width="350" src="https://github.com/user-attachments/assets/ca369811-9467-45b8-9c89-cd5db42e6e50" /> |
| This was a 3D volume render of the flow around a rocket with the density visualized. Shockwaves as a feature of compressible flow are clearly visible. | This was a render of y+ values which were sustainably under 5 for turbulent flow modelling in the cooling jacket of a Formula Student car. |

---

## 📚 Central Documents for Self-Study Evidence

### ⚛️ 1.) Quantum Field Theory
**File:** [`QFT/Sredniki QFT Solutions.pdf`](./QFT/Sredniki%20QFT%20Solutions.pdf)

Contains all handwritten solutions to Part 1 of Sredniki which covers feynman diagrams, loop corrections, renormalization, effective field theory, discrete and continuous symmetries, spontaneous symmetry breaking for the scalar field.

### 🌌 2.) General Relativity
**File:** [`GR/LearningDiffGeoGR.pdf`](./GR/LearningDiffGeoGR.pdf)

Comprehensive walkthrough of all the differential geometry needed for general relativity. Talks about manifolds, tensors, pull-backs, etc. Ends by deriving Einstein's equations and analyzing different spacetimes through Penrose diagrams and observing gravity-matter field interactions. 

### ⚡ 3.) Plasma Physics
**Folder:** [`Plasma/`](./Plasma/)

This folder has smaller notes for all the topics I covered on my tablet, there is a decent bit of MHD and Force Balance analysis for fusion.

### 🧶 4.) String Theory
**Folder:** [`String Theory/`](./String%20Theory/)

This is my biggest self-study focus right now. Currently it spans the first 2/3 chapters of Tong's notes and 1 chapter of Polchinski with handwritten notes and perspective on certain concepts like the Polyakov Action and Lightcone quantization.

$$S_P = -\frac{1}{4\pi\alpha'} \int d^2\sigma \sqrt{-h} h^{ab} \partial_a X^\mu \partial_b X^\nu \eta_{\mu\nu}$$
