# Credit Risk Modelling Tools 

**Author:** Ikhwan Afif  
**Focus:** Quantitative Finance, Risk Automation, Python

## Overview
This repository contains Python scripts designed to automate key workflows in **Credit Risk Management** and **Regulatory Reporting**. These tools bridge the gap between fundamental financial analysis and technical execution, focusing on efficiency and scalability.

## Modules

### 1. Portfolio Stress Tester (`portfolio_stress_tester.py`)
A sensitivity analysis engine designed to simulate **ICAAP** (Internal Capital Adequacy Assessment Process) scenarios.
* **Function:** Simulates interest rate shocks (e.g., +50bps, +200bps).
* **Output:** Calculates the "Additional Burden" on borrowers and projects the impact on **Probability of Default (PD)**.
* **Use Case:** Asset Sensitivity Analysis and LCR (Liquidity Coverage Ratio) monitoring.

### 2. IFRS 9 Staging Logic (`ifrs9_staging_logic.py`)
An automated classifier for loan portfolios under the **IFRS 9** accounting standard.
* **Logic:** Categorizes assets into **Stage 1, 2, or 3** based on Days Past Due (DPD) and Significant Increase in Credit Risk (SICR) triggers.
* **Use Case:** Streamlining the provisioning process and reducing manual Excel errors during monthly reporting cycles.

## Technology Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy
* **Environment:** Google Colab

## Contact
For inquiries regarding these models or collaboration opportunities, please reach out via [LinkedIn](https://www.linkedin.com/in/ikhwan-afif-9151b0269/).
