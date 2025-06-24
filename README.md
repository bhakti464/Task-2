# 🌦️ WeatherAUS EDA – Exploratory Data Analysis & Visualization
## 📌 Project Objective
This project focuses on performing exploratory data analysis (EDA) on the weatherAUS.csv dataset. The goal is to understand key patterns, clean the dataset, and visualize relationships between weather features to support future machine learning tasks.

## 🧰 Tools & Libraries Used
Python
Pandas – For data loading and manipulation
Matplotlib & Seaborn – For data visualization
Plotly Express – For interactive plotting

# 🔧 Steps Performed
## 1. Load the Dataset
The dataset was loaded and basic information was viewed, including data types and the presence of missing values.

## 2. Initial Data Exploration
Basic EDA operations like viewing the first few records, checking statistical summaries, and counting missing values were performed to get an overview of the data.

## 3. Data Cleaning
Columns with more than 30% missing values were removed. After that, all rows with any remaining null values were dropped to ensure a clean dataset.

## 4. Rainfall Distribution
A histogram was plotted to visualize the distribution of rainfall values. This helped in identifying skewness and concentration in lower ranges.

## 5. Correlation Matrix
A heatmap was generated to show correlations between numerical features, highlighting which variables might be important for prediction tasks.

## 6. Outlier Detection via Boxplot
A boxplot was created for the MaxTemp feature to visually detect outliers and understand the spread of data.

## 7. Pairplot by Target Variable
Selected features were used to generate a pairplot, colored by the RainTomorrow target variable. This allowed us to examine how features relate to each other and how they vary with the target.

## 8. Interactive Scatter Plot
An interactive scatter plot was created using Plotly to explore the relationship between afternoon humidity and rainfall, with color indicating whether it rained the next day.

## ✅ Outcome
Cleaned dataset with no missing values
Visual insights gained on data distributions and correlations
Categorical target variable (RainTomorrow) mapped and visualized
Clear foundation established for building predictive models
