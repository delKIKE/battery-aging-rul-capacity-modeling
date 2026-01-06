# Battery Aging — RUL & Capacity Modeling (NASA Dataset)

This project applies machine learning regression models to predict battery **Remaining Useful Life (RUL)** and **capacity degradation** using the NASA battery aging dataset. The goal is to model battery health decline over time and evaluate how different algorithms perform on degradation-related targets.

## Project Overview
Lithium-ion batteries degrade as they undergo repeated charge and discharge cycles. Accurately estimating remaining useful life and capacity loss is critical for applications such as predictive maintenance, electric vehicles, and energy storage systems. This project explores data-driven approaches to estimate these quantities from historical battery aging data.

## What This Repository Contains
- `final_project.ipynb` — End-to-end notebook including:
  - Data loading and preprocessing  
  - Exploratory data analysis (EDA)  
  - Feature engineering  
  - Regression modeling for RUL and capacity  
  - Model evaluation and comparison  

## Models Used
The project evaluates multiple regression approaches, including:
- Linear regression
- Tree-based models
- Ensemble methods

Model performance is compared using appropriate regression metrics.

## Data
The dataset used in this project comes from the **NASA Battery Aging Dataset**.  
Due to size and licensing considerations, the raw dataset files are **not included** in this repository. Paths in the notebook may need to be updated to match the local data location.

## How to Run
1. Clone the repository
2. Install required dependencies
3. Open and run the notebook:
   ```bash
   jupyter notebook final_project.ipynb
