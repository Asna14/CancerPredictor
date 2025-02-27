#Breast Cancer Survival Prediction
This project uses machine learning (SVM classifier) to predict whether a breast cancer patient will survive based on their medical and demographic data. The model takes input features such as age, tumor stage, lymph node involvement, and tumor size, standardizes the numerical values, and makes a prediction using a trained Support Vector Machine (SVM) model.
Key Features
1) User input for patient details
2) Data preprocessing (feature selection & standardization)
3) Machine learning-based survival prediction
4) Uses scikit-learn, NumPy, and pandas
WORKFLOW OF THE SYSTEM:
The user enters medical details such as age, tumor size, and cancer stage.
The input is converted into a structured format.
Numerical features are standardized using StandardScaler.
The trained SVM model predicts if the patient is "Alive" or "Dead".
PROJECT WORKFLOW:
CANCER_DATA ----> DATA PREPROCESSING ----> TRAIN_TEST_SPLIT ------> SVM MODEL -----> SVM CLASSIFIER <----- NEW DATA
                                                                                          |
                                                                                   PREDICTS (ALIVE OR DEAD) 
