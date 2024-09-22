# Project Overview: Insurance Data Analysis

This project focuses on analyzing historical car insurance claim data for AlphaCare Insurance Solutions (ACIS) to optimize marketing strategies and identify low-risk clients. The analysis is structured across three key notebooks: **Exploratory Data Analysis (EDA)**, **A/B Hypothesis Testing**, and **Statistical Modeling**. Each notebook contributes to extracting valuable insights for strategic decision-making, with data-driven visualizations, rigorous hypothesis testing, and predictive modeling techniques.

## Exploratory Data Analysis (EDA)
The **EDA notebook** begins with understanding the dataset through descriptive statistics and univariate/bivariate analysis, examining key variables like `TotalPremium`, `TotalClaim`, and geographic features. The analysis revealed significant regional differences in premiums, claims, and insurance types, which were further visualized using scatter plots, heatmaps, and time series graphs. Outlier detection and correlation analysis provided deeper insights into the relationships between premiums, claims, and regions, laying the groundwork for further analysis.

## A/B Hypothesis Testing
In the **A/B Hypothesis Testing notebook**, various statistical tests were performed to evaluate the significance of differences across segmented groups based on gender, province, and zip code. The T-Test and Chi-Squared tests identified meaningful variations in risk scores and profit margins, particularly across provinces, while also highlighting notable differences in risk scores between genders. These findings help ACIS understand how geographic and demographic factors influence insurance claims and premiums.

## Statistical Modeling
The **Statistical Modeling notebook** explored predictive modeling techniques to forecast premiums and identify low-risk clients. Three models—Linear Regression, Random Forest, and XGBoost—were built and compared. Random Forest and XGBoost provided the most accurate predictions, although signs of overfitting were observed. Using SHAP and LIME, we interpreted feature importance, revealing that vehicle characteristics and transaction timing were key predictors of premium rates. This information offers actionable insights for tailoring ACIS’s marketing strategies.

## Key Insights and Business Implications
The project highlights significant relationships between regional and demographic factors and insurance premiums and claims. The advanced models, despite high predictive accuracy, raise potential concerns about overfitting, indicating the need for further refinement. Insights from the models suggest that ACIS should focus on vehicle types, client demographics, and regional factors when developing targeted marketing campaigns aimed at low-risk customers.

## Next Steps
Ongoing improvements to the models, such as refining feature selection and addressing overfitting, are essential. The analysis will serve as a foundation for optimizing marketing efforts, offering premium reductions to targeted low-risk clients while continuously monitoring model performance as new data becomes available.