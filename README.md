# Demand Forecasting & Early Warning Alert System 

## Overview
This project builds a demand forecasting system with a KPI-based early warning mechanism to detect forecast failures and trigger timely operational actions.

## Problem Statement
Forecasting alone is not enough in real-world operations. When forecasts start failing, teams need early signals to intervene before business impact occurs.

## Solution
This project implements:
- Demand forecasting using historical sales data
- Rolling error monitoring (MAPE-based)
- KPI thresholds to detect anomalies
- Alert classification (LOW, MEDIUM, HIGH)
- Action recommendations for operations teams

## Dataset
The dataset used is the Online Retail (UK) dataset.

You can download it from:
https://archive.ics.uci.edu/ml/datasets/online%2Bretail

## Project Workflow
1. Data loading and inspection
2. Data cleaning and daily aggregation
3. Baseline demand forecasting
4. Forecast error tracking
5. KPI-based alert system
6. Action recommendation layer

## Key Features
- Time-series demand forecasting
- Rolling error monitoring
- Early warning alert system
- Decision-support recommendations
- Exportable alert log

## Output
The final output includes:
- Forecast vs actual comparison
- Rolling error metrics
- Alert classification
- Action recommendations
- Exported alert dataset (`alert_output.csv`)

## Tools Used
- Python
- Pandas
- Matplotlib

## Conclusion
This project demonstrates how forecasting systems can be extended into operational decision-support tools by integrating monitoring and alert mechanisms.
