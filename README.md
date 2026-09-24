# Bikers Portfolio — Bike Share Data Analysis

A Power BI project analyzing bike-share ridership data across two years to uncover usage trends, rider behavior, and cost/revenue patterns.

## 📌 Project Overview

This project explores bike-share trip data to understand how ridership changes over time, which rider segments drive volume, and how those patterns relate to operating costs. The analysis is delivered as an interactive Power BI dashboard built on cleaned and modeled trip-level data.

## 🎯 Objectives

- Consolidate and clean two years of raw trip data into an analysis-ready model
- Identify seasonal, monthly, and time-of-day ridership trends
- Compare rider segments (e.g. casual vs. member usage patterns)
- Combine ridership volume with cost data to surface cost-efficiency insights
- Present findings through an interactive, decision-ready Power BI dashboard

## 🗂️ Repository Contents

| File | Description |
|---|---|
| `Bike analysis.pbix` | Power BI report containing the data model, DAX measures, and dashboard visuals |
| `bike_share_yr_0.csv` | Trip-level bike-share data for year 1 |
| `bike_share_yr_1.csv` | Trip-level bike-share data for year 2 |
| `cost_table.csv` | Supporting cost/rate data used for cost analysis |

## 🛠️ Tools & Skills Used

- **Power BI** — data modeling, DAX measures, interactive dashboarding
- **Power Query** — data cleaning, transformation, and merging multi-year datasets
- **SQL** — data exploration and validation
- Data analysis fundamentals — trend analysis, segmentation, cost comparison

## 🔍 Approach

1. **Import & clean** — Loaded both years of trip data and the cost table into Power BI, standardized fields, handled missing/duplicate records, and merged the two years into a single ridership dataset.
2. **Model** — Built relationships between the trip data and cost table to support combined ridership + cost analysis.
3. **Analyze** — Used DAX measures to calculate ride counts, trends over time, and cost-related metrics by segment.
4. **Visualize** — Designed an interactive Power BI dashboard with filters/slicers so findings can be explored by period and rider segment.

## 📊 Key Insights

_(Add 3–4 bullet takeaways from your dashboard here, e.g. peak ridership months, casual vs. member split, cost-per-ride trends.)_

## ▶️ How to View

1. Download `Bike analysis.pbix`
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the slicers/filters on the dashboard to explore ridership and cost trends

## 👤 Author

**Raghavendra**
Data & Analytics enthusiast — SQL | Power BI
