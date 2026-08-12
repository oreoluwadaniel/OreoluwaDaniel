# Portfolio Map

This document explains how the public repositories are organized.

## Current flagship repositories

These are the repositories to review first when assessing my work:

1. `data-analytics-etl-portfolio` - CRM, HR, inventory, and sales ETL with data-quality controls.
2. `everdale-retail-analytics` - retail revenue, margin, customer, forecasting, and data-quality analysis.
3. `kavora-crm-migration-data-governance` - CRM migration, normalization, matching, reconciliation, and governance.
4. `bloomcrest-revenue-intelligence` - PostgreSQL revenue, CRM, customer economics, pipeline, and validation work.
5. `weatherintel-global-weather-analytics` - NOAA ingestion, PostgreSQL modeling, data-quality auditing, and forecast evaluation.
6. `stock-performance-risk-monitoring` - market data validation, risk measures, PostgreSQL modeling, and walk-forward forecasting.
7. `Brightwatt-Operations-Automation` - connected operational workflow design for customer intake, orders, inventory, payments, and field service.
8. `ab-testing-case-studies` - controlled experiments, statistical testing, uncertainty, and product decisions.

## Consolidated domain repositories

Some earlier projects were built as separate repositories before the portfolio was reorganized. Where a combined repository now exists, it is the current version.

- `credit-risk-banking-portfolio` replaces the separate credit-risk, NPL, roll-rate, loan-default, and fraud case-study repositories as the main credit-risk collection.
- `oil-gas-analytics-portfolio` groups well economics, pricing and margin, and rig reliability work.
- `larkmoor-property-portfolio` groups property pricing, rental yield, vacancy, and portfolio optimization work.
- `saas-analytics-portfolio` groups recurring revenue, product usage, and billing analytics.
- `insurance-risk-pricing-analytics` groups claims, pricing, fraud, and macroeconomic insurance analysis.

## Historical repositories

Older repositories are kept where they contain useful work or project history. They should not be mistaken for separate current flagship projects when a newer consolidated repository exists.

The current portfolio pages link to the consolidated versions first.

## Documentation standard

Public case studies should make five things clear:

1. The business question.
2. The data grain and source.
3. The checks used to validate the analysis.
4. What the data actually showed.
5. What decision the result supports.

Claims about measured business results are only made when the repository contains evidence for them. Synthetic projects are identified as synthetic. Designed workflows are not described as deployed systems.

## Language standard

Project documentation uses plain business language. It avoids inflated claims, unexplained technical terms, vague descriptions, and statements that imply production deployment when the repository only contains a design or prototype.
