# Bank-Customer-Churn-Analysis
**Strategic Retention Analysis & Predictive Insights | R-Language Project**

---

## Project Overview
This analysis investigates a critical churn crisis across European banking operations. While France and Spain remain stable, the German market exhibits a **32.4% churn rate**. This project identifies the "Product Fatigue" threshold and provides a roadmap for stabilizing high-value customer segments.

##  Project Deliverables
*  **[Live Executive Report](https://bank-customer-churn-analysis.netlify.app/)** — *Polished Stakeholder View*
*  **[Technical R-Markdown Script](./bank_churn.Rmd)** — *Data Cleaning & Visualization Logic*
*  **[Bank Customer Dataset](./index.html)** 

---

##  Technical Stack
| Category | Tools & Libraries |
| :--- | :--- |
| **Language** | R (v4.0+) |
| **Data Cleaning** | Tidyverse (dplyr, tidyr) |
| **Visualization** | ggplot2, Plotly |
| **Data Types** | Factor Re-classification, Dimensionality Reduction |
| **Reporting** | R Markdown (Knit to HTML) |

---

##  Key Strategic Findings
* **The "Two-Product" Anchor:** Identified a loyalty sweet spot where customers with exactly 2 products show the lowest attrition (11-13%).
* **German Market Crisis:** Churn in Germany (32.4%) is double that of France/Spain, driven by "Product Over-Saturation" (90%+ churn for 3+ products).
* **The Service Gap:** Discovered a **100% failure rate** in complaint-driven retention; every customer who filed a complaint eventually exited.
* **Gender Disparity:** Female customers are **1.5x more likely** to churn (25.1%) compared to male customers (16.5%).

---

##  Data Integrity & Methodology
To ensure professional-grade accuracy, the following preprocessing steps were taken in R:
1. **Noise Removal:** Dropped irrelevant identifiers (`RowNumber`, `CustomerId`, `Surname`).
2. **Feature Engineering:** Re-classified binary integers into **Factors** (`Exited`, `Complain`, etc.) for robust statistical grouping.
3. **Logic Verification:** Implemented `as.numeric(as.character())` transformations to ensure accurate percentage calculations for binary levels.

## Repository Structure
* `churn_analysis.Rmd`: The R source code with documented cleaning steps.
* `churn_analysis.html`: The final knitted report for executive review.

---
**Maria Aslam** 
**Contact:** [LinkedIn](https://www.linkedin.com/in/maria-aslam-458860316/)
