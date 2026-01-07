# Olist eCommerce Data Analysis Project

## Project Overview
This project involves a comprehensive analysis of the **Olist eCommerce dataset**, which contains 100k+ anonymized orders from 2016 to 2018 in Brazil. The goal was to extract actionable insights regarding customer geography, sales seasonality, and logistics performance.

## Objectives
* **Analyze** customer distribution across various Brazilian states.
* **Identify** seasonality and peak sales periods.
* **Determine** top-performing product categories.
* **Assess** shipping performance by comparing estimated vs. actual delivery timelines.

## Technologies Used
* **SQL** (PostgreSQL)
* **Dataset:** [Olist Brazilian eCommerce on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Key Findings
1. **Geographic Concentration:** São Paulo (SP) represents the largest customer hub.
2. **Sales Peaks:** Identified November 24, 2017 (Black Friday) as the highest volume day in the dataset.
3. **Logistics Performance:** Used Window Functions to benchmark individual deliveries against monthly averages, highlighting specific months where logistics efficiency dropped.

## How to Run the Queries
1. Download the CSV files from the Kaggle link above.
2. Import the datasets into your SQL editor (PostgreSQL recommended).
3. Run the scripts provided in the `/scripts` folder.
