# 🚗 Vehicle Price Prediction Project 💰

Welcome to the **Vehicle Price Prediction** project! This repository contains a machine learning pipeline to predict vehicle prices based on features like make, model, year, mileage, and more. Built with Python and popular data science libraries, this project demonstrates data preprocessing, exploratory data analysis (EDA), and predictive modeling using a Random Forest Regressor.

---

## 📖 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🚀 Project Overview
This project aims to predict vehicle prices using a dataset of vehicle attributes. The pipeline includes:
- **Data Cleaning**: Handling missing values and duplicates.
- **Exploratory Data Analysis (EDA)**: Visualizing price distributions and relationships with features like mileage, fuel type, and vehicle make.
- **Machine Learning**: Training a Random Forest Regressor to predict prices and evaluating performance with Mean Squared Error (MSE) and R² Score.

The project is implemented in a Jupyter Notebook (`Vehicle_Price_Prediction.ipynb`) and is perfect for learning about data preprocessing, visualization, and machine learning.

---

## ✨ Features
- **Data Preprocessing**:
  - Handles missing values using median for numerical columns and mode for categorical columns.
  - Encodes categorical variables using LabelEncoder.
  - Scales numerical features with StandardScaler.
- **Exploratory Data Analysis (EDA)**:
  - Histogram of vehicle prices with KDE.
  - Boxplots for price distribution by body type and top vehicle makes.
  - Scatterplot of price vs. mileage colored by fuel type.
- **Machine Learning**:
  - Random Forest Regressor with 100 estimators.
  - Feature importance analysis to identify key predictors.
- **Evaluation Metrics**:
  - **Mean Squared Error (MSE)**: 123,896,651.92
  - **R² Score**: 0.745

---

## 📊 Dataset
The dataset (`Vehicle Price.csv`) contains vehicle information with the following columns:
- **Columns**: `name`, `description`, `make`, `model`, `year`, `price`, `engine`, `cylinders`, `fuel`, `mileage`, `transmission`, `trim`, `body`, `doors`, `exterior_color`, `interior_color`, `drivetrain`.
- **Size**: 1,002 rows, 17 columns.
- **Source**: Not included in the repository due to size constraints. You can source a similar dataset from platforms like Kaggle or update the file path in the notebook to your local dataset (`c:\Users\user\Desktop\Kaggle Datasets\Vehicle Price.csv`).

---

## 🛠️ Installation
To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sahil007707/vehicle-price-prediction.git
   cd vehicle-price-prediction
