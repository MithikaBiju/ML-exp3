# ML-exp3
# 🏡 Multiple Linear Regression for House Price Prediction

A clean implementation of **Multiple Linear Regression** using **Scikit-learn** to predict house prices based on multiple property features. This project demonstrates how multiple independent variables influence the target variable and evaluates the model's prediction accuracy.

## 📌 Overview

This project builds a **Multiple Linear Regression** model to estimate house prices using four important features:

- Area
- Number of Bedrooms
- Age of the House
- Distance from the City Center

The model is trained on a sample housing dataset and is used to predict the price of a new house while evaluating its overall performance.

## ✨ Features

- Multiple Linear Regression implementation using Scikit-learn
- Dataset creation using Pandas
- Model training and prediction
- Displays regression coefficients and intercept
- Generates the complete regression equation
- Predicts the price of a new house
- Performance evaluation using:
  - Mean Squared Error (MSE)
  - R² Score
- Actual vs Predicted Price visualization

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

The project uses a sample housing dataset containing the following attributes:

| Feature | Description |
|---------|-------------|
| Area | Size of the house (sq.ft.) |
| Bedrooms | Number of bedrooms |
| Age | Age of the house (years) |
| Distance | Distance from the city center |
| Price | House price (Target Variable) |

## 📊 Workflow

1. Create the housing dataset.
2. Load the data into a Pandas DataFrame.
3. Separate input features and target variable.
4. Train a Multiple Linear Regression model.
5. Predict house prices.
6. Display model coefficients and intercept.
7. Generate the regression equation.
8. Evaluate model performance using MSE and R² Score.
9. Predict the price of a new house.
10. Visualize Actual vs Predicted prices.

## 📈 Evaluation Metrics

The model performance is evaluated using:

- **Mean Squared Error (MSE)**
- **R² Score (Coefficient of Determination)**

These metrics measure prediction accuracy and how well the model fits the data.

## 📷 Output Visualizations

The notebook includes:

- Actual vs Predicted Price Scatter Plot
- Ideal Prediction Reference Line

## 📚 Learning Outcomes

This project helps in understanding:

- Multiple Linear Regression
- Feature selection
- Model training using Scikit-learn
- Regression coefficients and intercept
- Regression equation interpretation
- Model evaluation using MSE and R² Score
- Predicting values for unseen data
- Data visualization with Matplotlib

## 🚀 Future Improvements

- Train/Test data splitting
- Feature Scaling
- Larger real-world housing datasets
- Cross-validation
- Feature importance analysis
- Hyperparameter tuning
- Model comparison with Decision Tree and Random Forest Regression

## 📄 License

This project is developed for **educational and learning purposes**. Feel free to use and modify it for academic or personal projects.

