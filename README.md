# Predicting Kansas Metropolitan Housing Pricing Changes

## Project Overview
Homeownership is an important financial goal, but changing housing prices can make it difficult for potential buyers to plan. This project investigates the economic and housing market variables associated with quarterly housing-price changes across selected Kansas regions (including Kansas City, Wichita, Lawrence, Manhattan, etc.).

## Data Sources
* **Primary Dataset:** Federal Housing Finance Agency (FHFA) House Price Index (HPI) tracking historical quarterly changes in single-family home values.
* **Supplementary Data:** U.S. Census Bureau, Bureau of Labor Statistics, and Federal Reserve (tracking unemployment rates, building permits, and mortgage rates).

## Methodology & Modeling Approach
* **Target Variable:** Quarterly percentage growth calculated from the HPI.
* **Train/Test Split:** Chronological split using the earliest 75% of quarters for training and the most recent 25% for testing to prevent data leakage.
* **Models:** 
  1. *Baseline Model:* Predicts that next-quarter growth will equal the previous quarter's growth.
  2. *Multiple Linear Regression Model:* Driven by past price-growth, unemployment rates, building permits, and mortgage rates for straightforward coefficient interpretation.
* **Evaluation Metrics:** Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and $R^2$ Score.

## Current Status (Nov. 10 Update)
* Repository initialized and data sources identified.
* [Add a 1-2 sentence update here on what you've accomplished by Nov. 10, e.g., "Completed initial data ingestion and exploratory data analysis."]
