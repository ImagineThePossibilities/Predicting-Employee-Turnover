# Predicting Employee Turnover: A Data-Driven Approach
**Author:** M Sabih Armaghan

This work showcases how data driven approaches can empower HR departments to proactively identify at-risk employees and implement interventions designed to enhance retention.

**Overview:** In this project, I analyzed a comprehensive dataset obtained from Kaggle using statistical modelling and machine learning techniques. The goal was to uncover patterns and identify the factors driving employee turnover. I then used these insights to build a predictive model for employee turnover.

**Business Understanding:** Employee turnover is a challenge faced by businesses across various industries. The loss of valuable talent disrupts workflows, erodes knowledge, and incurs substantial costs associated with recruitment and training replacements. Understanding the factors that contribute to employee attrition is essential for developing effective retention strategies.

**Data Understanding:** The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv). It is from the HR Department of some unidentified company. There are 14,999 rows and 10 columns with variables such as employee satisfaction levels, last evaluation scores, number of projects, salary, department, etc.

**Models:** Logistic Regression (Statistical Modelling), Random Forest (Tree-based Machine Learning)

**Results:** The Random Forest model had a much stronger overall performance than the Logistic Regression model. This model had an accuracy of 98%, weighted: precision = 98%, recall = 98%, and f1-score = 98%.

This model also performed better at identifying employees who would leave: f1-score = 95% (whereas it was 73% for the logistic regression model), recall (proportion of positives that are correctly classified) = 92% (66% for the logistic regression).

**Conclusion:** From the insights extracted from the models, it is evident that management practices were responsible for employee turnover at this company. For further details and my recommendations, please refer to the included Jupyter Notebook.
