# 🏦 Banking Sector Stress Testing Model & Resilience Framework

A comprehensive financial simulation and macroeconomic stress-testing framework evaluating four major commercial banks in India: **State Bank of India (SBI)**, **Punjab National Bank (PNB)**, **HDFC Bank**, and **Yes Bank**.

---

## 📌 Executive Summary

This repository contains a dynamic financial stress-testing model and analytical report designed to assess the resilience of Indian commercial banks under severe macroeconomic headwinds. Utilizing **FY24 baseline data**, the model projects key financial health metrics across three distinct scenarios: **Baseline**, **Moderate Stress** (COVID-19 shock replica), and **Severe Stress** (2015–16 NPA crisis with rate spikes).

The project integrates:
* **Financial Simulation Model (`.xlsx`)**: Interactive scenario engines, sensitivity matrices, and Early Warning Indicators (EWI).
* **Analytical Executive Report (`.pdf`)**: A concise report summarizing methodologies, comparative bank scorecards, and strategic capital preservation recommendations[cite: 3, 5].

---

## 📊 Core Financial Metrics Analyzed (FY24 Baseline)

| Key Financial Metric | SBI | PNB | HDFC Bank | Yes Bank |
| :--- | :---: | :---: | :---: | :---: |
| **Gross NPA (%)**[cite: 5] | 2.24%[cite: 3, 5] | 5.73%[cite: 3, 5] | 1.24%[cite: 3, 5] | 1.70%[cite: 3, 5] |
| **Capital Adequacy Ratio (CAR %)**[cite: 5] | 14.28%[cite: 3, 5] | 15.97%[cite: 3, 5] | 18.80%[cite: 3, 5] | 15.40%[cite: 3, 5] |
| **Net Interest Margin (NIM %)**[cite: 5] | 3.43%[cite: 3, 5] | 3.09%[cite: 3, 5] | 3.60%[cite: 3, 5] | 2.40%[cite: 3, 5] |
| **Return on Assets (ROA %)**[cite: 5] | 1.04%[cite: 3, 5] | 0.77%[cite: 3, 5] | 1.98%[cite: 3, 5] | 0.30%[cite: 3, 5] |
| **Return on Equity (ROE %)**[cite: 5] | 20.32%[cite: 3, 5] | 16.48%[cite: 3, 5] | 16.10%[cite: 3, 5] | 3.10%[cite: 3, 5] |
| **Liquidity Coverage Ratio (LCR %)**[cite: 5] | 129.02%[cite: 3, 5] | 141.60%[cite: 3, 5] | 115.00%[cite: 3, 5] | 116.10%[cite: 3, 5] |

*(Data Source: Published FY24 Financial Results)*[cite: 3, 5]

---

## 🎯 Macroeconomic Stress Scenarios

1. **Baseline Scenario (FY24 Actuals):**
   * Represents the current operational baseline[cite: 3, 5].
   * All banks satisfy statutory minimum capital requirements (11.5% CAR including CCB)[cite: 3, 5].
   * HDFC Bank leads in overall asset quality (1.24% GNPA) and return profile (1.98% ROA)[cite: 3, 5].

2. **Moderate Stress Scenario (COVID-19 Shock Replica):**
   * Simulates credit risk escalation, increasing portfolio GNPA ratios by **180–250 bps** across portfolios[cite: 3, 5].
   * High Provision Coverage Ratios (PCR) mitigate solvency risks, though Net Interest Margins (NIM) compress by **25–40 bps** due to slippages[cite: 3, 5].

3. **Severe Stress Scenario (2015–16 Crisis + 150 bps Rate Spike):**
   * Combines severe credit impairment with aggressive interest rate hikes[cite: 3, 5].
   * Evaluates capital cushion erosion across public and private sector banks[cite: 3, 5].
   * **HDFC Bank** maintains the highest capital headroom (CAR remaining above 15.2%), whereas **PNB** and **Yes Bank** experience significant margin compression and provisioning pressures[cite: 3, 5].

---

## 🏆 Resilience Scorecard Rankings

1. **HDFC Bank (Rank 1):** Superior capital headroom, strong earnings power, and minimal asset quality deterioration under stress[cite: 3, 5].
2. **State Bank of India (Rank 2):** High structural stability supported by a low-cost deposit franchise and systemic importance[cite: 3, 5].
3. **Punjab National Bank (Rank 3):** High Liquidity Coverage Ratio (141.60%) offers a substantial short-term buffer, though elevated baseline GNPA requires aggressive provisioning[cite: 3, 5].
4. **Yes Bank (Rank 4):** Rebuilding phase limits loss-absorption capacity; lower baseline NIM (2.40%) and ROA (0.30%) require tight risk controls[cite: 3, 5].

---

## 🚨 Early Warning Indicators (EWI) Dashboard

The framework tracks key threshold triggers to identify systemic and bank-specific risk vulnerabilities before capital erosion occurs[cite: 3, 5]:
* **Credit-to-Deposit (CD) Ratio Trigger:** $> 85\%$ (Monitors liquidity tightness and funding strain)[cite: 3, 5].
* **Liquidity Coverage Ratio (LCR) Trigger:** $< 110\%$ (Signals impending short-term liquidity risk)[cite: 3, 5].
* **NPA Slippage Acceleration:** Real-time sensitivity tracking on provision requirements[cite: 3, 5].

---

## 📁 Repository File Structure

```text
├── Banking_Sector_Stress_Testing_Model.xlsx   # Interactive financial model & scenario engine
├── Banking_Sector_Stress_Testing_Report.pdf  # Minimalist executive summary report
└── README.md                                  # Documentation and repository overview
