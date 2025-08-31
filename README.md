# Basic Neural Network from Scratch for Regression on Walmart Sales Data

This project demonstrates a simple feedforward neural network for time series regression using Walmart sales data.

## Project Structure
- `basic_nn_regression.ipynb`: Main Jupyter notebook with all code, plots, and analysis.
- `data/walmart_sales/Walmart_Sales.csv`: Source data file (available on [Kaggle Walmart Sales Dataset](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)).

## Features
- **Data Exploration**: Visualizes sales trends and seasonality for a selected store.
- **Feature Engineering**: Adds week-of-year and lagged sales features.
- **Neural Network**: Implements a simple neural network from scratch (NumPy) with one hidden layer and L2 regularization.
- **Model Comparison**: Compares models with and without feature engineering using RMSE and MAPE metrics.
- **Visualization**: Plots actual vs. predicted sales for both models.

## Usage
1. Place the Walmart sales CSV in `data/walmart_sales/Walmart_Sales.csv`.
2. Open `basic_nn_regression.ipynb` in Jupyter or VS Code.
3. Run all cells to reproduce the analysis and results.
4. Adjust hyperparameters (hidden size, epochs, L2 lambda) in the notebook to experiment.

## Requirements
- Python 3.8+
- numpy
- pandas
- matplotlib
- scikit-learn

Install requirements with:
```bash
pip install numpy pandas matplotlib scikit-learn
```

## License
This project is for educational use only.