## House Price Visualization Analysis
This project aims to predict house prices in King County, USA, using linear regression. The dataset includes various features of houses, such as square footage, bedrooms, bathrooms, and price, among others.
## Objectives
- Perform EDA to identify trends and correlations between features (e.g., price vs. square footage).
- Visualize relationships using scatterplots, histograms, and heatmaps.
## Data Preprocessing:

- Handle missing values, encode categorical variables, and scale numerical features.
- Split data into training and testing sets.
## Model Building:

- Train a linear regression model using scikit-learn.
- Evaluate model performance using R-squared and Mean Squared Error (MSE).
## OLS Regression Analysis:

- Perform OLS regression to gain statistical insights into feature significance.
## Model Evaluation:

- Compare sklearn's linear regression and statsmodels' OLS regression.
- Analyze residuals to improve model accuracy.
  Key Findings from EDA
## Scatterplot Analysis:
- Strong positive correlation between sqft_living and price, with some non-linear patterns and outliers.

## Heatmap:
- Features like sqft_living, grade, and bathrooms have high positive correlations with price, while others show weak or negative correlations.

## Prerequisites
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels for OLS model
## Install necessary libraries:
- pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
  How to Run
## Clone the Repository:

-git clone https://github.com/akshatamarewad/Home-Sales-Project/edit/main/README.md
-cd Home-Sales-Project
## Download Dataset:
-Download the kc_house_data.csv from Kaggle and place it in the project directory.

## Run the Notebook:
- Open and run the House_Sales_project.ipynb in Jupyter:

- jupyter notebook House_Sales_project.ipynb

## Project Structure
- kc_house_data.csv: Dataset
- house_price_prediction.ipynb: Jupyter Notebook with the analysis
- README.md: Project description
## Conclusion
- This project provides a linear regression model for predicting house prices and analyzes the influence of various features on price through EDA and OLS regression.




