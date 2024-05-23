# <img src="https://github.com/elliotfontaine/awesome-cylc/assets/92150839/1536672f-0fab-4d93-8a66-a4daa1d6cd53" alt="Cylc Logo" width=5% height=5%> Awesome Cylc
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of [Cylc](https://cylc.github.io/) workflows and useful resources. Please feel free to contribute!

Each item specifies the Cylc main versions it is compatible with. For exemple, "**[7/8] Cylc VSCode Extension**" means that this IDE extension is compatible with Cylc 7 and 8.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Fully-Fledged Workflows](#fully-fledged-workflows)
- [Workflow Design Patterns](#workflow-design-patterns)
- [Cylc Plugins](#cylc-plugins)
- [CI/CD](#cicd)
- [Syntax Highlighting](#syntax-highlighting)
- [Presentations](#presentations)
- [Videos](#videos)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Fully-Fledged Workflows
- **[8] [Cylc-GeoFabrics](https://github.com/rosepearson/cylc-geofabrics)** - A workflow for automating the use of [GeoFabrics](https://github.com/rosepearson/GeoFabrics) on NeSI.
- **[8] [RTMet](https://github.com/MetaboHUB-MetaToul-FluxoMet/RTMet)** - A workflow to process mass spectrometry data for metabolomics.
- **[8] [Cylc-Log-Analysis](https://github.com/aosprey/cylc-log-analysis)** - A workflow for asynchronously archiving and analysing cylc job logs from multiple cylc suites/workflows.
- **[7] [CMIP6 Workflows](https://github.com/NCAR/CESM_CMIP6_Cylc_Suites)** - Workflows used for the [CMIP6](http://doi.org/10.5194/gmd-13-5567-2020) experiments that NCAR participated in.

## Workflow Design Patterns
- **[7/8] [Tim's Simple Cylc Examples](https://github.com/wxtim/workflows)** - A collection of minimal Cylc workflows highlighting different features.
- **[8] [Cylc Patterns](https://github.com/pletzer/cylc_patterns)** - A collection of commonly used Cylc workflow patterns.
- **[8] [Sub-Workflow](https://github.com/hjoliver/cylc-subwf-example)** - A workflow run by a task in another workflow.
- **[8] [File-Driven Workflow](https://github.com/hjoliver/cylc-filedriven-example)** - Emulating [Snakemake](https://snakemake.github.io/)-like data processing.

## Cylc Plugins
- **[8] [Cylc-Rose Plugin](https://github.com/cylc/cylc-rose)** - A Cylc plugin providing support for the Rose `rose-suite.conf` file. Cylc 8 and Rose 2.

## CI/CD
- **[7/8] [Cylc Sphinx Extensions](https://cylc.github.io/cylc-sphinx-extensions/)** - Official library of Sphinx extensions for documenting Cylc projects.

## Syntax Highlighting
- **[7/8] [Cylc VSCode Extension](https://marketplace.visualstudio.com/items?itemName=cylc.vscode-cylc)**
- **[8] [Cylc TextMate Bundle](https://github.com/cylc/Cylc.tmbundle)** - For TextMate, Sublime Text, PyCharm, WebStorm and other editors.
- **[8] [Other IDEs](https://cylc.github.io/cylc-doc/latest/html/user-guide/writing-workflows/configuration.html#syntax-highlighting-for-workflow-configuration)** - Instructions for enabling syntax highlighting in other editors (Atom, Emacs, Gedit, Kate, Vim).

## Presentations
- **[7/8] [Cylc Presentations](https://cylc.github.io/cylc-presentations/)** - Official list of presentations by the Cylc team.

## Videos
- **[8] [IS-ENES3 Webinar](https://youtu.be/MHC-PCuy_94?feature=shared)** - Introduction to the Cylc workflow engine by Oliver Sanders (2023).
- **[8] [NeSI Webinar](https://youtu.be/lYTEWn4mncE?feature=shared)** - Workflow Orchestration with Cylc 8 on NeSI Platforms, Hilary Oliver (2022).