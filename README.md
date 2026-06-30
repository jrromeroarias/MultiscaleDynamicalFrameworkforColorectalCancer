# Colorectal Cancer Multiscale Modeling

This repository contains the computational framework developed to investigate colorectal cancer as a nonlinear multiscale dynamical system. The project integrates a nonlinear gene regulatory network (GRN) with a biomechanical crypt model based on Voronoi tessellations, providing a quantitative link between intracellular regulation, tissue architecture, and emergent tumor behavior.
The mathematical model combines nonlinear ordinary differential equations describing the interactions among morphogens, tumor suppressor genes, and oncogenic regulators with a spatial representation of the intestinal crypt. The GRN includes nine key molecular components:

# Morphogens
- Wnt
- β-catenin
- Axin
# Tumor suppressor genes
- APC
- TP53
# Oncogenic regulators
- KRAS
- BRAF
- MYC
- TGF-β

The framework reproduces the emergence of bistability, nonlinear transitions, and spatial tumor predisposition driven by regulatory feedback and biomechanical constraints.

# Features

- Nonlinear gene regulatory network (9-node GRN)
- Stability and bifurcation analysis
- Phase-space visualization
- Bistability and attractor analysis
- Tumor state order parameters ($R_{full}$ and $R_{min}$)
- Voronoi-based intestinal crypt model
- Spatial Wnt gradient implementation
- Coupling between molecular dynamics and tissue biomechanics
- Visualization of crypt evolution and tumor progression


# Scientific Highlights
This framework demonstrates that colorectal cancer can be interpreted as a nonlinear dynamical transition between homeostatic and tumorigenic attractors.

The model reveals:

- bistable dynamics in the Wnt–TP53 regulatory plane;
- bistability between TP53 and TGF-β signaling;
- critical thresholds separating healthy and tumor states;
- spatial expansion of tumor-associated phenotypes along the crypt axis;
- collective tumor-state descriptors through the order parameters $R_{full}$ and $R_{min}$.

# Applications

- Mathematical Oncology
- Systems Biology
- Gene Regulatory Networks
- Dynamical Systems
- Nonlinear Dynamics
- Computational Biology
- Crypt Modeling
- Tissue Biomechanics
- Pattern Formation
- Multiscale Modeling

# Citation

If you use this repository in your research, please cite the accompanying publication describing the multiscale colorectal cancer model.
