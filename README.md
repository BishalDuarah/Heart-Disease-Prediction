# Heart-Disease-Prediction
The project involved analysis of the heart disease patient dataset with proper data processing along with data visualization.

Then, different models were trained and and predictions are made with different algorithms Decision Tree, Random Forest,SVM,Logistic Regression.

Deployed with Streamlit UI- user inputs:'Age','Sex','ChestPainType','RestingBP','Cholesterol','FastingBS', 'RestingECG','MaxHR','ExerciseAngina','Oldpeak','ST_Slope'

Feature values conventions:
-Age: age of the patient [years]
-Sex: sex of the patient [0: Male, 1: Female]
-ChestPainType: chest pain type [3: Typical Angina, 0: Atypical Angina, 1: Non-Anginal Pain, 2: Asymptomatic]
-RestingBP: resting blood pressure[mm Hg]
-Cholesterol: serum cholesterol [mm/dl]
-FastingsBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
-RestingECG: resting electrocardiogram results [0: Normal, 1:having ST-T wave abnormality, 2: Left ventricular hypertrophy]
-MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
-ExerciseAngina: exercise-induced angina [1: Yes, 0: No]
-Oldpeak: oldpeak = ST [Numeric value measured in depression]
-ST_Slope: the slope of the peak exercise ST segment [0: upsloping, 1: flat, 2: downsloping]

Also User can Upload csv file with inputs columns and get predictions in one go.

Dataset used:https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
