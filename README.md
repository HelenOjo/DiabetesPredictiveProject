# DiabetesPredictiveProject

![Project_69-03](https://github.com/user-attachments/assets/0846d72c-e140-43aa-9f04-4cb4f8e95952)

## Business Problem
Diabetes is a health hazard for the patients of Stark Health and a high cost as well. Even though diagnostic tools are available at this health facility, early detection is less precise. Early interventions are missed due to a lack of proper early detection methodologies, which negatively affects the patient's health and increases costs associated with advanced stages of the disease. The bottom line is an urgent need for better, more accurate, and reliable predictive tools to enable early identification and treatment of at-risk individuals.

## Solution Strategy
My solution to solve this problem will be the development of a data science project. This project will have a machine learning model which can predict patients who have diabetes. It'll help the clinic with timely interventions and reduce diabetes progress. Contribute to reducing the costs of advanced diabetes management for patients.

## Data Source
The dataset was provided by 10Alytics

## Step by Step Workflow
Step 01. Data Description: the data will be collected and studied. The missing values will be treated or removed. The data will be comprehended.
Step 02. Feature Engineering: In this section, a mind map will be created to assist in the creation of the hypothesis and the creation of new features. These assumptions will help in exploratory data analysis and may improve the model scores.
Step 03. Exploratory Data Analysis: The exploratory data analysis section consists of univariate analysis, bivariate analysis and multivariate analysis to assist in understanding the database.
Step 04. Data Preparation: In this section, the data will be prepared for machine learning modelling. Therefore, they will be transformed to improve the learning of the machine learning model, thus they can be encoded, oversampled, subsampled or rescaled.
Step 05. Feature Selection: select the best columns to be used for the training of the machine learning model. This reduces the dimensionality of the database and decreases the chances of overfiting.
Step 06. Machine Learning Modeling: It aims to train the machine learning algorithms and how they can predict the data.
Step 07. Hyparameter Fine Tuning: First select the best model to be applied in the project, it's important to fine-tune the parameters to improve its scores. The same model performance methods applied in step 06 are used.

## EDA

![Screenshot 2025-01-05 195327](https://github.com/user-attachments/assets/63f14506-6d8d-4ddc-b059-1f42606d134d)

The age group above 66 years has the highest count of diabetes cases (1) while the lowest is in the 0-12 age group meaning the prevalence of diabetes tends to increase progressively with age.

![Screenshot 2025-01-12 212948](https://github.com/user-attachments/assets/9e86e934-6a4c-4e0e-9865-c2cac70e1ef1)

Obese patients have the highest number of diabetic patients, generally, all category has diabetic patients 

![Screenshot 2025-01-05 195023](https://github.com/user-attachments/assets/13b9275b-b936-4603-8e4a-6b1306960a2d)

Individuals with HbA1c levels ranging from 5.7% to 9.0% are highly indicative of diabetes or prediabetes.

![Screenshot 2025-01-12 212948](https://github.com/user-attachments/assets/e63433eb-93a6-493e-a8ab-81d29a666a5a)

This shows the distribution position of diabetes amongst other variables and their relationship with each other

![Screenshot 2025-01-12 212948](https://github.com/user-attachments/assets/edfd9340-7727-4aa1-80d3-ed5acac1d62a)

Amongst the variables, there is a strong correlation between diabetes and HbAIc level followed by diabetes and blood-glucose level.

## Model Performance
Four models were trained with class weight

### XGB Classifier
![Screenshot 2025-01-12 214950](https://github.com/user-attachments/assets/043d4a4e-2675-4323-968a-83a483ea9911)

### Logistic Regression
![Screenshot 2025-01-12 215245](https://github.com/user-attachments/assets/376be735-6906-4bdf-9ac1-7a284daa3440)

### Random Forest
![Screenshot 2025-01-12 215401](https://github.com/user-attachments/assets/7257e803-3aba-4d15-872b-87fe718c7152)

### SGD Classifier
![Screenshot 2025-01-12 215602](https://github.com/user-attachments/assets/79ebeb1c-08f1-48b0-b2e9-5f7e83c9677b)

Using Class weight to trained the model, the Logistic Regression and SGD Classifier models improved while the  XGB Classifier and Random Forest remain the same accuracy and recall.

## Hyperparameter fine tune
Using hyperparameter Tuning for the model the Random Forest is better with recall score of 73%. From the metrics it is quite clear that the model is able to predict the diabetes quite effectively, with accuracy 97%.

### Random Forest Classifier Model
![Screenshot 2025-01-12 220205](https://github.com/user-attachments/assets/e784e8c7-66ec-40c2-92e5-c062c916fa67)

## Conclusion
From the exploratory data analysis, I have concluded that diabetes depends upon two factors which are the HbA1c level and Blood glucose level of the patient. BMI and Age play less significant roles in a patient having diabetes though diabetes is prominent in older years these can be a result of another factor.

The models performed pretty well, however, the Random Forest Classifier have excellent results with 97% accuracy.




