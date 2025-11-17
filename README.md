# README

## Overview

This repository contains three Jupyter notebooks that generate all visualizations used in our paper:

- **Cleaning_up_Germany_Geimende_plots_maps.ipynb**
- **Cleaning_up_Germany_Gemeinde_Climate_Scenarios.ipynb**
- **Cleaning_up_Germany_Land_2020.ipynb**


Each notebook includes an **“Open in Colab”** button at the top, allowing users to launch it directly in Google Colab. This is often the easiest way to reproduce the figures, since Colab provides a stable environment with simple package installation.

---

## Running the Notebooks on Google Colab

**Note:** The Colab free tier has **limited RAM**, which affects:

- `Cleaning_up_Germany_Geimende_plots_maps.ipynb`
- `Cleaning_up_Germany_Gemeinde_Climate_Scenarios.ipynb`

These notebooks use large raw files and many intermediate variables. Users may experience **session restarts** due to RAM limitations.

### What to do when RAM runs out

1. Re-run the **package installation** and **import** cells (the first two cells).
2. Re-run the specific sections that are **highlighted inside the notebook** as required.
3. Reload the stored **pickle files** containing key intermediate variables.

### Why storing and reloading is required on Colab

On Google Colab, **storing and reloading the intermediate variables is necessary**; otherwise, Colab will continually re-compute them, run out of RAM, and users will never be able to complete the workflow.  
The notebooks include cells that save important intermediate variables as `.pkl` files and instructions on when to reload them.

---

## Running the Notebooks Locally

If users install the required packages on their local computer, the **RAM limitation is not a problem**. The notebooks can run continuously without session restarts.

---

## Notes for `Cleaning_up_Germany_Geimende_plots_maps.ipynb`

This notebook includes clear instructions highlighting several sections that must be re-run at specific points. Different sections require different starting variables, so following the highlighted instructions is essential for ensuring that the later parts run correctly.

---
