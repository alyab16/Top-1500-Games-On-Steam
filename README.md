# Top-1500-Games-On-Steam
<img src="https://upload.wikimedia.org/wikipedia/commons/8/83/Steam_icon_logo.svg" width="50" height="50">

A predictive analysis project exploring factors influencing game prices on Steam using regression models.

## Table of Contents
- [Dataset](#dataset)
- [Analysis Overview](#analysis-overview)
- [Installation](#installation)

## Dataset
**Source:** [Kaggle - Top 1500 Games on Steam by Revenue](https://www.kaggle.com/datasets/alicemtopcu/top-1500-games-on-steam-by-revenue-09-09-2024)  
**Features Included:**
- Price
- Copies Sold
- Revenue
- Average Playtime
- Review Score
- Release Date
- Publisher/Developer Information

## Analysis Overview
1. **Data Preparation**
   - Handled missing values
   - Feature engineering:
     - Converted release dates to "days since release"
     - One-hot encoded categorical variables

2. **Exploratory Analysis**
   - Price distribution visualization
   - Correlation matrix analysis
   - Pairplot relationships

3. **Model Development**
   - Tested 8 regression algorithms:
     - Linear/Ridge/Lasso/ElasticNet Regression
     - Decision Tree/Random Forest
     - Gradient Boosting
     - Support Vector Regression
   - Hyperparameter tuning with GridSearchCV

## Installation
```bash
# Required libraries
pip install pandas numpy scikit-learn matplotlib seaborn
