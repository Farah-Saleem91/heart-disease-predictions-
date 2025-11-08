![8_Main_Types_of_Heart_Disease](https://github.com/user-attachments/assets/3314839d-4a7c-4b7c-bfc4-d269239f6a8e)

# Heart-disease-predictions
Artificail Neural Network for heart disease predictions 


In this assignment you will create a simple network	using dense layers.  You will also create 2 more versions of it where you adjust the number of layers and neurons per layer to see if you can achieve better performance.

Task: Create a deep learning model to predict heart disease in populations at risk.  
Data Source: Kaggle Heart Disease Dataset
Direct link to data: heart.csv

TASK: Use a neural network to predict heart disease using the given data.

**Make sure you:**

1. Explore and clean the data if needed.
2. Perform a train-test split on your data.
3. Use a column transformer to scale the numeric features and one-hot encode the categorical features.
4. Define your base sequential model.
5. Include the number of features of each sample in your input layer.
6. Use the correct activation function and the correct number of neurons for your output layer.
7. ompile your model with the correct loss function and an optimizer (‘adam’ is a fine choice)
8. Include a validation split when fitting the model.
9. Plot your model’s training history.
10. Evaluate your models with appropriate metrics.

After you’ve created, fit, and evaluated your first model, try 2 more versions of it with different numbers of layers and neurons to see if you can create a model that scores better on the testing data.
## Data Source 
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

| Data Dictionary: | |
|---|---|
| Age: | age of the patient [years] |
| Sex: | sex of the patient [M: Male, F: Female] |
| ChestPainType: | chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic] |
| RestingBP: | resting blood pressure [mm Hg] |
| Cholesterol: | serum cholesterol [mm/dl] |
| FastingBS: | fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise] |
| RestingECG: | resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria] |
| MaxHR: | maximum heart rate achieved [Numeric value between 60 and 202] |
| ExerciseAngina: | exercise-induced angina [Y: Yes, N: No] |
| Oldpeak: | oldpeak = ST [Numeric value measured in depression] |
| ST_Slope: | the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping] |
| HeartDisease: | output class [1: heart disease, 0: Normal] |


