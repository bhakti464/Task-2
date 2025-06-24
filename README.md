This repository contains Python code for exploratory data analysis (EDA) on the weatherAUS.csv dataset. The goal is to understand the dataset, clean it, and visualize relationships among weather features, especially with respect to predicting rainfall.

# Step 1: Load Dataset
We use pandas to load the dataset and check the structure using .info() to understand column types and missing values.

# Step 2: Basic Exploration
We view:

The first few rows (df.head()),

Descriptive statistics (df.describe()), and

The number of missing values in each column (df.isnull().sum()).

🔹 Step 3: Data Cleaning
We remove columns with more than 30% missing values.

Then, we drop rows that still contain missing data using dropna().

🔹 Step 4: Rainfall Distribution
We plot a histogram of the Rainfall column to understand its distribution and skewness.

🔹 Step 5: Correlation Matrix
We compute a correlation matrix for numerical columns and use a heatmap to visualize the strength and direction of relationships between features.

🔹 Step 6: Boxplot for Max Temperature
A boxplot is used to detect outliers and spread in the MaxTemp column.

🔹 Step 7: Pairplot (Grouped by Rain Tomorrow)
Using selected features, we create a pairplot (multi-variable scatterplot grid) colored by the RainTomorrow column (binary classification: Yes/No). It helps visualize class separation and feature relationships.

🔹 Step 8: Interactive Scatter Plot
An interactive Plotly scatter plot shows how Humidity3pm relates to Rainfall, colored by RainTomorrow. This helps in visual pattern detection.

This EDA lays the groundwork for building a predictive model to forecast rain tomorrow using historical weather data.
