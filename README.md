# 🏦 Banking Sector Stress Testing Model & Resilience Framework

A comprehensive financial simulation and macroeconomic stress-testing framework evaluating four major commercial banks in India: **State Bank of India (SBI)**, **Punjab National Bank (PNB)**, **HDFC Bank**, and **Yes Bank**.

---

## 📌 Executive Summary

This repository contains a dynamic financial stress-testing model and analytical report designed to assess the resilience of Indian commercial banks under severe macroeconomic headwinds. Utilizing **FY24 baseline data**, the model projects key financial health metrics across three distinct scenarios: **Baseline**, **Moderate Stress** (COVID-19 shock replica), and **Severe Stress** (2015–16 NPA crisis with rate spikes).

The project integrates:
* **Financial Simulation Model (`.xlsx`)**: Interactive scenario engines, sensitivity matrices, and Early Warning Indicators (EWI).
* **Analytical Executive Report (`.pdf`)**: A concise report summarizing methodologies, comparative bank scorecards, and strategic capital preservation recommendations.

---

## 📊 Core Financial Metrics Analyzed (FY24 Baseline)

| Key Financial Metric | SBI | PNB | HDFC Bank | Yes Bank |
| :--- | :---: | :---: | :---: | :---: |
| **Gross NPA (%)** | 2.24% | 5.73% | 1.24% | 1.70% |
| **Capital Adequacy Ratio (CAR %)** | 14.28% | 15.97% | 18.80% | 15.40% |
| **Net Interest Margin (NIM %)** | 3.43% | 3.09% | 3.60% | 2.40% |
| **Return on Assets (ROA %)** | 1.04% | 0.77% | 1.98% | 0.30% |
| **Return on Equity (ROE %)** | 20.32% | 16.48% | 16.10% | 3.10% |
| **Liquidity Coverage Ratio (LCR %)** | 129.02% | 141.60% | 115.00% | 116.10% |

*(Data Source: Published FY24 Financial Results)*

---

## 🎯 Macroeconomic Stress Scenarios

1. **Baseline Scenario (FY24 Actuals):**
   * Represents the current operational baseline.
   * All banks satisfy statutory minimum capital requirements (11.5% CAR including CCB).
   * HDFC Bank leads in overall asset quality (1.24% GNPA) and return profile (1.98% ROA).

2. **Moderate Stress Scenario (COVID-19 Shock Replica):**
   * Simulates credit risk escalation, increasing portfolio GNPA ratios by **180–250 bps** across portfolios.
   * High Provision Coverage Ratios (PCR) mitigate solvency risks, though Net Interest Margins (NIM) compress by **25–40 bps** due to slippages.

3. **Severe Stress Scenario (2015–16 Crisis + 150 bps Rate Spike):**
   * Combines severe credit impairment with aggressive interest rate hikes.
   * Evaluates capital cushion erosion across public and private sector banks.
   * **HDFC Bank** maintains the highest capital headroom (CAR remaining above 15.2%), whereas **PNB** and **Yes Bank** experience significant margin compression and provisioning pressures.

---

## 🏆 Resilience Scorecard Rankings

1. **HDFC Bank (Rank 1):** Superior capital headroom, strong earnings power, and minimal asset quality deterioration under stress.
2. **State Bank of India (Rank 2):** High structural stability supported by a low-cost deposit franchise and systemic importance.
3. **Punjab National Bank (Rank 3):** High Liquidity Coverage Ratio (141.60%) offers a substantial short-term buffer, though elevated baseline GNPA requires aggressive provisioning.
4. **Yes Bank (Rank 4):** Rebuilding phase limits loss-absorption capacity; lower baseline NIM (2.40%) and ROA (0.30%) require tight risk controls.

---

## 🚨 Early Warning Indicators (EWI) Dashboard

The framework tracks key threshold triggers to identify systemic and bank-specific risk vulnerabilities before capital erosion occurs:
* **Credit-to-Deposit (CD) Ratio Trigger:** $> 85\%$ (Monitors liquidity tightness and funding strain).
* **Liquidity Coverage Ratio (LCR) Trigger:** $< 110\%$ (Signals impending short-term liquidity risk).
* **NPA Slippage Acceleration:** Real-time sensitivity tracking on provision requirements.

---

## 📁 Repository File Structure

```text
├── Banking_Sector_Stress_Testing_Model.xlsx   # Interactive financial model & scenario engine
├── Banking_Sector_Stress_Testing_Report.pdf  # Minimalist executive summary report
└── README.md                                  # Documentation and repository overview
