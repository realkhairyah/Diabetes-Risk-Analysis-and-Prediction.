Diabetes Risk Prediction Model

This project focuses on analyzing quantitative data related to diabetes risk factors and building a predictive model for assessing diabetes risk. The dataset contains 100,000 records, including a variety of features that are crucial in predicting the likelihood of diabetes, such as BMI, HbA1c, glucose fasting levels, and cholesterol levels.

Project Overview

The main goal of this project is to analyze demographic, lifestyle, and medical features to build a predictive model for diabetes risk. By examining these factors, we can estimate the likelihood of an individual developing diabetes.

Key Insights:
 • Risk Factors Analysis: The dataset highlights several key quantitative factors that significantly influence the risk of diabetes, including:
 • HbA1c levels: The most significant factor in determining risk.
 • Glucose fasting levels: A critical marker for pre-diabetes and diabetes.
 • Age: Older individuals tend to have a higher risk of diabetes.
 • BMI: Higher BMI values are strongly correlated with increased risk.
 • Cholesterol levels: Both total and LDL cholesterol levels contribute to the risk.
 • Early Risk vs Clinical Risk: The project compares early indicators (like HbA1c) with clinical risk assessments, demonstrating that while early-risk features provide a rough estimate, clinical tests offer more precise predictions with a higher AUC (Area Under the Curve).
 • Top Clinical Features: The most important features influencing diabetes risk based on the dataset are HbA1c, glucose fasting levels, and age. These features have the highest coefficients in the model.

Model Performance:
 • Model Type: The model uses logistic regression and decision tree algorithms.
 • Performance Metric: The model achieved an AUC (Area Under the Curve) score of 93%, indicating high accuracy in predicting diabetes risk.

Dashboard:

A dynamic dashboard was designed to present the key insights and model outcomes. The dashboard visualizes the distribution of risk for both diagnosed and non-diagnosed individuals and showcases the relative importance of various clinical features in predicting diabetes risk.

Data Description

The dataset consists of 100,000 records with the following key quantitative features:
 1. HbA1c: A measure of the average blood sugar levels over the past 3 months.
 2. Glucose Fasting: Fasting blood glucose levels, measured after a period of no food intake.
 3. BMI: Body Mass Index, a common measure of body fat based on height and weight.
 4. Age: The age of the individual, with older ages being a significant risk factor for diabetes.
 5. Cholesterol Levels: Both LDL cholesterol and total cholesterol contribute to cardiovascular risks, which are correlated with diabetes.
 6. Smoking Status: Whether the individual smokes, which can be a contributing factor to diabetes risk.
 7. Additional features: Including glucose postprandial, HDL cholesterol, triglycerides, and waist-to-hip ratio.

Data Statistics:
 • Total Records: 100,000
 • Percentage Diagnosed: 60%
 • Feature Importance: HbA1c has the highest weight in predicting diabetes risk, followed by glucose fasting levels, age, and BMI.

Insights from the Analysis
 • Risk Distribution: The analysis shows that non-diabetic individuals tend to have lower average HbA1c and glucose fasting levels compared to those diagnosed with diabetes. This difference is clearly reflected in the distribution plots.
 • Clinical Testing vs Early Screening: The clinical model, which incorporates lab-based tests such as HbA1c and glucose fasting levels, achieved a much higher AUC of 93%, compared to the early-risk model with an AUC of 66%. This highlights the importance of clinical diagnostics in confirming diabetes risk.
 • Actionable Recommendations:
 • Use early-risk indicators (like HbA1c and glucose fasting) for initial population screening.
 • Refer individuals at high-risk (20-30%) based on early indicators to clinical testing for more accurate diagnosis.
 • Confirm diabetes diagnosis with clinical tests (AUC = 0.93).

Conclusion
This project demonstrates the value of using quantitative medical and lifestyle data to predict diabetes risk. By focusing on key clinical features like HbA1c, glucose fasting, and BMI, we can effectively assess the risk of diabetes and recommend early interventions.
