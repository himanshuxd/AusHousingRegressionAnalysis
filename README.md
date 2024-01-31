# Housing Regression Analysis

This repository presents an in-depth regression analysis of the Australian housing market. Surprise Housing, a US-based company, is strategically entering the Australian real estate landscape. Through meticulous data analytics, our objective is to predict property values accurately. This analysis empowers Surprise Housing to make informed investment decisions, ensuring the acquisition of properties below market value for subsequent profitable resale.

## Table of Contents
- [Housing Regression Analysis](#housing-regression-analysis)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Approach](#approach)
  - [Conclusions](#conclusions)
    - [Business Insights:](#business-insights)
  - [Technologies Used](#technologies-used)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  - [Contact](#contact)

## Project Overview

This repository focuses on a regression analysis using the `train.csv` dataset to predict property values in the Australian housing market for Surprise Housing, a US-based real estate company entering Australia. A guide to the data structure present is give in `data_description.txt`, by leveraging statistical modeling, the project aims to equip Surprise Housing with data-driven strategies to make informed decisions, ensuring successful market entry and profitable property transactions in Australia.

## Approach

We begin with comprehensive data preprocessing, including handling missing values and categorical encoding. Exploratory Data Analysis (EDA) delves into the dataset's nuances, providing insights that inform feature engineering decisions. The code then implements Lasso and Ridge Regression models for predictive analytics. To ensure robust evaluation, metrics like RMSE and R-squared are employed.

## Conclusions

- Variables such as `OverallQual`, `GrLivArea`, `TotalBsmtSF`, and `YearBuilt` significantly influence housing prices positively.
- The neighborhood (Neighborhood) plays a crucial role in determining housing prices, contributing to variations in overall housing prices.
- Property age (`PropAge`) negatively impacts housing prices, with newer properties commanding higher prices.
- Both Lasso and Ridge Regression models demonstrated good predictive performance, with R-squared values around 0.92, capturing a significant portion of the variance in housing prices.
- The analysis provides valuable insights for the real estate sector, guiding decision-making based on features like overall quality, living area, neighborhood, and property age to maximize property values.

### Business Insights:

   1. Emphasize property quality and size, as features like `OverallQual` and `GrLivArea` significantly impact housing prices.
   2. Choose neighborhoods strategically, considering the positive influence of certain areas on overall housing prices.
   3. Prioritize newer properties for investment, aligning with the market trend favoring modern constructions.

## Technologies Used

- Python: The primary programming language for data manipulation, analysis, and visualization.
- NumPy: Used for numerical operations and efficient array handling.
- Pandas: Employed for data manipulation, including data cleaning and preprocessing.
- Matplotlib and Seaborn: Visualization libraries for creating insightful plots and charts.
- Scikit-Learn: Utilized for machine learning tasks, including model building, feature selection, and data scaling.
- Statsmodels: Leveraged for advanced statistical modeling and analysis, particularly for linear regression and VIF calculations.
- Jupyter Notebook: The interactive environment for executing code, documenting the analysis, and presenting results.
- Min-Max Scaler: A feature scaling technique from Scikit-Learn for normalizing numerical data.
- LassoCV: Implemented for Lasso Regression with cross-validated alpha selection.
- Ridge: Applied for Ridge Regression.
- Imputer: Used to fill missing values in selected features, ensuring robustness in data preprocessing.

## License

This project is licensed under the MIT License.

[1] Himanshu S, "Housing Regression Analysis : Ridge and Lasso Regression Approach (2024)" [@himanshuxd](https://github.com/himanshuxd)


## Acknowledgments

- This project is done for US-based housing company named Surprise Housing trying to penetrate Australian market.
- This project was done as a part of a project for LJMU and IIIT Bangalore's Masters in Machine Learning & Artificial Intelligence program.

## Contact

- For inquiries or collaborations, feel free to reach out on GitHub: [@himanshuxd](https://github.com/himanshuxd)