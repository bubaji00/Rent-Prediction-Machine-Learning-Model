# Rent Prediction Machine Learning Model

This project predicts rental prices using a dataset from UC Irvine that consists of 10,000 classified apartment listings. Two machine learning models, Multiple Linear Regression (MLR) and Decision Trees, are employed to analyze the data and predict rent prices based on key apartment features like size, location, and pet policies.

## Project Files

- `data.csv`: The dataset containing apartment listings.
- `model.py`: Python script to build, train, and evaluate the MLR and Decision Tree models.
- `analysis.ipynb`: Jupyter notebook for data exploration, visualization, and model performance analysis.

## Key Features

- **Multiple Linear Regression (MLR)**: Evaluates linear relationships between rent price and apartment features.
- **Decision Tree**: Explores non-linear relationships and handles outliers in the dataset.
- **Data Preprocessing**: Includes cleaning, one-hot encoding, and feature selection for modeling.

## Results

- MLR Model: Achieved an R² score of 0.552 with a Mean Squared Error (MSE) of 93,453.
- Decision Tree Model: After tuning, achieved an R² score of 0.496.

## Usage

1. Clone this repository.
2. Run the following command to interact with Streamlit UI:
     - Windows: py -m streamlit run app_model4.py
     - Linux or macOS: python3 -m streamlit run app_model4.py
4. Explore detailed data analysis and visualizations in the .ipynb file.
