# World Happiness Analysis
Exploratory data analysis and predictive modeling on the 2019 UN World Happiness Report.

## Overview
This project analyzes happiness scores across 156 countries using the 2019 World Happiness Report. It combines exploratory data analysis with two predictive models — Linear Regression and Random Forest — to identify the key drivers of national happiness and predict happiness scores.

## Dataset
- **Source:** [UN World Happiness Report 2019](https://www.kaggle.com/datasets/unsdsn/world-happiness) via Kaggle
- **Size:** 156 countries, 9 features
- **Key variables:** Happiness Score, GDP per Capita, Social Support, Healthy Life Expectancy, Freedom to Make Life Choices, Generosity, Perceptions of Corruption

## Methods
- Exploratory data analysis with correlation heatmaps, distribution plots, and scatter plots
- Linear Regression for baseline predictive modeling
- Random Forest Regression for improved prediction accuracy
- Feature importance analysis to identify top predictors

## Key Findings
- **Random Forest outperformed Linear Regression:** R² = 0.725 vs. R² = 0.687
- **Top predictors of happiness:** GDP per capita, social support, and healthy life expectancy
- Strong positive correlations between economic indicators and happiness scores across regions

## Tools & Libraries
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/World_Happiness.git`
2. Install dependencies: `pip install pandas matplotlib seaborn scikit-learn`
3. Open and run the Jupyter notebook, or [view on Kaggle](https://www.kaggle.com/code/bronsonb/happiness-score-2019-eda-prediction)
