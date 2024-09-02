# Alcohol-Attributed Mortality Analysis in the United States (2015-2019)

## Project Overview

This project conducts a comprehensive analysis of alcohol-attributed mortality in the United States from 2015 to 2019. Using data from the CDC's Alcohol Related Disease Impact (ARDI) application, we explore patterns, trends, and factors influencing alcohol-related deaths across different demographics and regions.

## Key Objectives

1. Identify and characterize patterns and trends in alcohol-related mortality.
2. Explore demographic disparities and geographic variations in alcohol-attributed deaths.
3. Investigate types and causes of alcohol-related fatalities, including associated risk factors and comorbidities.

## Methodology

Our analysis employs various data mining and machine learning techniques:

1. Data Preparation: Cleaning, handling missing values, and feature engineering.
2. Exploratory Data Analysis: Univariate, bivariate, and multivariate analyses.
3. Predictive Modeling: Using SVR, Gradient Boosting, Random Forest, and XGBoost.
4. Statistical Analysis: Linear regression to explore relationships between variables.

## Key Findings

- XGBoost consistently outperformed other models in predicting alcohol-related mortality rates.
- Significant geographic variations in mortality rates were observed across states.
- Age and specific causes of death were identified as significant predictors of alcohol-related fatalities.
- Demographic disparities were highlighted, suggesting higher risk among certain age groups, particularly older individuals.

## Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/DeborahAdedigba/COM725_assessment.ipynb
   ```
2. Run the Jupyter notebooks in the `notebooks/` directory to reproduce the analysis.

## Dependencies

- Python 3.8+
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn
- tableau (for visualization)

## Contributors

- Deborah Adetayo ADEDIGBA

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE License.

## Acknowledgments

- Centers for Disease Control and Prevention (CDC) for providing the ARDI dataset.
- Solent University, Faculty of Business, Law, and Digital Technologies

For more detailed information about the analysis and findings, please refer to the full technical report.
