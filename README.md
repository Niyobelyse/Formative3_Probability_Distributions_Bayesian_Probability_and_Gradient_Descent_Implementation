# Probability Distributions, Bayesian Probability, and Gradient Descent Implementation

This repository contains Jupyter notebooks and supporting files that demonstrate key concepts in probability distributions, Bayesian probability, and linear regression using gradient descent and optimization techniques. The code is written in Python and leverages libraries such as Matplotlib, and SciPy.

## Repository Structure
- Uses NumPy for numerical operations
- **gradient_descent.ipynb**  
  Implements linear regression using mean squared error (MSE) loss and parameter optimization via SciPy's `minimize` function. Includes data visualization and result interpretation.

- **exponential_distribution.ipynb**  
  Demonstrates the exponential probability distribution, including PDF calculation, visualization, and parameter manipulation.

- **Bayesian.ipynb**  
  Implements Bayesian probability calculations, including helper functions for computing posterior probabilities and marginal likelihoods.

- **Gradient_discent_calculations.pdf**  
  Contains supporting mathematical derivations and explanations for gradient descent.

## Features

- Utilizes SciPy's `minimize` function for parameter optimization
- Visualizes regression lines and data points with Matplotlib
- Modular code structure for easy understanding and extension
- Demonstrates exponential and Bayesian probability concepts

## How It Works

1. **Data Preparation**: Defines data points for linear regression and probability distributions.
2. **Model Prediction**: Implements functions to predict values using linear and probabilistic models.
3. **Loss Function**: Calculates mean squared error for regression.
4. **Optimization**: Uses SciPy's `minimize` to find best-fit parameters.
5. **Visualization**: Plots data, fitted regression lines, and probability distributions.

```

## Running the Notebooks

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open any of the `.ipynb` files to explore the code and visualizations.

## Example Usage

**Linear Regression (from `gradient_descent.ipynb`):**
```python
x_data = np.array([1, 3])
y_data = np.array([3, 6])
optimized_params, final_cost = optimize_parameters(x_data, y_data)
m_opt, b_opt = optimized_params
plot_regression_line(x_data, y_data, m_opt, b_opt)
```

**Exponential Distribution (from `exponential_distribution.ipynb`):**
```python
x, y = generate_distribution(mean_time=2)
plot_distribution(x, y)
```




