Airbnb Booking Prediction - README

Project Overview

This project involves building a predictive model to forecast the number of days an Airbnb listing will be booked in the next 30 days. The data is derived from real listings in Los Angeles, with training labels provided for a subset of the listings. The goal is to maximize prediction accuracy, evaluated using the R² metric.

Project Structure

Feature Engineering and Preprocessing: Data cleaning, transformation, and feature engineering.

Model Training and Evaluation: Experiments with Random Forest, Lasso Regression, and hyperparameter tuning.

Prediction Generation: Generate predictions for the test dataset for competition submission.

Data Analysis Techniques

Feature Engineering: One-hot encoding for categorical variables, imputation of missing values, and removal of irrelevant features.

Model Selection and Evaluation: Random Forest and Lasso Regression models with cross-validation.

Feature Importance Analysis: Identify the most significant predictors for bookings.

Key Insights

Reviews per Month: The strongest predictor, highlighting the role of customer engagement.

Availability Metrics: Availability over the next 60 and 90 days indicates short-term demand.

Geographical Location: Latitude and longitude significantly influence booking patterns.

Tools and Libraries

Python (pandas, numpy, scikit-learn, matplotlib)

Jupyter Notebooks

Parquet for data handling

Getting Started

Clone the repository.

Install the required libraries using pip install -r requirements.txt.

Run the Jupyter notebook 'ML_Airbnb.ipynb' to replicate the analysis and generate predictions. The predictions for my analysis may be found by accessing the 'ML_Airbnb_Predictions.xlsx' document.

Future Improvements

Experiment with additional model architectures like Gradient Boosting.

Implement feature selection techniques to reduce noise.

Apply advanced hyperparameter tuning strategies.
