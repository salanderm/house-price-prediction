# House Price Prediction Using Linear Regression

This project predicts house prices based on square meter (`metrekare`) data using a **linear regression model**. It focuses on exploring the relationship between the size of a house and its price.

## Project Overview

### Features:
- **Input**: Square meter (`metrekare`) data.
- **Output**: Predicted house price (`fiyat`).
- **Code-Driven**: All logic and implementation are embedded within code cells.
- **Analysis**: 
  - Loading and preprocessing data using `pandas`.
  - Training a linear regression model with `scikit-learn`.
  - Visualizing results with `matplotlib`.

## Project Structure

### Files:
- **main.ipynb**: Contains the code for data analysis, modeling, and visualization.
- **metrekare_fiyat.csv**: The dataset used in the project, which includes:
  - `metrekare`: House area in square meters.
  - `fiyat`: Corresponding house price.

### Code Highlights:
1. **Data Loading**:
   - The dataset is loaded and inspected using `pandas`.
2. **Modeling**:
   - A linear regression model is implemented to predict house prices.
3. **Evaluation**:
   - The performance of the model is visualized and evaluated using metrics and plots.

## How to Run

1. **Setup**:
   - Install Python 3.x and Jupyter Notebook.
   - Install required libraries:
     ```bash
     pip install pandas matplotlib scikit-learn
     ```

2. **Run the Notebook**:
   - Open `main.ipynb` in Jupyter Notebook or JupyterLab.
   - Execute cells sequentially to preprocess the data, train the model, and visualize predictions.

3. **Input New Data**:
   - Update or replace `metrekare_fiyat.csv` with new data for predictions.

## Requirements

- Python 3.x
- Libraries: `pandas`, `matplotlib`, `scikit-learn`

## Outputs

- Predicted house prices for the given square meter data.
- Visualizations of the regression model and its predictions.
