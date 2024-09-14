# Startups Profit Prediction

This project aims to predict the profit of startups based on their spending on R&D, Marketing, and Administration using Multiple Linear Regression. The project also includes data visualization in Tableau to compare the actual vs predicted profits.

## Project Overview

Startups often face challenges in predicting their potential profits based on investment in various areas. This project builds a predictive model to help startups make informed decisions about spending.

### Key Features:
- Predict the profit of startups based on key spending areas.
- Use of **Multiple Linear Regression** for prediction.
- Visualized predictions using **Tableau**.
  
---

## Table of Contents
1. [Dataset]
2. [Exploratory Data Analysis (EDA)]
3. [Modeling]
4. [Tableau Visualization]
5. [Results]
7. [Contributing]

## Dataset

The dataset used for this project contains information about startups' spending on R&D, Marketing, and Administration, along with the corresponding profit. You can find the dataset in the /data folder or download it from Kaggle.

## Dataset Overview:
+ R&D Spend: Money spent on research and development.
+ Administration: Administration expenses.
+ Marketing Spend: Marketing budget.
+ State: Location of the startup.
+ Profit: The dependent variable (target) we aim to predict.

## Exploratory Data Analysis (EDA)
Basic exploratory data analysis (EDA) was performed to understand the relationships between different features. Some key insights:

+ R&D Spend has the strongest correlation with profit.
+ Marketing Spend also contributes but to a lesser extent.
  ![bar1](https://github.com/user-attachments/assets/70ba104e-eff1-49f2-9a59-b162b60d38ed)
+ The State variable does not significantly impact the profit.
## Modeling

We used Multiple Linear Regression to build a model that predicts the startup's profit based on:

+ R&D Spend
+ Administration
+ Marketing Spend
+ State (encoded using One-Hot Encoding)
## Model Performance:
**R-squared: 0.93** (indicating a strong fit).
**RMSE: 9137.99** (root mean squared error showing the average deviation of predictions from actual values).

## Tableau Visualization
The predicted profits were visualized using Tableau. The scatter plot compares the Actual Profit and Predicted Profit, showing how closely the model's predictions match the real data.

![actualvspred](https://github.com/user-attachments/assets/bdfb4b37-6c34-4846-a3b3-e8937d02dba8)



## Results
- The R&D Spend had the most significant impact on a startup's profit.
- Marketing Spend also contributed positively but was not as impactful.
+ Administration expenses had little to no effect on profit.
## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request. We welcome suggestions and improvements!
