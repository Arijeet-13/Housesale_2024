# House Price Prediction - Data Analysis and Modeling

## Overview
This project involves analyzing and predicting house prices using the "kc_house dataset". The dataset includes details on houses sold in King County, USA, with various attributes such as price, number of bedrooms, square footage, location, and more.

## Project Structure
- **Data Loading & Exploration**
  - Load dataset using `pandas`
  - Display basic information and statistics using `.head()` and `.describe()`
  
- **Data Visualization**
  - Distribution of bedrooms
  - Geospatial distribution of houses
  - Relationships between price and various features (square footage, location, number of bedrooms, etc.)

- **Preprocessing**
  - Dropped unnecessary columns (`id`, `price` for training data)
  - Converted `date` column into a numerical format

- **Model Training & Evaluation**
  - Used **Linear Regression** from `sklearn`
  - Split dataset into training and testing sets (90%-10%)
  - Evaluated performance using MAE, MSE, and RMSE
  - Implemented **Random Forest Regressor** to compare performance

## Requirements
To run this project, install the following dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Running the Project
1. Load the dataset (`kc_house_data.csv`).
2. Run the analysis and visualization sections.
3. Train models and evaluate their performance.

## Results
- Linear Regression Model Score: *Computed on test set*
- Random Forest Model Score: *Computed on test set*
- Performance metrics: MAE, MSE, RMSE

## Future Improvements
- Feature engineering to improve prediction accuracy.
- Hyperparameter tuning for better model performance.
- Exploring additional regression models.

## Author
Developed for a data analysis and machine learning study.

