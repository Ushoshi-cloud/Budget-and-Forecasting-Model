# Budget-and-Forecasting-Model
An Excel-based financial model for tracking expenses, forecasting budgets, and generating scenario-driven income statements.
# Budget and Forecasting Model

This repository contains an Excel-based model for managing operating expenses, forecasting future financials under multiple scenarios, and projecting income statements. It is suitable for startups, financial analysts, and business planners seeking a structured way to analyze financial performance.

## File Overview

- **Budget and Forecast Start.xlsx**: Main workbook with interconnected sheets for:
  - Actual Operating Expenses
  - Forecast Projections (Best, Base, Worst Cases)
  - Income Statement Forecast

---

## Sheets and Structure

### 1. Actual Expenses
- Captures historical operating expenses by:
  - Department (Marketing, Engineering, Support, HR)
  - Description (e.g., Paid Ads, Consulting, Software)
  - Monthly data from **Sep 2024 to Dec 2024**

### 2. Forecast
- Contains projections for the next year (Jan 2025 to Dec 2025) under three scenarios:
  - **Best Case** (30% increase)
  - **Base Case** (steady continuation)
  - **Worst Case** (30% decrease)
- Forecasted metrics include:
  - Monthly department-wise expenses
  - Cumulative annual planning

### 3. Income Statement
- Pulls data from the forecast sheet and calculates:
  - **Revenue**, **COGS**, **Gross Profit**
  - **Operating Expenses** by department
  - **Operating Income**, **Taxes**, and **Net Income**
- Assumptions include:
  - Price per unit
  - Units sold
  - CAC (Customer Acquisition Cost)
  - Tax rate
  - COGS and other income as a percentage of revenue

---

## Key Features

- Automated scenario analysis for financial planning
- Dynamic forecast calculations with adjustable growth/decline %
- Logical cell structuring with dollar-locked formulas for consistent referencing
- Income Statement integrates forecasted values to reflect projected profitability
- Customizable inputs for assumption-based planning

---

## Usage Instructions

1. Open the Excel file.
2. Adjust the scenario assumptions in the **Forecast** sheet (Top rows).
3. Update actuals in the **Actual Expenses** sheet as needed.
4. Switch between scenarios using the selector in the **Income Statement** sheet.
5. Review output financials including Net Income and Operating Profit.

---

## Ideal For

- MBA/Finance students creating forecasting models
- Early-stage startups for operational planning
- Analysts preparing scenario-based income statements
