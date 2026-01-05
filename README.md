# Aadhaar Enrolment and Update Analysis (UIDAI-DATA-HACKATHON-2026)

## Project Overview

This project, developed for the **UIDAI-DATA-HACKATHON-2026**, presents a comprehensive data analysis and insights report on the Aadhaar enrolment and update system. The goal is to uncover significant demographic, geographic, and temporal trends, identify critical data quality issues, and provide strategic recommendations for system improvement and resource allocation.

## Data Scope

*   **Dataset Period:** March 2025 - December 2025
*   **Total Records Analyzed:** 4,933,437 (Enrolment, Biometric Updates, Demographic Updates)
*   **Geographic Coverage:** 55 States/UTs, 985 Districts, 19,463 Pincodes

## Key Findings

The analysis revealed several critical insights:

1.  **Demographic Disparity:** A significant gap in adult enrolment, with only **3.1%** of total enrolments belonging to the adult category (18+ years).
2.  **Update Efficiency Concern:** **46 states** recorded an update rate exceeding **1000%** of their enrolment rate, suggesting potential systemic data quality issues.
3.  **Temporal Volatility:** The system exhibits high volatility, with a **215% average monthly growth rate** and significant seasonal peaks.
4.  **Risk States:** **11 states** show declining enrolment trends, indicating a risk of reduced coverage in certain regions.

## Methodology

The analysis employed a multi-dimensional approach:

*   **Data Preprocessing:** Rigorous cleaning, duplicate removal (up to 22.9% in some datasets), and feature engineering.
*   **Statistical Analysis:** Descriptive statistics, correlation analysis, and distribution analysis.
*   **Temporal Analysis:** Time series decomposition, growth rate calculation, and seasonal pattern detection.
*   **Geographic Analysis:** State-wise, district-wise, and pincode-level clustering to assess regional disparity.
*   **Anomaly Detection:** Z-score calculation and outlier detection to identify data quality concerns.

## Strategic Recommendations

The report proposes a three-pronged strategy:

*   **HIGH Priority:** Data Quality Enhancement and Declining State Intervention.
*   **MEDIUM Priority:** Adult Enrolment Campaign, Service Quality Improvement, and Geographic Expansion.

## Team

This project was prepared by:

*   **Rohit**
*   **Darniga**

## Reproduction and Technical Stack

The full analysis is detailed in the accompanying report, `Aadhaar_Analysis_Report_Final.pdf`.

The analysis was conducted using the following technical stack:

*   **Language:** Python 3.x
*   **Libraries:** `pandas`, `matplotlib`, `seaborn`, `scipy`, `sklearn`
*   **Data Source:** UIDAI Datasets (March-December 2025)

To reproduce the analysis, ensure the required libraries are installed and the raw data files are placed in the appropriate directory structure as outlined in the original technical appendix (now removed for conciseness).
