# Predict Attrition and Monthly Salary

Case Study # 2 for SMU DS6307 - Doing Data Science class, Fall Semester 2019.

We were provided a data file (CaseStudy2-data.csv) containing XX features describing XXX employees at an anonymous company. Using these data, we were asked to build a classification model to predict Attrition (response = "Yes" or "No") and a regression model to predict Monthly Salary ($) of each employee. 

## Attrition Model:
See the Rmarkdown file "PredictAttrition.Rmd" for details. Main components:
1. EDA
2. Feature Selection with correlation plots and recursive feature elimination
3. Train multiple types of models (knn, naive bayes, adaboost)
4. Evaluate model performance
5. Run model on unlabeled data ("CaseStudy2CompSet No Attrition.csv") and provide predictions ("Attrition_Predictions.csv")

## Salary Model:
See the Rmarkdown file "PredictSalary.Rmd" for details. Main components:
1. Feature Selection with correlation plots, backward/forward/stepwise selection
2. Evaluate model performance and select a final model for making predictions
4. Run model on unlabeled data ("CaseStudy2CompSet No Salary.csv") and provide predictions ("Salary_Predictions.csv")

## Presentation:
1. Slide deck summarizing the data analysis and conclusions ("CaseStudy2.pptx")
2. YouTube presentation of slide deck (https://youtu.be/4P_7kmHEHbA)


