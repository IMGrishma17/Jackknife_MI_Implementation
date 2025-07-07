# Testing and Understanding the Jackknife Approach to Mutual Information Estimation

**Author:** Grishma Mainali

This repository contains the implementation, testing, and final report for the second phase of my postgraduate project on the Jackknife resampling method for Mutual Information (MI) estimation.

## Project Overview

Estimating Mutual Information from limited data is challenging due to bias and variance. This project builds on the 2018 PNAS study by Zeng, Xia, and Tong, which introduced a Jackknife-based bias-corrected MI estimator.

In this phase, we:

- Implemented the Jackknife MI estimator in Python  
- Tested its performance on synthetic datasets varying in dependency strength, sample size, and noise  
- Compared results against Scikit-learn’s MI estimator and a histogram-based approach  
- Investigated multivariate dependence estimation and compared Jackknife MI with bootstrap resampling  
- Explored the estimator’s potential as an alternative to Wasserstein distance in noise-sensitive, small-sample scenarios  

Our results demonstrate that Jackknife MI provides more stable and less biased estimates in low-sample settings and various dependency structures, supporting its use in feature selection, dependency detection, and learning tasks.

## Repository Contents

- `JackknifeMI_FinalReport.pdf` — The final detailed report of this project phase  
- `PPB.ipynb` — Notebook with Jackknife MI estimator implementation and basic tests  
- `PPB_Multivariate.ipynb` — Notebook covering multivariate dependence estimation and comparisons  
- `PPB_Application.ipynb` — Notebook exploring Jackknife MI vs Wasserstein distance under noise and sample size variations  
