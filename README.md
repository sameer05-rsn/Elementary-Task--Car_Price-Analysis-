# Elementary-Task--Car_Price-Analysis-
Car Price Analysis using Python, showcasing data cleaning, exploratory data analysis, and feature insights through statistical methods and visualizations.
Car Price Analysis
Objective

The objective of this project is to analyze the CarPrice_Assignment dataset to identify the key factors that influence car prices.
The analysis involves data cleaning, preprocessing, feature engineering, and visualization to uncover meaningful insights for business decision-making and predictive modeling.

Overview

This project provides an end-to-end exploratory data analysis (EDA) of car price data.
It covers:

Cleaning and preprocessing raw data

Handling categorical variables

Feature engineering (e.g., car stability metric)

Visualization and correlation analysis

Identifying the most important features that affect car prices

Data Source

The dataset used in this project is the CarPrice_Assignment dataset.


Download Dataset Here
  https://github.com/sameer05-rsn/Elementary-Task--Car_Price-Analysis-/blob/main/CarPrice_Assignment.csv

Key Features:

Numerical: wheelbase, carlength, curbweight, enginesize, horsepower, citympg, highwaympg, price (target).

Categorical: CarName, fueltype, aspiration, carbody, drivewheel, enginetype, fuelsystem.

 Data Analysis Process
 Data Import & Initial Inspection

Import libraries and load the dataset.

Inspect dataset shape, columns, and preview rows.

Questions Addressed:

How many rows and columns does the dataset have?

Are there missing values, and what percentage of data is missing?

Should rows with high missing values (>60% columns) be dropped?

2️⃣ Data Cleaning & Preprocessing

Drop unwanted/irrelevant columns.

Extract carCompany from CarName.

Fix spelling errors in car company names.

Handle categorical variables and convert them to dummy variables.

Rename dummy columns for clarity.

Questions Addressed:

Which columns are unnecessary and can be removed?

How do we standardize company names?

How do categorical variables (e.g., fuel type, car body) get encoded?

3️⃣ Feature Engineering

Create car_stability = wheelbase / carlength.

Drop redundant columns after feature creation.

Questions Addressed:

Can new meaningful metrics be derived from existing features?

Which features are redundant after encoding or transformation?

4️⃣ Exploratory Data Analysis (EDA)

How many rows and columns are in the dataset?

Are there any missing values, and in which columns?

Should rows with excessive missing values (>60% of columns) be removed?

Which columns are irrelevant and can be dropped?

How can we standardize car company names for consistency?

How are categorical variables like fueltype, carbody, and drivewheel encoded?

Can new meaningful metrics (like car stability) be derived from existing features?

Are there any redundant features after feature engineering?

Which numerical features have strong correlation with price?

How are key features like horsepower, enginesize, and curbweight distributed?

Do higher horsepower or larger engine cars cost more?

How do different car companies influence pricing?



🛠 Tools & Libraries

Python 3.11

Libraries:

Pandas – Data manipulation

NumPy – Numerical computing

Matplotlib – Visualization

Seaborn – Advanced visualization

Jupyter Notebook – Interactive environment



