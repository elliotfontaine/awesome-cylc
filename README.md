# <img src="https://github.com/elliotfontaine/awesome-cylc/assets/92150839/1536672f-0fab-4d93-8a66-a4daa1d6cd53" alt="Cylc Logo" width=5% height=5%> Awesome Cylc
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of [Cylc](https://cylc.github.io/) workflows and useful resources. Please feel free to contribute!

Each item specifies the Cylc main versions it is compatible with. For exemple, "**[7/8] Cylc VSCode Extension**" means that this IDE extension is compatible with Cylc 7 and 8.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

<p align="center">
<a href="#fully-fledged-workflows">Fully-Fledged Workflows</a>
<span>|</span>
<a href="#workflow-design-patterns">Workflow Design Patterns</a>
<span>|</span>
<a href="#cylc-plugins">Cylc Plugins</a>
<span>|</span>
<a href="#cicd">CI/CD</a>
<span>|</span>
<a href="#syntax-highlighting">Syntax Highlighting</a>
<span>|</span>
<a href="#research-papers">Research Papers</a>
<span>|</span>
<a href="#presentations">Presentations</a>
<span>|</span>
<a href="#videos">Videos</a>
<span>|</span>
<a href="#miscellaneous">Miscellaneous</a>
</p>

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Fully-Fledged Workflows
- **[8] [Cylc-GeoFabrics](https://github.com/rosepearson/cylc-geofabrics)** - A workflow for automating the use of [GeoFabrics](https://github.com/rosepearson/GeoFabrics) on NeSI.
- **[8] [RTMet](https://github.com/MetaboHUB-MetaToul-FluxoMet/RTMet)** - A workflow to process mass spectrometry data for metabolomics.
- **[8] [Cylc-Log-Analysis](https://github.com/aosprey/cylc-log-analysis)** - A workflow for asynchronously archiving and analysing cylc job logs from multiple workflows.
- **[7] [CMIP6 Workflows](https://github.com/NCAR/CESM_CMIP6_Cylc_Suites)** - Workflows used for the [CMIP6](http://doi.org/10.5194/gmd-13-5567-2020) experiments that NCAR participated in.
- **[7] [eWaterCycle](https://github.com/eWaterCycle/ewatercycle-forecast)** - Workflow of the [eWaterCycle](https://www.ewatercycle.org/) forecasting system.

## Workflow Design Patterns
- **[7/8] [Tim's Simple Cylc Examples](https://github.com/wxtim/workflows)** - A collection of minimal Cylc workflows highlighting different features.
- **[8] [Cylc Patterns](https://github.com/pletzer/cylc_patterns)** - A collection of commonly used Cylc workflow patterns.
- **[8] [Sub-Workflow](https://github.com/hjoliver/cylc-subwf-example)** - A workflow run by a task in another workflow.
- **[8] [File-Driven Workflow](https://github.com/hjoliver/cylc-filedriven-example)** - Emulating [Snakemake](https://snakemake.github.io/)-like data processing.
- **[7] [Tasks in Conda Envs](https://github.com/matthewrmshin/cylc-workflow-conda)** - A Cylc workflow template where tasks can be run inside [Conda](https://github.com/conda/conda) virtual environments.

## Cylc Plugins
- **[8] [Cylc-Rose Plugin](https://github.com/cylc/cylc-rose)** - A Cylc plugin providing support for the Rose `rose-suite.conf` file. Cylc 8 and Rose 2.

## CI/CD
- **[7/8] [Cylc Sphinx Extensions](https://cylc.github.io/cylc-sphinx-extensions/)** - Official library of Sphinx extensions for documenting Cylc projects.

## Syntax Highlighting
- **[7/8] [Cylc VSCode Extension](https://marketplace.visualstudio.com/items?itemName=cylc.vscode-cylc)**
- **[8] [Cylc TextMate Bundle](https://github.com/cylc/Cylc.tmbundle)** - For TextMate, Sublime Text, PyCharm, WebStorm and other editors.
- **[8] [Other IDEs](https://cylc.github.io/cylc-doc/latest/html/user-guide/writing-workflows/configuration.html#syntax-highlighting-for-workflow-configuration)** - Instructions for enabling syntax highlighting in other editors (Atom, Emacs, Gedit, Kate, Vim).

## Research Papers
- **[Workflow Automation for Cycling Systems](https://ieeexplore.ieee.org/document/8675433), *Oliver et al.*** - Original Cylc publication.
- **[Automated model optimisation using the Cylc workflow engine (Cyclops v1.0)](https://doi.org/10.5194/gmd-11-2153-2018), *Gormat et Oliver*** - How to use Cylc and [NLops](https://nlopt.readthedocs.io/en/latest/) for geophysical model parameters tuning.

## Presentations
- **[7/8] [Cylc Presentations](https://cylc.github.io/cylc-presentations/)** - Official list of presentations by the Cylc team.

## Videos
- **[8] [IS-ENES3 Webinar](https://youtu.be/MHC-PCuy_94?feature=shared)** - Introduction to the Cylc workflow engine by Oliver Sanders (2023).
- **[8] [NeSI Webinar](https://youtu.be/lYTEWn4mncE?feature=shared)** - Workflow Orchestration with Cylc 8 on NeSI Platforms, Hilary Oliver (2022).

## Miscellaneous
- **[7/8] [Altair Weather Solution](https://web.altair.com/en/cylc-weather-solution)** - Commercial support for Cylc from Altair, using Altair PBS Professional™ for workload management (*[blog article](https://altair.com/blog/articles/Cylc-Altair-s-PBS-Professional-x2122-Power-Weather-Modeling-at-Australia-s-Bureau-of-Meteorology)*).
