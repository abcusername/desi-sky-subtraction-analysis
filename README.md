# DESI Sky-Subtraction Analysis for Emission-Line Measurements

This repository contains the first-stage workflow for assessing sky-subtraction effects on DESI emission-line measurements, with a focus on narrow-line AGN spectra and the impact of sky residuals near the [OI] 6300/6364 Å region.

## Project Background

Night-sky emission introduces strong background features into ground-based optical spectroscopy. In emission-line studies, imperfect sky subtraction can affect line flux measurements, line ratios, and the physical interpretation of spectra.

This project focuses on evaluating how sky-subtraction residuals may influence DESI emission-line measurements, especially for narrow-line AGN spectra in the redshift range **z = 0.25–0.29**, where the target spectral features are close to important sky-line regions.

## Current Research Goal

The current goal is to assess the effect of sky subtraction around the oxygen sky-line region near **6300 Å** and **6364 Å**, and to understand how these residuals may bias emission-line measurements in DESI spectra.

## What Has Been Completed

### 1. Background review
I reviewed the physical origin of night-sky background and the role of strong atmospheric emission lines in optical spectroscopy.

### 2. Problem definition
I defined the current science task as:
- using a narrow-line AGN sample at z = 0.25–0.29
- assessing the effect of sky subtraction near the [OI] sky-line region
- understanding the influence on emission-line measurements

### 3. DESI data workflow setup
I completed the first-stage notebook workflow, including:
- environment check
- inspection of DESI FITS files
- retrieval of public DESI spectra
- preliminary spectral exploration

## Repository Structure

```text
desi-sky-subtraction-analysis/
├── docs/      # task summaries and progress notes
├── src/       # notebooks and scripts
├── figures/   # selected spectra and skyline-region plots
├── results/   # stage summaries and future outputs
