# Geometry-Aware Learning with Symmetric Positive Definite Matrices

National Science Foundation Research Training Group (RTG) Summer Internship 2026 | Tuskegee University & Auburn University

## Overview
This project compares three Riemannian geometries (Log-Euclidean, Bures-Wasserstein,
and Affine-Invariant) for EEG motor imagery classification using SPD covariance matrices
and tangent-space projections across three benchmark datasets.

## Datasets
- **BCI III IIIa** — 4-class motor imagery, 3 subjects, 60×60 covariance matrices
- **BCI III IVa** — Binary motor imagery, 5 subjects, 118×118 covariance matrices
- **PhysioNet EEG Motor Imagery** — Binary left/right fist imagery, ~100 subjects, 64×64

> Data is not included in this repo. Files are stored in Google Drive.

## Tasks
- **Task 1:** Compare Manifold UMAP vs Tangent-Space UMAP across three geometries
- **Task 2:** Nested CV classification with PCA/UMAP dimensionality reduction
- **Task 3:** Raw vs standardized tangent features analysis

## Key Results
- LogE geometry consistently achieved the strongest classification performance
- BCI IIIa: 73.8% test accuracy, Kappa 0.651 (25% chance baseline)
- Full tangent features outperformed PCA and UMAP reduction in all conditions
- Standardization helps BW but consistently hurts LogE

## Authors
Chinasa Anthony, Katy Yang, JB Gracey, Rio Vazquez, Jerome Holland
