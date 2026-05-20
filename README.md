# NYC Airbnb Price Prediction using Machine Learning

## Project Overview

This project analyzes Airbnb listing data from New York City and builds a machine learning model to predict nightly rental prices.

The main goal of this project is to understand what factors affect Airbnb prices, such as room type, location, availability, number of reviews, and other listing features. The project follows a complete beginner-friendly data science workflow, including data cleaning, exploratory data analysis, visualization, statistical testing, and machine learning model building.

## Dataset

The dataset used in this project is the NYC Airbnb 2019 dataset.

It contains information about Airbnb listings in New York City, including:

- Listing name
- Host information
- Neighbourhood group
- Room type
- Price
- Minimum nights
- Number of reviews
- Availability
- Geographic location

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy
- Scikit-learn

## Project Steps

### 1. Data Cleaning

The dataset was cleaned by:

- Removing duplicate rows
- Removing listings with invalid prices
- Handling missing values
- Removing unrealistic minimum night values
- Removing extreme price outliers

### 2. Exploratory Data Analysis

Different visualizations were created to understand the dataset better, including:

- Price distribution
- Price comparison by room type
- Average price by neighbourhood group
- Availability analysis
- Correlation heatmap

### 3. Statistical Analysis

A statistical test was used to compare Airbnb prices between different room types.

The analysis showed that entire homes/apartments are generally more expensive than private rooms.

### 4. Machine Learning Model

A Ridge Regression model was built to predict Airbnb nightly prices.

The model was evaluated using:

- RMSE
- MAE

## Results

The model was able to predict Airbnb prices with reasonable accuracy for a beginner-level machine learning project.

The project showed that room type, location, availability, and review-related features can affect Airbnb pricing.

## What I Learned

Through this project, I learned how to:

- Clean real-world data
- Analyze data using Python
- Create useful visualizations
- Apply basic statistical testing
- Build a machine learning regression model
- Evaluate model performance
- Present data science results in a report and notebook

## How to Run This Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/airbnb-nyc-price-prediction.git
