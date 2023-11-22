# Linear-Regression-Assignment
BoomBikes, hit by pandemic revenue woes, consults to predict post-lockdown bike demand in the US. Analyzing meteorological and lifestyle data, they aim to identify key factors driving demand for shared bikes, crafting a strategic plan for profitability.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [View 01.pdf](01.pdf)
* [Acknowledgements](#acknowledgements)


## General Information
The project revolves around addressing the business challenges faced by BoomBikes, a bike-sharing provider in the US. With the onset of the COVID-19 pandemic, BoomBikes experienced a decline in revenue. The company is keen on developing a strategic business plan to thrive in the post-lockdown period and understand the factors influencing the demand for shared bikes.

<b> Business Problem:</b>
The primary business problem is to model and predict the demand for shared bikes. BoomBikes aims to identify the significant variables affecting bike demand, comprehend the dynamics of demand, and prepare a business strategy accordingly. The objective is to enhance revenue by meeting customer expectations and distinguishing themselves from other service providers.

<b>Dataset:</b>
The dataset used for analysis contains information on daily bike demands across the American market. The dataset includes various features such as weather conditions, seasons, months, weekdays, and more. The target variable, 'cnt,' represents the total number of bike rentals. The company has gathered this data to explore the factors influencing bike demand and to build a predictive model for future demand scenarios.

In the project, we will perform data cleaning, exploratory data analysis (EDA), feature engineering, and build a multiple linear regression model. The dataset will be split into training and testing sets, and the model's performance will be evaluated. Recommendations based on the analysis will be provided to assist BoomBikes in adapting their business strategy for optimal results.

## Technologies Used
- Pandas - version 1.0
- NumPy - version 1.0
- Matplotlib - version 2.0
- Seaborn - version 3.0
- Scikit-learn - version 0.24

## Conclusions <a name="conclusions"></a>
<b>Correlation Insights:</b>
The chart and heatmap analysis unveil robust positive correlations, with a correlation coefficient of 0.8 for clear weather, 0.7 for temperature, and a weak negative correlation of -0.3 with humidity. Clear weather and temperature emerge as influential factors positively impacting bike demand. These insights are pivotal for predictive modeling and informed resource allocation decisions.

<b>Binary Classification Model Performance:</b>
The confusion matrix provides a snapshot of the binary classification model's performance. With an accuracy of 0.85, precision of 0.80, recall of 0.91, and an F1 score of 0.85, the model exhibits strong overall performance. It accurately predicts positive outcomes 91% of the time and negative outcomes 85% of the time. Evaluating the model on a held-out test set adds credibility to its performance assessment.

<b>Classification Model Accuracy and Insights:</b>
The classification model excels with an impressive AUC of 0.95, indicative of a well-balanced sensitivity and specificity. Notably, it highlights a positive correlation between clear weather and increased bike demand, marked by heightened variability and more extreme cases. This underscores the model's ability to discern patterns and provide valuable insights.

<b>Regression Model Fit:</b>
The residuals plot from the regression model suggests a strong fit to the data. This indicates that the model effectively captures the underlying patterns and relationships in the dataset, bolstering confidence in its predictive capabilities.

## Acknowledgements
- This project was inspired by the need to understand the demand dynamics of bike-sharing systems.
- The insights gained from the "Machine Learning 1" module in the Executive PG Programme in Machine Learning & AI - August 2023, available at [Machine Learning 1 Course](https://learn.upgrad.com/course/4701), also played a crucial role in shaping the project.
- The foundational knowledge and methodologies learned from the course greatly contributed to the success of this project.

## Contact
Created by [@poronita] - feel free to contact me!
Note: if the PDF dosen't open please clone it your system, it must be visible locally. 
