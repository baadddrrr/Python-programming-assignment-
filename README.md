# SKEE1033 Group Assignment (2025/2026) — README

## Group Members
- **BADR ANAS AL MOKDAD** — **A25KE4015**
- **Abdelaziz Alsayed** — **A24KE4080**
- **MOHAMED ELHADI** — **A25KE0028**
- **Omar Elgohary** — **A25KE0036**
- **Mazin Mohamed** — **A25KE0021**

## Project Overview
This project analyses household electricity consumption data (2018–2022) and includes:
- Data cleaning (handling missing values and outliers)
- Descriptive statistics by region
- Visualisation of consumption trends and relationships
- Predictive modelling using Linear Regression to estimate electricity cost

## Files Included
- `dataset_student (2).csv` — Original dataset  
- `dataset_cleaned.csv` — Cleaned dataset (after handling NaNs/outliers and recomputing cost)  
- `task1_data_cleaning.py` — Task 1: Data cleaning  
- `task2_descriptive_analysis.py` — Task 2: Summary statistics + correlation  
- `task3_visualisation.py` — Task 3: Trend plots + scatter plot  
- `task4_predictive_model.py` — Task 4: Linear regression + evaluation + actual vs predicted plot  

## How to Run (in order)
1. Run **Task 1** to generate the cleaned dataset:
   - `python task1_data_cleaning.py`
2. Run **Task 2** for descriptive analysis:
   - `python task2_descriptive_analysis.py`
3. Run **Task 3** to display plots:
   - `python task3_visualisation.py`
4. Run **Task 4** for prediction results and plot:
   - `python task4_predictive_model.py`

## Notes
- Missing values are handled using **linear interpolation by region over time**.
- Electricity cost is computed using the tariff rate:
  - **Cost_RM = 0.57 × Consumption_kWh**
- Model evaluation uses **R²** and **MAE** on an **80/20 train-test split**.
