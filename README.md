# Vehicle Price Prediction Project

## Overview
This project aims to predict the prices of vehicles using machine learning techniques. The workflow includes exploratory data analysis (EDA), data preparation, baseline modeling, and a series of experiments with different regression algorithms. The project is organized into several Jupyter notebooks, each focusing on a specific stage of the data science process.

## Project Structure
- **36106_26AU_AT1_26040826_Aryan_Goel_a_EDA.ipynb**: Exploratory Data Analysis (EDA) of the vehicle dataset, including data visualization and initial insights.
- **36106_26AU_AT1_26040826_Aryan_Goel_b_Preparation.ipynb**: Data cleaning, feature engineering, and preparation of training, validation, and test sets.
- **36106_26AU_AT1_26040826_Aryan_Goel_c_Baseline.ipynb**: Establishes a baseline model using a constant mean predictor to set a performance floor.
- **36106_26AU_AT1_26040826_Aryan_Goel_d_experiment_1.ipynb**: Experiment 1 — Multivariate Linear Regression.
- **36106_26AU_AT1_26040826_Aryan_Goel_e_experiment_2.ipynb**: Experiment 2 — ElasticNet Regression with feature selection and regularization.
- **36106_26AU_AT1_26040826_Aryan_Goel_f_experiment_3.ipynb**: Experiment 3 — K-Nearest Neighbors (KNN) Regression.
- **36106/assignment/AT1/data/**: Contains all data files, including raw and processed CSVs for training, validation, and testing.

## Data Files
- `vehicles_price_training.csv`, `vehicles_price_validation.csv`, `vehicles_price_testing.csv`: Raw data splits.
- `X_train.csv`, `X_val.csv`, `X_test.csv`: Feature matrices for each split.
- `y_train.csv`, `y_val.csv`, `y_test.csv`: Target price values for each split.

## Methodology
1. **EDA**: Understand data distributions, missing values, and feature relationships.
2. **Preparation**: Clean data, engineer features, and split into train/val/test sets.
3. **Baseline**: Use a constant mean predictor to establish minimum performance.
4. **Experiment 1**: Apply linear regression to model relationships between features and price.
5. **Experiment 2**: Use ElasticNet for regularization and feature selection.
6. **Experiment 3**: Explore non-linear relationships with KNN regression.

## Results Summary
- All experiments significantly outperform the baseline, confirming the value of engineered features.
- ElasticNet provides a sparser, more interpretable model with similar or better performance than plain linear regression.
- KNN explores local similarity in feature space for further improvements.

## Requirements
- Python 3.x
- pandas, numpy, scikit-learn, seaborn, altair, IPython

## How to Run
1. Open the notebooks in order, starting from EDA to Experiment 3.
2. Ensure all data files are present in the `36106/assignment/AT1/data/` directory.
3. Run each cell sequentially for reproducible results.

## Author
Aryan Goel (26040826)

---





