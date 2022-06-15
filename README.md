# Cardiovascular-Risk-Prediction
## Problem Statement
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).
## Data Description
The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.Variables Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.Attribute Information as followed
### Demographic
- Sex : male or female("M" or "F")
- Age: Age of the patient (Continuous)
### Behavioral
- is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
- Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(Continuous)
- BP Meds: whether or not the patient was on blood pressure medication (Nominal)
- Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
- Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
- Diabetes: whether or not the patient had diabetes (Nominal)
- Tot Chol: total cholesterol level (Continuous)
- Sys BP: systolic blood pressure (Continuous)
- BMI: Body Mass Index (Continuous)
- Heart Rate: heart rate (Continuous)
- Glucose: glucose level (Continuous)
### Predict variable (desired target)
- 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)
## Conclusion
- Machine Learning algorithm K-Nearest Neighbour, Gradient boosting and XG Boosting performed the best with a recall of 1.0 on the train data set
- KNN and Gradient boosting performed the best on test data with a recall score of 0.89 and 0.90 respectively
- Logistic Regression is the least accurate as compared to other models performed.
- Model Explanibililty was performed on extrema gradient boosting using eli5 and it’s observed that sex(gender) has the most significant impact on the target variable whether the patient will have the risk of CHD or not.
- Model can be improved with more computational resources and with more data.
