# County Rainfall and Planting Advisory

An exploratory data analysis and agricultural advisory project analyzing monthly rainfall patterns across five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa, and Machakos.

## Overview

This project cleans station weather data, analyzes monthly rainfall distributions using NumPy, determines optimal consecutive two-month planting windows, flags dry months (< 50 mm), and produces actionable planting guidance for agricultural support initiatives.

## Key Findings & Summary

| County | Annual Total (mm) | Wettest Month | Dry Months (<50 mm) | Recommended Planting Window |
|---|---|---|---|---|
| Nairobi | 1,045 | April | 4 | April–May |
| Nakuru | 916 | April | 3 | April–May |
| Kisumu | 1,371 | April | 0 | April–May |
| Mombasa | 1,075 | May | 2 | April–May |
| Machakos | 811 | November | 6 | November–December |

*Note on Data Quality:* Missing records for Machakos (April and September) were imputed using the station's rounded valid mean (68 mm).

## Project Structure

- `county_rainfall_advisory.ipynb`: Jupyter notebook containing data cleaning, matrix transformations, statistical summaries, and advisory generation.
- `rainfall_summary.csv`: Exported summary table with calculated totals, peak months, dry periods, and planting recommendations.
- `requirements.txt`: Python package dependencies (`numpy`).

## Requirements & Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open and run `county_rainfall_advisory.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
