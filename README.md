

# Changes to the orignal Tutorials
1. This repository is working to make the [TrackML dataset from Kaggle](https://www.kaggle.com/competitions/trackml-particle-identification/data) compatiable with these tutotrial.
2. Currently tutorial 1 has passed.
3. Please also using this repository of [gnn_tracking](https://github.com/walkieq/gnn_tracking)

<div align="center">

# GNN Tracking Tutorials

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- [![Documentation Status](https://readthedocs.org/projects/gnn-tracking-tutorials/badge/?version=latest)](https://gnn-tracking-tutorials.readthedocs.io/) -->
<!-- [![Pypi status](https://badge.fury.io/py/gnn-tracking-tutorials.svg)](https://pypi.org/project/gnn-tracking-tutorials/) -->

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/gnn-tracking/tutorials/main.svg)](https://results.pre-commit.ci/latest/github/gnn-tracking/tutorials/main)
[![link checker](https://github.com/gnn-tracking/tutorials/actions/workflows/check-links.yaml/badge.svg)](https://github.com/gnn-tracking/tutorials/actions/workflows/check-links.yaml)
[![gitmoji](https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg)](https://gitmoji.dev)
[![License](https://img.shields.io/github/license/gnn-tracking/tutorials)](https://github.com/gnn-tracking/tutorials/blob/master/LICENSE.txt)
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)
[![PR welcome](https://img.shields.io/badge/PR-Welcome-%23FF8300.svg)](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)

</div>

## 📝 Description

Tutorials and onboarding for the GNN Tracking project

## 📦 Installation

1. Follow the instructions from [the main library](https://github.com/gnn-tracking/gnn_tracking)
   to set up the conda environment and install the package.

2. Run `pytest` on the main package

3. Download the [trackml dataset](https://competitions.codalab.org/competitions/20112) (see note below).
   Note that the full dataset is linked in "Dataset description and other files" in the "Participate"
   tab (O(100GB) of data). The data files of the "Starting Kit"/"Public Data" are only a tiny fraction
   of this.

> **Note**
> The website [competitions.codalab.org](https://competitions.codalab.org/) does no longer accept new
> registrations (needed to access the data set). If you do not already have an account there,
> contact us for the dataset.

## 🧰 Development setup

```bash
pip3 install pre-commit
pre-commit install
nbdime config-git enable
```
