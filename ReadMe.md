# California Housing Price Prediction

A Jupyter notebook-based machine learning project that predicts California housing prices using XGBoost, with full experimentation from data exploration to evaluation.

## Overview

This project explores the California housing dataset to build a regression model that predicts median house values. It walks through the complete machine learning workflow: loading and exploring the data, preprocessing, feature engineering, model training, and evaluation.

## Features

- Exploratory data analysis with Pandas and Seaborn
- Data preprocessing and cleaning
- Feature engineering
- XGBoost regression model training
- Model evaluation with MAE and R²
- Visualization of predicted vs. actual prices

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn / Matplotlib
- Scikit-learn
- XGBoost

## Project Structure

```text
California-Housing-Price-Prediction/
├── Project_1_House_Price_Prediction.ipynb   # Main analysis + model training
├── Images/                                  # Generated plots
│   ├── Actual Prices_VS_Predicted_Prices.jpg
│   ├── HeatMap_For_DataSet.jpg
│   └── Scatter_Plot_Actual Prices_VS_Predicted_Prices.jpg
└── ReadMe.md
```

## Methodology

```text
Load Data → EDA → Preprocessing → Feature Engineering → XGBoost Training → Evaluation
```

## Results

| Metric | Value |
|--------|-------|
| MAE    | 0.31  |
| R²     | 0.83  |

## Installation

```bash
git clone https://github.com/ahmedyasser1588/California-Housing-Price-Prediction.git
cd California-Housing-Price-Prediction
pip install -r requirements.txt
jupyter notebook
```

> Note: `requirements.txt` is not currently committed. Install the packages listed under Tech Stack if you do not have it.

## Usage

Open `Project_1_House_Price_Prediction.ipynb` in Jupyter and run the cells in order.

## Project Status

Completed — a training/learning project demonstrating a full ML workflow.

## Future Improvements

- Add a `requirements.txt` for reproducibility
- Try additional regressors and cross-validation
- Deploy the model behind an API
