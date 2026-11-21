# Car Price Prediction Using Machine Learning

## 1. Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning regression algorithms.

The model analyzes various car features, including manufacturing year, kilometers driven, fuel type, seller type, transmission, and ownership details to estimate the selling price.

## 2. Problem Statement

Estimating the resale value of used cars can be challenging because prices depend on multiple factors.

This project aims to develop a Machine Learning model that predicts used car prices based on historical car data.

## 3. Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Perform feature engineering.
- Train multiple regression models.
- Compare model performance.
- Select the best-performing model.
- Develop an interactive prediction interface using Gradio.

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Gradio
- Jupyter Notebook

## 5. Dataset

Dataset: CAR DETAILS FROM CAR DEKHO.csv

The dataset contains used car information and features such as:
- Car name
- Manufacturing year
- Selling price
- Kilometers driven
- Fuel type
- Seller type
- Transmission
- Owner type

## 6. Machine Learning Algorithms

The following regression algorithms are implemented:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## 7. Model Evaluation

Models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The best-performing model is selected based on the lowest MAE.

## 8. Model Deployment

Gradio is used to create an interactive interface where users can enter car details and receive an estimated selling price.

## 9. Project Structure

- CAR PRICE PREDICTION USING MACHINE LEARNING.ipynb
- CAR DETAILS FROM CAR DEKHO.csv
- requirements.txt
- README.md

## 10. How to Run the Project

1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook.
4. Run the notebook cells sequentially.
5. Use the Gradio interface to predict car prices.

## 11. Conclusion

This project demonstrates the application of Machine Learning regression techniques to predict used car selling prices. It provides practical experience in data analysis, preprocessing, feature engineering, model training, evaluation, and interactive deployment.

---

**Developed as a Machine Learning project.**
