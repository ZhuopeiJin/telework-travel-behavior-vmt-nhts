# Telework, Time Allocation, and Non-Work Travel Behavior

## Overview
This repository contains code for my Master’s Report examining how remote work
influences non-work out-of-home activity time allocation and vehicle miles traveled using
the 2017 and 2022 National Household Travel Survey (NHTS).

## Repository Structure
- notebooks/01_run_2017.ipynb: Data preparation (2017)
- notebooks/02_run_2022.ipynb: Data preparation (2022)
- notebooks/03_sur_analysis.ipynb: SUR estimation and results
- src/: Shared utility code
- data/sample/: Sample datasets for reproducibility

## Data
Raw NHTS microdata are restricted and not included.
Sample datasets are provided to allow code execution.

## How to Reproduce
1. Clone the repository
2. Run notebooks in order: 01 → 02 → 03
