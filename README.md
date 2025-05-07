# <img src="https://github.com/elliotfontaine/awesome-cylc/assets/92150839/1536672f-0fab-4d93-8a66-a4daa1d6cd53" alt="Cylc Logo" width=5% height=5%> Awesome Cylc
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of [Cylc](https://cylc.github.io/) workflows and useful resources. Please feel free to contribute!

Each entry specifies the main Cylc versions it supports. For example, "**8️⃣|7️⃣ Cylc VSCode Extension**" means the extension works with both Cylc 7 and 8.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

<p align="center">
<a href="#-real-world-workflows">🌍 Real-World Workflows</a>
<span>|</span>
<a href="#-templates--design-patterns">🧩 Templates & Design Patterns</a>
<span>|</span>
<a href="#-tooling--extensions">🧰 Tooling & Extensions</a>
<span>|</span>
<a href="#-deployments">🚀 Deployments</a>
<span>|</span>
<a href="#-learning--presentations">🎓 Learning & Presentations</a>
<span>|</span>
<a href="#-publications">📚 Publications</a>
</p>

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 🌍 Real-World Workflows
- **8️⃣ [Cylc-GeoFabrics](https://github.com/rosepearson/cylc-geofabrics)** – Automates hydrological modelling workflows using [GeoFabrics](https://github.com/rosepearson/GeoFabrics) on NeSI.
- **8️⃣ [RTMet](https://github.com/MetaboHUB-MetaToul-FluxoMet/RTMet)** – Processes mass spectrometry data for metabolomics.
- **8️⃣ [Cylc-Log-Analysis](https://github.com/aosprey/cylc-log-analysis)** – Asynchronously archives and analyses Cylc job logs from multiple workflows.
- **7️⃣ [CMIP6 Workflows](https://github.com/NCAR/CESM_CMIP6_Cylc_Suites)** – Runs [CMIP6](http://doi.org/10.5194/gmd-13-5567-2020) experiments at NCAR using CESM models.
- **7️⃣ [eWaterCycle](https://github.com/eWaterCycle/ewatercycle-forecast)** – Runs the forecasting workflow for the [eWaterCycle](https://www.ewatercycle.org/) system.

## 🧩 Templates & Design Patterns
- **8️⃣|7️⃣ [Tim's Simple Cylc Examples](https://github.com/wxtim/workflows)** – Minimal workflows showcasing key Cylc features.
- **8️⃣ [Cylc Patterns](https://github.com/pletzer/cylc_patterns)** – Commonly used workflow design patterns in Cylc.
- **8️⃣ [Data in Cylc Workflows](https://github.com/hjoliver/cylc-and-data)** – A simple example to illustrate the relationship between Cylc workflows and the data they process.
- **8️⃣ [Sub-Workflow](https://github.com/hjoliver/cylc-subwf-example)** – Demonstrates running a workflow from within a task of another.
- **8️⃣ [File-Driven Workflow](https://github.com/hjoliver/cylc-filedriven-example)** – Emulates [Snakemake](https://snakemake.github.io/)-style rule-based data processing.
- **7️⃣ [Tasks in Conda Envs](https://github.com/matthewrmshin/cylc-workflow-conda)** – Runs Cylc tasks inside [Conda](https://github.com/conda/conda) virtual environments.

## 🧰 Tooling & Extensions
- **8️⃣|7️⃣ [Cylc VSCode Extension](https://marketplace.visualstudio.com/items?itemName=cylc.vscode-cylc)** – Language support for `.cylc` workflow configuration files in Visual Studio Code.
- **8️⃣|7️⃣ [Cylc Sphinx Extensions](https://cylc.github.io/cylc-sphinx-extensions/)** – Official Sphinx extensions for documenting Cylc projects.
- **8️⃣ [Cylc-Rose Plugin](https://github.com/cylc/cylc-rose)** – Support for `rose-suite.conf` files (Cylc 8 + Rose 2).
- **8️⃣ [yProv4WFs](https://github.com/HPCI-Lab/yProv4WFs)** – PROV-compatible provenance capture for Cylc and StreamFlow. See the [setup guide](https://github.com/HPCI-Lab/yProv4WFs/blob/main/yprov4wfs/yProv4WFs_cylc/HowToRun_yProv4WFs_Cylc.md).
- **8️⃣ [Syntax Highlighting](https://cylc.github.io/cylc-doc/latest/html/user-guide/writing-workflows/configuration.html#syntax-highlighting-for-workflow-configuration)** – How to enable syntax highlighting for `.cylc` files in popular editors.
- **8️⃣ [Cylc TextMate Bundle](https://github.com/cylc/Cylc.tmbundle)** – Syntax support for TextMate, Sublime Text, JetBrains IDEs, and more.
- **8️⃣ [Tree-Sitter-Cylc](https://github.com/elliotfontaine/tree-sitter-cylc)** – Tree-sitter grammar for `.cylc` files, compatible with Zed, Neovim, Helix, Pulsar, Emacs, etc.

## 🚀 Deployments
- **8️⃣|7️⃣ [Altair Weather Solution](https://web.altair.com/en/cylc-weather-solution)** – Commercial deployment of Cylc with Altair PBS Professional™.
  See the [blog article](https://altair.com/blog/articles/Cylc-Altair-s-PBS-Professional-x2122-Power-Weather-Modeling-at-Australia-s-Bureau-of-Meteorology) for details on its use at the Australian Bureau of Meteorology.


## 🎓 Learning & Presentations
- **8️⃣|7️⃣ [Cylc Presentations](https://cylc.github.io/cylc-presentations/)** – Official slides and talks from the Cylc team.
- **8️⃣ [IS-ENES3 Webinar](https://youtu.be/MHC-PCuy_94?feature=shared)** – “Introduction to the Cylc workflow engine” by Oliver Sanders (2023).
- **8️⃣ [NeSI Webinar](https://youtu.be/lYTEWn4mncE?feature=shared)** – “Workflow Orchestration with Cylc 8 on NeSI Platforms” by Hilary Oliver (2022).
- **8️⃣ [yProv4WFs presented at SC24](https://dl.acm.org/doi/abs/10.1109/SCW63240.2024.00253)** – “A Software Ecosystem for Multi-Level Provenance Management in Large-Scale Scientific Workflows for AI Applications” (2024).

## 📚 Publications
- **[Workflow Automation for Cycling Systems](https://ieeexplore.ieee.org/document/8675433), *Oliver et al.*** – Original Cylc publication.
- **[Automated model optimisation using the Cylc workflow engine (Cyclops v1.0)](https://doi.org/10.5194/gmd-11-2153-2018), *Gormat et Oliver*** – How to use Cylc and [NLops](https://nlopt.readthedocs.io/en/latest/) for geophysical model parameters tuning.
