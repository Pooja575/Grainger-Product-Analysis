# Grainger-Product-Analysis(Power BI)

## Project Overview

This project presents an end-to-end product analytics dashboard built using Power BI on a simulated dataset inspired by Grainger’s product catalog.
The dashboard helps stakeholders analyze revenue performance, inventory health, customer ratings, and long-term sales trends from 2000–2024.

The goal was to demonstrate data cleaning, feature engineering, and executive-level dashboard design using real-world business metrics.

* Data Preparation
* Engineered features using Python (Pandas):
* Revenue (Price × UnitsSold)
* Low-stock flag (StockQty < 20)
* Sales level & price range bucketing
* Generated order dates (2000–2024) for trend analysis
* Exported clean dataset for Power BI consumption

## Dashboard Highlights
* KPI cards: Total Revenue, Units Sold, Avg Rating, % Low Stock
* Top products by revenue
* Revenue trend over time
* Inventory & product detail table
* Slicers for category, brand, and year

## Key Insights
* Revenue concentrated among top products
* Multiple items at low-stock risk
* Strong revenue growth from 2016–2023
* Higher ratings correlate with higher sales

## Outcome
* This dashboard acts as a single source of truth for:
* Monitoring product performance
* Identifying inventory risks
* Analyzing long-term revenue trends
* Supporting data-driven business decisions

## Tech Stack

Power BI | Python (Pandas) | Google Colab | CSV
