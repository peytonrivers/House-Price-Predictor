🏡 House Price Predictor
This project builds and evaluates a linear regression model to predict house prices based on various features from a housing dataset. It includes data cleaning, exploratory analysis, model training, and residual diagnostics to assess model performance.

📂 Project Overview
The goal of this project is to create a regression model that accurately predicts housing prices and evaluate its performance using statistical checks and visualizations.

Key steps:

Data Cleaning & Preprocessing: Handling missing values, encoding categorical features, and scaling numeric data.

Exploratory Data Analysis (EDA): Visualizing distributions and relationships between features and price.

Model Training: Building a Linear Regression model using scikit-learn.

Model Evaluation: Analyzing residuals using histograms and Q–Q plots to verify regression assumptions.

Performance Metrics: Calculating MAE, MSE, and R² to assess accuracy.

📊 Results
R² (Coefficient of Determination): ~0.83

Mean Absolute Error (MAE): ~39,000

Insights:

Most predictions are close to actual prices.

Some outliers exist (large misses), especially at extreme price ranges.

🖼 Visuals
Residual Histogram: Shows how far predictions were from actual values (most errors near zero).

Q–Q Plot: Confirms residuals are approximately normally distributed (model assumptions hold).



🛠 Technologies Used
Python 3

Pandas, NumPy for data handling

Matplotlib, Seaborn for visualization

scikit-learn for machine learning

SciPy for statistical analysis


