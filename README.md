# GCB Bank PLC — Financial Statement Analysis

## Problem
Analyse GCB Bank's financial performance and trends over five years using their publicly available annual reports to assess profitability, efficiency and risk profile.

## Approach
1. Extracted financial statement data from the annual report PDFs (largely using pdfplumber)
2. Calculated six core banking ratios: ROE, ROA, Equity-to-assets, cost-to-income, loan-to-deposit, Net Profit Margin
3. Visualised multi-year trends and interpreted drivers

## Key Findings
- 2022 was a particularly bad year, likely a lingering aftershock of COVID-19 and the lockdown
- Equity was cut nearly in half that year
- Most ratios were negatively affected by the loss made as well
- All ratios experienced substantial rebound growth in subsequent years

## Data Sourcing Note
- Financial statement data was extracted from GCB Bank's publicly filed annual reports (gcbbank.com.gh/downloads/reports).
- The updated report of 2022 was selected over the original issue.

## What I'd improve with more time
- Add a peer comparison against another GSE-listed bank
- Improve PDF extraction to minimise time spent cleaning
- Incorporate quarterly data for finer trend detection and analysis
- Perform some valuation (P/E, P/B) for an investment thesis like a true analyst