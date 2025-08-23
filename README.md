# Expenditure Modelling & Transformation (OJT 2025) 🚧📊

## Project Overview
Analyze **rural road project spending** under PMGSY using **R**.  
Goal: **Identify key factors affecting expenditure** and **build accurate prediction models**.  

- **Dataset:** 2,273 records (states + districts)  
- **Methods:** Data cleaning → Visualization → Regression (Lasso/Ridge/PLS)  
- **Best Model:** **Partial Least Squares (RMSE ≈ 591.9 Lakhs)**  

## Key Findings
- **Main drivers:** Cost 💰 • Road length 🛣️ • State GDP 📈 • Scheme type  
- **Political impact:** Higher spending in BJP/Congress/BJD/TMC/DMK states  
- **Outcome:** Better **fund planning** & **transparency**  

## How to Run
```r
install.packages(c("dplyr","caret","glmnet","ggplot2","rsample","vip"))
df <- read.csv("ROAD_WORK_PMGSY.csv")
# Clean → Transform → Model → Evaluate
