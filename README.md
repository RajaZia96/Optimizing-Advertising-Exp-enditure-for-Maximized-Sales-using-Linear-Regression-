# Optimizing-Advertising-Exp-enditure-for-Maximized-Sales-using-Linear-Regression-
This project explores how different advertising mediums—TV, radio, and newspapers—affect product sales, using Linear Regression and several optimization algorithms (Gradient Descent, Stochastic Gradient Descent, Mini-batch Gradient Descent, and Newton’s Method). The goal is to determine the optimal allocation of ad budgets to maximize sales.

📌 Objective
To analyze and optimize the relationship between advertising expenditures and product sales using machine learning models and optimization techniques, specifically:

Identify the most influential advertising channel

Minimize prediction error using advanced optimizers

Compare multiple optimization algorithms for effectiveness

📊 Dataset
Source: Kaggle Advertising Dataset

200 samples

Features:

TV, Radio, Newspaper – advertising costs

Sales – product sales (target)

🧠 Algorithms Used
1. Linear Regression
Models the relationship between input features (TV, radio, newspaper) and sales.

2. Gradient Descent
Basic optimization to minimize Mean Squared Error (MSE).

3. Stochastic Gradient Descent
Performs updates using a single sample at a time—faster convergence.

4. Mini-batch Gradient Descent
Uses small batches of data for efficient computation and improved stability.

5. Newton’s Method
Uses second-order derivatives (Hessian matrix) for fast convergence near minima.

⚙️ Training & Evaluation
Loss Function: Mean Squared Error (MSE)

Preprocessing:

Data normalization

Random weight initialization

Evaluation Metrics: MSE, weight coefficients, convergence behavior

