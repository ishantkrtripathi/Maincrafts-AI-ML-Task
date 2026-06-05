# California Housing Price Prediction (ML - Task 1)

This repository contains my project submission for Task 1 of my AI & Machine Learning Internship at Maincrafts Technology. The goal of this task was to build a baseline Linear Regression model to predict median housing prices across different districts in California using historical census data.

## Programs & Steps Included

* **Data Loading & Cleaning:** Programmatic scan to ensure the dataset is clean with zero missing or null values.
* **Exploratory Data Analysis (EDA):** Analyzing feature distributions and plotting a correlation matrix.
* **Train-Test Split:** Splitting the dataset into an 80% training set and a 20% testing set for fair evaluation.
* **Model Training:** Implementing an Ordinary Least Squares (OLS) Linear Regression model using Scikit-Learn.
* **Performance Evaluation:** Calculating metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²) Score.
* **Data Visualization:** Plotting an "Actual vs. Predicted" scatter plot to visualize model performance.

## Key Insights Found

* **Median Income:** It has the strongest positive relationship (~0.69 correlation) with housing prices. Wealthier areas naturally have higher property values.
* **The Data Cap:** The target housing prices are capped right at $500k. This artificial limit creates a boundary that a simple straight line struggles to fit perfectly.

## Performance Metrics

* **MAE:** ~0.533 (On average, predictions miss the actual values by about $53,300)
* **RMSE:** ~0.746 (Shows larger errors near the extreme price limits due to the $500k cap)
* **R-squared Score:** ~0.576 (Our baseline model successfully explains roughly 57.6% of the variance in prices)

## Technologies Used

* Python 3
* Pandas & NumPy (Data Manipulation)
* Scikit-Learn (Machine Learning)
* Matplotlib & Seaborn (Data Visualization)
* Jupyter Notebook

## Learning Outcome

This task helped me improve my understanding of:
* Complete Machine Learning workflow (EDA to Model Evaluation)
* Handling real-world datasets and analyzing feature correlations
* Evaluating regression model errors using mathematical metrics (MAE, RMSE, R²)
* Understanding the limitations of linear models and the need for advanced ensemble algorithms

## Author

Ishant Kumar  
B.Tech AI & ML Student
