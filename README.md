# Understanding Risk Factors for Type 2 Diabetes in Adult Women: A Logistic Regression Approach
by Team 4 (Justin Pan, Amy Liu, Nelson Zhu, Angela Chen) 

## Summary
Diabetes is a leading cause of death and disability globally, with an estimated 10.5% of the adult population living with the disease. Our study aims to develop a model that investigates the relationship between glucose measurements, various risk factors, and the likelihood of developing Type 2 diabetes in adult women. By conducting logistic regression, we found that genetic predisposition and lifestyle factors like high BMI and number of pregnancies increased the likelihood of diabetes. Our model revealed a counterintuitive negative association between blood pressure and diabetes risk, suggesting that higher blood pressure may slightly reduce the odds of diabetes. We also concluded that an interaction effect between glucose levels and genetic predisposition was significant. Our approach prioritizes sensitivity in diagnosis and recognizes the severe implications of misdiagnosing diabetes in order to inform prevention and treatment strategies. 

## Data Dictionary
Our dataset includes 2,768 observations from the National Institute of Diabetes and Digestive and Kidney Diseases and Frankfurt Hospital.
| Variable Name  | Description |
| ------------- | ------------- |
| ID  | <dbl> Unique identifier of an individual patient  |
| Pregnancies  | <dbl> Number of times a patient has been pregnant |
| Glucose  | <dbl> Plasma glucose concentration over 2 hours in an oral glucose tolerance test |
| BloodPressure  | <dbl> Diastolic blood pressure (mmHg) |
| SkinThickness  | <dbl> Triceps skinfold thickness (mm) |
| Insulin  | <dbl> 2-Hour serum insulin (muU/ml) |
| BMI  | <dbl> The body mass index if a patient (weight in kg/height in m^2) |
| DiabetesPedigreeFunction  | <dbl> Diabetes pedigree function, a genetic score of diabetes |
| Age  | <dbl> The age of the patient in years |
| Outcome  | <dbl> Binary classification indicating the presence (1) or absence (0) of diabetes |
