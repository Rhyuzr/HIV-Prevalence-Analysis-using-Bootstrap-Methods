# Bootstrap Analysis of Global HIV Prevalence: A Statistical Investigation of Temporal Trends and Regional Disparities

This repository contains the code and report for a statistical investigation into global HIV prevalence, focusing on temporal trends and regional disparities using bootstrap methods.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [Methodology](#methodology)
4. [Key Findings](#key-findings)
5. [Implications](#implications)
6. [Limitations and Future Work](#limitations-and-future-work)
7. [Repository Structure](#repository-structure)
8. [How to Run the Analysis](#how-to-run-the-analysis)
9. [Dependencies](#dependencies)
10. [Author](#author)
11. [License](#license)

## Introduction
HIV/AIDS remains a significant global health challenge with varying prevalence rates across different regions and time periods. Understanding these patterns and their associated uncertainties is crucial for effective public health planning and resource allocation. This project employs robust bootstrap methods to provide statistical analyses of HIV prevalence data, offering insights into global trends and regional differences.

## Project Objectives
- To estimate global HIV prevalence rates with associated uncertainty measures
- To analyze temporal trends in HIV prevalence over time
- To investigate regional disparities in HIV prevalence rates, identifying statistically significant differences

## Methodology
This study utilizes the Gapminder dataset, which provides HIV prevalence rates (percentage of adults aged 15-49) across various countries and years. The core of the analysis relies on bootstrap resampling techniques. Bootstrap methods are employed to:

- Derive robust estimates of prevalence
- Quantify the uncertainty in these estimates through confidence intervals
- Assess the statistical significance of observed temporal changes and regional differences

## Key Findings
The bootstrap analysis yielded several important insights:

1. **Robust Estimates**: The analysis provided robust estimates of global HIV prevalence with well-defined uncertainty bounds.
2. **Temporal Trends**: Significant changes in HIV prevalence over time were observed, indicating evolving epidemic dynamics.
3. **Regional Disparities**: Regional disparities remain a crucial factor in global HIV distribution, with statistically significant differences between high and low prevalence areas.
4. **Uncertainty Quantification**: The temporal analysis demonstrated how the uncertainty in HIV prevalence estimates has changed over time.

## Implications
Our findings have several important implications for public health policy:

- **Region-Specific Interventions**: The need for tailored, region-specific intervention strategies to address the varying prevalence rates effectively.
- **Uncertainty in Estimates**: The importance of considering uncertainty in prevalence estimates for more accurate planning and resource allocation.
- **Continuous Monitoring**: The value of continuous monitoring and assessment of temporal trends to adapt public health responses proactively.

## Limitations and Future Work
Several limitations should be considered when interpreting these findings:

- **Data Quality and Representativeness**: The analysis assumes the data is representative of the true HIV prevalence in each country, and data availability/quality can vary across regions.
- **Missing Data**: Missing data points might affect the reliability of some estimates and trend analyses.
- **Temporal Gaps**: Gaps in data collection over time may influence the accuracy of temporal trend analyses.

Future research could focus on:

- Incorporating additional variables such as healthcare spending, education levels, and specific intervention programs to better understand the drivers of disparities.
- Evaluating the effectiveness of targeted interventions in specific regions.
- Exploring more advanced statistical models to account for potential confounding factors.

## Repository Structure
- `AppStat Homework Submission HALMAERT.ipynb`: The Jupyter Notebook containing the complete statistical analysis, including data loading, cleaning, bootstrap implementation, and visualization.
- `report HALMAERT.pdf`: A detailed report summarizing the study's objectives, methodology, key findings, implications, and limitations.

## How to Run the Analysis
To reproduce the analysis presented in this repository, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
