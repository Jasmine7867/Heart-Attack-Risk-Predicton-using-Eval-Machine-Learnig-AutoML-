# Heart-Attack-Risk-Predicton-using-Eval-Machine-Learnig-AutoML
 In this project Make an app which will help us to predict the risk of Heart Attack a person have
 Use the Various Algorithms to predict the resul and see which one suits best and then use the Auto ML Library Eval ML to predict the results
 Steps follows :
 1.Data Analysis
 2.Feature Engineering
 3. Standardization
 4. Model Building
 5.Predictions

1.Data Analysis : Understanding Dataset 
  Age: Age of the patient
  sex: sex of the patient
  exang:exercise induced angina(1=yes,0=no)
  ca=Chest pain type 
    1. value 0:typical angina
    2. value 1:atypical angina
    3. value 2: non-anginal pain
    4. value 3:asymptomatic
  trtbps:resting blood pressure(in mm Hg)
  chol:cholestrol in mg/dl fetched via BMI sensor
  fbs:(fasting blood sugar> 120 mg/dl) (1=true,0=false)
  rest_ecg:resting electrocardiographic restuls
     1. value 0:normal
     2.value 1:having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of 0.05>mV)
     3.value 2: showing probable or definite left ventricular hypertrophy by Estes'Criteria
 thalach:maximum heart rate achieved
 target:0=less chance of heart attack,1=more chance f heart attack

 Heart disease is one of the leading causes of death worldwide. Early prediction of heart attack risk can help in timely medical intervention.
This project uses EvalML (Automated Machine Learning) to build an optimized machine learning pipeline that predicts whether a person is at risk of a heart attack based on medical attributes.

EvalML automatically handles model selection, feature engineering, and hyperparameter tuning, making the process efficient and accurate.
Objectives:
To predict heart attack risk (Binary Classification: Risk / No Risk)
To automate model selection using EvalML AutoML
To evaluate model performance using standard ML metrics

Technologies and tools used 
1.Python
2.EvalML (AutoML)
3.Scikit-learn
4.Pandas & NumPy
5.Matplotlib / Seaborn
6.Jupyter Notebook

Dataset Description

The dataset contains medical attributes commonly used to detect heart disease, such as:
Feature	Description
age	Age of the patient
sex	Gender (1 = Male, 0 = Female)
cp	Chest pain type
trestbps	Resting blood pressure
chol	Serum cholesterol
fbs	Fasting blood sugar
restecg	Resting ECG results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina
oldpeak	ST depression
slope	Slope of peak exercise
ca	Number of major vessels
thal	Thalassemia
output	Target variable (0 = No Risk, 1 = Risk)


Project Workflow:
Data Loading and Exploration
Data Preprocessing
Feature & Label Separation
Train-Test Split
AutoML Pipeline Creation using EvalML
Model Training & Optimization
Performance Evaluation
Prediction Results

 AutoML with EvalML,
 EvalML automatically:
 1.Tries multiple ML algorithms
 2. Selects the best pipeline
 3.Optimizes hyperparameters
 4.Evaluates models using metrics like:
 5.Accuracy
 6.Precision
 7.Recall
 8.ROC-AUC
This reduces manual effort and improves performance.

Model Evaluation:
The best-performing model is selected based on evaluation metrics.
EvalML provides a ranked leaderboard of pipelines for comparison.
                    
