# BNP Paribas SA Financial Analysis (FY2022–FY2024)

A three-year historical financial analysis of BNP Paribas SA using publicly available annual reports, consolidated financial statements, Pillar 3 disclosures, annual-results materials, and related investor reporting.

This project demonstrates financial analysis, banking-sector analysis, financial-risk interpretation, reporting, reconciliation, and analytical documentation skills relevant to Financial Analyst, Banking Analyst, Financial Risk Analyst, and Big 4 Financial Services roles in Luxembourg and the wider European financial-services market.

---

## Project Objective

The purpose of this project is to evaluate BNP Paribas SA's financial performance, capital strength, liquidity position, credit quality, and operating efficiency over FY2022–FY2024.

The analysis is designed to answer the following business question:

> How did BNP Paribas perform through a changing European interest-rate cycle, and what are the key implications for profitability, solvency, liquidity, and credit quality?

---

## Scope

### Entity

BNP Paribas SA (Consolidated Group)

This is **not** a standalone analysis of BGL BNP Paribas SA. BGL BNP Paribas is referenced only as part of the Luxembourg relevance context.

### Period

FY2022–FY2024

### Reporting Framework

- IFRS as adopted by the European Union
- IFRS 9 Expected Credit Loss framework
- IFRS 17 insurance-transition considerations
- ECB Single Supervisory Mechanism (SSM)
- SREP supervisory context
- CRD VI / CRR3 regulatory environment
- Pillar 3 regulatory disclosures

### Currency

EUR millions unless otherwise stated.

### Reporting Basis

FY2022 figures affected by the IFRS 17 / related insurance IFRS 9 transition use BNP Paribas' **restated comparative disclosures where applicable** so that the analytical series is presented on a consistent basis with FY2023–FY2024.

Reported and restated FY2022 values are retained separately in the workbook's `IFRS17_RESTATEMENT_NOTE` sheet. The workbook does not silently mix the two bases in its analytical series.

---

## Deliverables

### Excel Financial Analysis Workbook

**File**

`BNP_Paribas_3Y_Financial_Analysis_BNP_2022-2024.xlsx`

Contains:

- Executive KPI Scorecard
- Income Statement Analysis
- Balance Sheet Analysis
- Cash Flow Analysis
- Variance Bridge Analysis
- Profitability Ratio Analysis
- Liquidity Ratio Analysis
- Capital Adequacy Analysis
- Asset Quality Analysis
- Efficiency Analysis
- Earnings Waterfall Analysis
- Trend Dashboard
- Validation Checks
- Source Register
- IFRS 17 / IFRS 9 Restatement Documentation
- Ratio Dictionary
- Data Dictionary
- Benchmarks Register
- Workbook Methodology
- Analytical Inputs

### Analyst Report

**File**

`BNP_Paribas_Analyst_Note_2022-2024.pdf`

A concise analyst-style narrative covering:

- Profitability and revenue mix
- Capital adequacy
- Liquidity and funding
- Credit quality and IFRS 9 indicators
- Efficiency
- Key risks and watchpoints
- Forward-looking analytical scenarios
- Relevant regulatory context

---

## Key Areas of Analysis

### Profitability

Metrics analysed include:

- Net Banking Income (NBI)
- Net Interest Income (NII)
- Return on Equity (ROE)
- Return on Tangible Equity (ROTE)
- Return on Assets (ROA)
- Net Interest Margin (NIM)
- Earnings Per Share (EPS)
- Cost-to-Income Ratio (CIR)

### Capital Adequacy

Metrics analysed include:

- CET1 Ratio
- Tier 1 Ratio
- Total Capital Ratio
- Leverage Ratio
- Risk-Weighted Assets (RWA)

Regulatory reference levels are used for analytical comparison only. The project does **not** assert a BNP-specific SREP requirement or supervisory approval.

### Liquidity

Metrics analysed include:

- Liquidity Coverage Ratio (LCR)
- Net Stable Funding Ratio (NSFR)
- Loan-to-Deposit Ratio
- High Quality Liquid Assets (HQLA)

### Credit Risk / Asset Quality

Metrics analysed include:

- NPL Ratio
- Coverage Ratio
- Standard Cost of Risk
- Other net losses for risk on financial instruments
- Stage 1 Expected Credit Losses
- Stage 2 Expected Credit Losses
- Stage 3 Impairment Allowances

The workbook keeps **Cost of Risk** separate from **other net losses for risk on financial instruments** rather than combining the two under a single Cost of Risk label.

### Efficiency

Metrics analysed include:

- Cost-to-Income Ratio
- Operating Leverage
- Revenue Growth
- Expense Growth

---

## Controls and Validation

The workbook includes a dedicated control framework covering:

- Balance-sheet reconciliation
- Cash-flow validation and reconciliation
- Ratio consistency checks
- Variance and waterfall reconciliation
- Source-completeness controls
- Documentation-completeness controls
- Cross-sheet validation checks
- Reported-versus-restated FY2022 controls

The workbook contains **23 validation checks**, supported by visible source registers, methodology documentation, ratio definitions, data definitions, and analytical input schedules.

The control register is intended to be reviewed alongside the underlying calculations rather than treated as a substitute for them.

---

## Data Sources

Primary sources include:

- BNP Paribas Annual Reports / Universal Registration Documents
- Consolidated Financial Statements
- Full-Year Results Presentations
- Annual-results releases
- Pillar 3 Regulatory Disclosures

External analytical references include:

- ECB Supervisory Banking Statistics
- European Banking Authority (EBA) Risk Dashboard

Detailed source mapping and workbook locations are documented in the `SOURCE_REGISTER` sheet.

---

## Methodology

The project follows a controlled historical financial-analysis workflow:

1. Identify the reporting entity and perimeter
2. Identify official source documents
3. Extract and standardise financial-statement data
4. Separate reported and restated FY2022 figures where applicable
5. Calculate financial ratios using visible analytical inputs
6. Analyse year-on-year movements and trends
7. Reconcile major statement and waterfall movements
8. Compare selected metrics with clearly identified sector references
9. Interpret the financial and risk implications
10. Validate calculations and document limitations

Data were manually extracted from official BNP Paribas documents and standardised in Excel. The workbook does not claim a production data pipeline or automated source ingestion process.

---

## Key Analytical Findings

The completed analysis indicates that BNP Paribas entered FY2024 with stronger earnings and a marked efficiency recovery.

- Net Banking Income increased from **€45,430M in restated FY2022 to €48,831M in FY2024**.
- Net income attributable to equity holders increased from **€9,848M in restated FY2022 to €11,688M in FY2024**, equivalent to an approximately **8.9% two-year CAGR**.
- FY2024 CIR improved to **61.83%**.
- CET1 closed FY2024 at **12.87%**.
- LCR and NSFR closed FY2024 at **137%** and **111.75%**, respectively.
- NPL improved to **1.6%**, while coverage declined to **69.7%**.
- Standard Cost of Risk increased slightly in FY2024, while other net risk losses declined substantially.

These findings are analytical interpretations of the historical data and are not forecasts, investment recommendations, or supervisory assessments.

---

## Reproduction / Review Guide

A reviewer can follow the project in this order:

1. Open the workbook `📌 COVER` and `📊 EXECUTIVE_SUMMARY` sheets to understand scope and headline findings.
2. Review `📄 INCOME_STATEMENT`, `🏦 BALANCE_SHEET`, and `💰 CASH_FLOW` for the underlying statements.
3. Review the ratio schedules for profitability, liquidity, capital, asset quality, and efficiency.
4. Review `IFRS17_RESTATEMENT_NOTE` to distinguish reported and restated FY2022 values.
5. Review `ANALYTICAL_INPUTS` for the visible denominator assumptions supporting ROE, ROTE, ROA, and NIM.
6. Review `SOURCE_REGISTER`, `RATIO_DICTIONARY`, `DATA_DICTIONARY`, and `WORKBOOK_METHODOLOGY` for traceability and definitions.
7. Review `🔍 CHECKS` for validation status and control evidence.
8. Read the accompanying analyst note for the financial narrative and risk interpretation.

The workbook is designed for analytical review and interview discussion rather than as a production banking model.

---

## Important Limitations

- Annual data only
- Historical analysis only
- No forecasting or consensus estimates
- No valuation analysis
- No stress-testing model
- No claim of regulatory validation, supervisory approval, or production deployment
- FY2022 comparability follows BNP Paribas' disclosed IFRS 17 / related insurance IFRS 9 restatement perimeter
- IAS 7 cash and cash equivalents are reconciled separately from the balance-sheet central-bank cash line using the published component composition

---

## Disclaimer

This repository is an educational portfolio project intended to demonstrate financial-analysis, banking-sector analytical, reporting, reconciliation, and risk-interpretation skills.

It is not investment advice, credit advice, regulatory guidance, valuation advice, a credit-rating opinion, or a recommendation to buy, sell, or hold any security.

The regulatory terminology used in this project is included for analytical context. The project does not represent evidence that the author has performed regulated activities or that the workbook is approved, validated, or used by BNP Paribas or any supervisory authority.

Users should consult BNP Paribas' official publications and applicable regulatory sources for authoritative information.

---

**Author:** Joy Lorna  
**Target Roles:** Financial Analyst, Banking Analyst, Financial Risk Analyst, Business Intelligence Analyst, Big 4 Financial Services Consultant  
**Portfolio Purpose:** Professional portfolio demonstration
