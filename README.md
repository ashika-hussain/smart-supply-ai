# smart-supply-ai

Inventory Planning

This project is part of my learning in Python and machine learning. It combines my background in computing with my experience working in retail operations.

## Summary

SmartRetailAI is a machine learning-based model that predicts expected product demand in a retail environment.

## Database used

Retail Store Inventory from Kaggle

## Key Features

- Uses XGBoost to predict units sold per product
- Accepts input including:
  - Product ID
  - Region, Category, Weather Condition, Seasonality
  - Price, Discount, Competitor Pricing
- Calculates recommended order quantities based on forecast vs inventory
- Simulates promotion impact based on historical uplift (on progress)

## How It Works

1. Csv data is used to train a regression model
2. Future product and environment conditions are passed into the model
3. The model returns predicted sales volume
4. Output includes product ID, predicted demand, inventory level, and suggested reorder quantity
