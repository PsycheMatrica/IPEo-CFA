# Validation of the IPE<sub>O</sub> and ΔIPE<sub>O</sub> Tests for CFA

Replication code for the manuscript:

**Data-Matrix-Based Overall Goodness-of-Fit Testing for Confirmatory Factor Analysis: In-Sample Prediction Error for Observed Variables**

**Authors:** Youngze Kim, Gyeongcheol Cho*, and Hanjoe Kim*  
\*Co-corresponding authors

This repository contains the computational materials used to reproduce the simulation study and empirical illustration reported in the manuscript. The study evaluates two data-matrix-based goodness-of-fit tests for confirmatory factor analysis: the in-sample prediction error for observed variables (IPE<sub>O</sub>) test for evaluating a single model and the ΔIPE<sub>O</sub> test for comparing nested models.

## Repository Structure

### `simulation/`

Contains the code used for the Monte Carlo simulation study, including:

- data generation,
- specification of simulation conditions,
- calls to SFA Prime and lavaan for model estimation and hypothesis testing, and
- summarization of simulation results.

### `illustration/`

- contains the code and materials used to reproduce the empirical illustration reported in the manuscript.

## Software

Structured factor analysis (SFA) is implemented using **SFA Prime Version 1.2.0** (Cho, 2024).

Covariance structure analysis (CSA) is implemented in R using **lavaan Version 0.6-20** (Rosseel, 2012).

Additional software requirements and instructions for running the analyses are provided within the corresponding folders.

## Reproducibility

The materials in this repository are provided to facilitate reproduction of the computational results reported in the manuscript. Repository releases are used to preserve versions corresponding to different stages of the manuscript.

## Code Inquiries

For questions regarding the replication code, please contact Gyeongcheol Cho at **cheol6091@gmail.com**.

## Citation

If you use these materials, please cite the associated manuscript:

Kim, Y., Cho, G., & Kim, H. *Data-Matrix-Based Overall Goodness-of-Fit Testing for Confirmatory Factor Analysis: In-Sample Prediction Error for Observed Variables*. Manuscript in preparation.
