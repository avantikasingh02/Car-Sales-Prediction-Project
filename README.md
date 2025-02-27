# 🚗 Car Sales Prediction using Artificial Neural Networks (ANNs)

## 📌 Project Overview

This project aims to predict the **Car Purchase Amount** a customer is willing to pay based on various attributes using an **Artificial Neural Network (ANN)**. The model helps car dealerships and financial analysts in understanding customer spending behavior and improving pricing strategies.

## 🔍 Problem Statement

As a **car salesman**, you want to develop a machine learning model that predicts the **total dollar amount** customers are willing to pay for a car. The dataset consists of multiple customer attributes, which serve as predictors for car purchase behavior.

### Input Features
- Customer Name
- Customer E-mail
- Country
- Gender
- Age
- Annual Salary
- Credit Card Debt
- Net Worth

### Target Variable

- Car Purchase Amount (Predicted by the ANN model)

## 📂 Dataset

The dataset used is **Car_Purchasing_Data.csv**, containing demographic and financial details of customers. Features such as **annual salary, credit card debt, and net worth** are leveraged to train the model.

## 📊 Data Preprocessing & Exploration

- **Removed non-relevant features** such as customer name, email, and country.
- **Exploratory Data Analysis (EDA)** performed using **Seaborn** and **Matplotlib** to visualize patterns.
- **Feature Scaling** applied to normalize data for ANN training.

## 🛠️ Tech Stack & Libraries Used

- **Python** (Core Programming Language)
- **Pandas**, **NumPy** (Data Processing)
- **Matplotlib**, **Seaborn** (Data Visualization)
- **Scikit-Learn** (Data Preprocessing)
- **TensorFlow**, **Keras** (Building the ANN Model)

## 🏗️ Model Architecture

The ANN model is designed with the following structure:
- **Input Layer:** Takes numerical input features (Age, Salary, Debt, etc.).
- **Hidden Layers:** Fully connected dense layers with activation functions.
- **Output Layer:** Single neuron for predicting Car Purchase Amount.

## 🚀 Results & Performance

- Achieved **high accuracy** in predicting car purchase amounts.
- **Loss function** optimized using **Mean Squared Error (MSE)**.
- **Performance metrics** evaluated to ensure model reliability.

## 📌 How to Run the Project

1. Clone the repository:
   
   git clone https://github.com/yourusername/car-sales-prediction.git
   cd car-sales-prediction

2. Install dependencies:

   pip install -r requirements.txt

3. Run the Jupyter Notebook or Python script.

## 📜 Conclusion

This project showcases the power of Artificial Neural Networks in predicting customer spending behavior based on financial attributes. The model can be further fine-tuned to improve accuracy and deployed as a web application for real-world usage.
