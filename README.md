# Simple Random Sampling: A Comprehensive Analysis with R


## Project Overview

This repository contains a detailed report and R code for a comprehensive exploration of **Simple Random Sampling (SRS)**, one of the most fundamental probability sampling techniques in statistics. The project uses a hypothetical population of university students to demonstrate key concepts, from theoretical definitions to practical implementation and simulation.

The work includes a full methodological report, a reproducible R script for simulation, and a comparison of SRS With Replacement (SRSWR) and SRS Without Replacement (SRSWOR), highlighting their differences in efficiency and variance.


## Objectives

The primary objectives of this project are to:

1.  **Define** a clear population and sampling frame for a study.
2.  **Delineate** the exact, step-by-step procedure for selecting a sample via Simple Random Sampling.
3.  **Critically evaluate** the advantages and limitations of SRS in a practical context.
4.  **Explain** the conceptual and statistical differences between SRSWR and SRSWOR.
5.  **Simulate** both sampling methods in R to empirically demonstrate their properties and compare the results.


## Key Findings from the Simulation

The R simulation empirically validates the core theoretical concepts:

- Unbiasedness: Both SRSWOR and SRSWR produce sample means that are, on average, equal to the true population mean (~3.20).
- Efficiency: SRSWOR is more efficient. The variance of the sample means under SRSWOR is consistently lower than under SRSWR, due to the Finite Population Correction (FPC) factor.

The generated plot clearly shows a tighter, more precise sampling distribution for SRSWOR.


## Detailed Report Contents

The comprehensive report (SRS_Comprehensive_Report.pdf) covers the following sections in depth:

1. Introduction & Objectives
2. Population & Sampling Frame: A clear definition of the "University of Exemplaria" student population and a critical assessment of the sampling frame.
3. Steps for SRS: A meticulous, step-by-step guide to selecting a simple random sample.
4. Advantages & Limitations: Three key strengths and three practical limitations of SRS, contextualized for the study.
5. SRSWR vs. SRSWOR: A conceptual deep-dive into the differences, focusing on selection probability, sample space, and variance.
6. R Simulation & Comparison: The methodology, code, and results of the empirical comparison.
7. Conclusion: A summary of findings and the practical recommendation for SRSWOR.


