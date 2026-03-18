# SprayDriftModels

Welcome to **SprayDriftModels** — an open-source organization developing mechanistic models for simulating the drift and fate of pesticide spray droplets from agricultural spray equipment.

## Projects

### [CDM — Casanova Drift Model](https://github.com/SprayDriftModels/CDM)

The Casanova Drift Model (CDM) is a mechanistic model that simulates the trajectory and fate of pesticide spray droplets released from agricultural spray equipment. It supports risk assessment workflows for non-target organisms by providing detailed drift profiles under varying environmental and equipment conditions.

Key features:
- Simulates droplet trajectory and deposition for a range of nozzle types and operating pressures
- Validated against SETAC DRAW test cases
- Available as a C++ library, command-line tool, and R package
- Builds on Windows and Linux via CMake and vcpkg

### [cdmshiny — CDM Shiny App](https://github.com/SprayDriftModels/cdmshiny)

An interactive R Shiny web application for the Casanova Drift Model (CDM). Provides a user-friendly graphical interface for running CDM simulations and visualizing spray drift results without requiring command-line usage.

Key features:
- Interactive web interface for configuring and running CDM simulations
- Visualization of spray drift deposition profiles
- Accessible to users without programming experience

### [DRAW-Model — DRAW Model Prediction App](https://github.com/SprayDriftModels/DRAW-Model)

A Shiny app for spray drift prediction in agricultural risk assessment, using Bayesian multilevel regression models fitted with [brms](https://paul-buerkner.github.io/brms/). A deliverable of the [SETAC DRAW workshop](https://www.spraydriftmitigation.info/).

Key features:
- Predicts spray drift deposition at various downwind distances under user-specified conditions
- Compares predictions against Rautmann reference curves
- Supports Bayesian multilevel (BRM-lognormal) and frequentist linear mixed (LME) models
- Interactive dashboard with trial comparisons and downloadable HTML reports

## Getting Started

See the [CDM repository](https://github.com/SprayDriftModels/CDM) for build instructions, sample input files, and documentation. See the [DRAW-Model repository](https://github.com/SprayDriftModels/DRAW-Model) for prerequisites and usage instructions. See the [cdmshiny repository](https://github.com/SprayDriftModels/cdmshiny) for the CDM Shiny app.

## Contributing

Contributions are welcome! Please open an issue or pull request in the relevant repository.
