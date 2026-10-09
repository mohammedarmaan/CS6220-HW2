# CS 6220 – Homework 2: Linear Regression and Regression Trees

From-scratch implementations of a noisy data generator, linear regression (normal equation),
and a regression tree with recursive binary splits. No ML libraries are used for the models.

## Setup
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt

## Run
jupyter notebook program.ipynb
Then select "Run All". All plots and tables are produced in the notebook.

## Contents
- `generate_noisy_dataset`, `split_data`: synthetic data with uniform noise, fixed 80/20 split
- `fit`, `predict`, `evaluate_model`: linear regression via β = (XᵀX)⁻¹XᵀY and RMSE
- `best_split`, `RegressionTree`: regression tree with fit, predict, visualize, stats
- Experiments for report questions 3–11
