# 🏠 House Price Prediction — King County, USA

This project was completed as the Final Project in the **IBM Data Analyst Professional Certificate** program. The objective is to analyze residential housing data from King County, Washington to build a regression model that predicts home sale prices based on several property features.

---

## 📌 Project Scenario

You are a **Data Analyst** working at a **Real Estate Investment Trust** that plans to invest in residential real estate. Your job is to determine the **market value of homes** using housing attributes such as square footage, location, number of bedrooms, and more. The analysis will help guide future investment decisions.

---

## 📁 Dataset Information

- **Dataset**: House Sales in King County, USA  
- **Source**: [Kaggle - House Sales Prediction](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)  
- **Timeframe**: May 2014 – May 2015  
- **Description**: Includes house prices and features for residential properties in King County, including Seattle.

---

## 🔍 Project Objectives

- Import and clean the housing dataset
- Explore the data to find patterns and relationships
- Build regression models to predict house prices
- Evaluate model performance and make refinements

---

## 🧪 Project Workflow

### 🔹 Module 1: Importing Data
- Loaded the dataset using Pandas
- Inspected data structure, types, and basic stats

### 🔹 Module 2: Data Wrangling
- Dropped irrelevant or redundant features
- Handled missing values
- Created new features (e.g., house age)

### 🔹 Module 3: Exploratory Data Analysis (EDA)
- Used scatter plots, box plots, and heatmaps to explore correlations
- Identified key variables influencing price
- Detected outliers and distribution trends

### 🔹 Module 4: Model Development
- Built a Simple Linear Regression model using `sqft_living`
- Developed a Multiple Linear Regression model with several predictors
- Implemented models using `scikit-learn`

### 🔹 Module 5: Model Evaluation and Refinement
- Evaluated models using R² Score and Mean Squared Error (MSE)
- Compared predicted vs. actual values
- Selected best-fit model based on performance

---

## 💡 Key Skills Demonstrated

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis  
- Regression Modeling (Simple & Multiple)  
- Model Evaluation Techniques  
- Visualization with Matplotlib & Seaborn  

---

## 🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📂 Repository Structure

house-price-prediction-king-county/
│
├── House_Sales_in_King_Count_USA_final.ipynb # Main notebook
├── README.md # Project description
└── images/ # Charts
