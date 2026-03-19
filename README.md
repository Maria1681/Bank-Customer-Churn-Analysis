# Bank Customer Churn Analysis
**Strategic Retention Analysis & Predictive Insights | R-Language Project**

---

## Project Overview
This analysis investigates a critical churn crisis across European banking operations. While France and Spain maintain stable churn rates (~16%), the German market exhibits a severe **32.4% churn rate**This project identifies the "Product Fatigue" threshold and provides a data-driven roadmap for stabilizing high-value customer segments.

## Project Deliverables
* 📈 **[Live Analysis Report](https://bank-customer-churn-analysis.netlify.app/)** — *Full R-Markdown Executive Summary*
* 💾 **[Technical R-Script](bank_churn.Rmd)** — *End-to-end cleaning and visualization logic*

---

## Technical Stack (R)
| Category | Tools & Libraries |
| :--- | :--- |
| **Language** | R |
| **Data Wrangling** | `tidyverse` (dplyr, tidyr, readr) |
| **Visualization** | `ggplot2` |
| **Methodology** | [cite_start]Factor Re-classification, Dimensionality Reduction [cite: 27, 30] |
| **Reporting** | R Markdown (Knit to HTML) |

---

## Key Strategic Findings
* **The "Two-Product" Anchor:** Identified a loyalty "Survival Sweet Spot" where customers with exactly 2 products show the lowest churn (11–13%).
* **Product Over-Saturation:** Churn spikes to **90–100%** when German customers reach 3 or 4 products, suggesting complex bundles drive exits.
* **The Service Gap:** Discovered a **100% failure rate** in complaint-driven retention; every customer who filed a complaint eventually closed their account.
* **Premium Segment Flight:** Churn is high among "Very Good" credit tier customers (~33.5%), matching the rate of high-risk segments.
* **Gender Disparity:** Female customers are **1.5 times more likely** to leave the bank than men.

---

## Data Cleaning & Methodology
To ensure statistical integrity, the raw dataset underwent rigorous preprocessing in R:
1. **Dimensionality Reduction:** Removed irrelevant identifiers such as `RowNumber`, `CustomerId`, and `Surname` to reduce noise.
2. **Attribute Re-classification:** Converted categorical integers (`Exited`, `HasCrCard`, `IsActiveMember`, `Complain`) into **Factors** for accurate grouping.
3. **Metric Calculation:** Utilized nested `as.numeric(as.character())` transformations to ensure binary factor levels were correctly interpreted for percentage calculations.

---

## Repository Structure
*  '[Churn Analysis](https://bank-customer-churn-analysis.netlify.app/)': for live report
* `bank_churn.Rmd`: The source R Markdown file containing all documented cleaning steps.
* `index.html`: The final knitted report with all code hidden for professional presentation.

---
**Maria Aslam** 
 [LinkedIn](https://www.linkedin.com/in/maria-aslam-458860316/)
