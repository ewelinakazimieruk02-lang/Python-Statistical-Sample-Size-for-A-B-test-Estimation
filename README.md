# 🧪 The A/B Blueprint

Python: Statistical Sample Size Estimation

## I. Introduction

This project provides a rigorous statistical foundation for planning reliable A/B tests using Python. The primary goal is to accurately calculate the required sample sizes needed to detect meaningful changes in conversion rates between product page variants. By executing these estimations before an experiment launches, it ensures that product teams avoid underpowered tests (which miss real business impacts) and oversized tests (which unnecessarily waste time and web traffic).

## II. Project Details

The analysis is built around a baseline conversion rate of 10% and an industry-standard statistical power of 80%. The project systematically calculates the exact traffic volume required to validate a 3% expected uplift in conversion. Moving beyond a single calculation, the code performs a sensitivity analysis to evaluate how the testing requirements change under stricter conditions. It directly compares the required sample sizes when the significance level (alpha) is tightened from 5% down to 1%, and calculates the massive traffic shift required to detect a much smaller, 1% minimum detectable effect.

## III. Challenges and Highlights

The standout feature of this project is its focus on proactive experimental design rather than reactive post-experiment analysis. A major analytical highlight is mathematically demonstrating the non-linear relationship between statistical strictness and traffic requirements. 

By calculating and comparing the numbers, the project proves how dropping the expected effect from 3% to 1% exponentially increases the required sample size. This bridges the gap between theoretical statistics and practical business reality, providing managers with a clear understanding of the trade-offs between the desire for high statistical certainty and the actual time/traffic costs required to achieve it. 

## IV. Technologies Used

* **Python (Statsmodels / SciPy)** – executing statistical proportion tests, power analysis, and sample size calculations
* **A/B Testing Frameworks** – applying core concepts like Minimum Detectable Effect (MDE), statistical power (1-β), and significance levels (α)
* **Google Colab** – interactive notebook environment for executing code and documenting business conclusions
