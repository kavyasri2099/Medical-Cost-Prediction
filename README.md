# Medical-Cost-Prediction  

Project Overview :  
This project aims to predict medical costs using various machine learning algorithms. The dataset includes information such as age, sex, BMI, number of children, smoking status, region, and charges. The goal is to predict the charges based on these features.    

Dataset:  

The dataset used in this project is insurance.csv. It contains the following columns:  
age: Age of the primary beneficiary  
sex: Gender of the primary beneficiary  
bmi: Body mass index, providing an understanding of body, weight relative to height, and the risk of health problems  
children: Number of children/dependents covered by health insurance  
smoker: Smoking status of the primary beneficiary  
region: The beneficiary's residential area in the US, divided into four regions  
charges: Individual medical costs billed by health insurance  

Requirements:  

The following Python libraries are required to run the code:  
numpy  
pandas  
seaborn  
matplotlib  
scikit-learn  

pip install numpy pandas seaborn matplotlib scikit-learn  
Data Preprocessing  

Loading the Data: The dataset is loaded using pandas.   
Handling Missing Values: The dataset is checked for missing values and duplicates.  
Splitting the Data: The dataset is split into training and testing sets (75:25 ratio).  

Feature Transformation:    
Numerical Features: StandardScaler is used to standardize the numerical features.  
Categorical Features: OneHotEncoder is used to encode categorical features. 

Model Training and Evaluation:  

The following machine learning models were trained and evaluated:  
  
- Linear Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Support Vector Regression (SVR)  
Mean Absolute Error (MAE) for each model were calculated and compared.  

Results :  

The performance of each model is as follows:  
Linear Regression :  
Mean Absolute Error: 4012.7152   
 
K-Nearest Neighbors:  
Mean Absolute Error:4146.45     

Decision Tree:  
Mean Absolute Error:3281.22   

Random Forest:  
Mean Absolute Error:2687.83  

Support Vector Regression:  
Mean Absolute Error: 4012.71  


Files :  
  
insurance.csv: The dataset used for this project.  
medical_cost_prediction.ipynb: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.  
medical_cost_prediction_presentation.pptx: PowerPoint presentation summarizing the project.  


Conclusion :  
  
This project demonstrates the use of various machine learning algorithms to predict medical costs. The results show that the Random Forest model achieved the best performance based on MAE. This model can be used to predict individual medical costs based on various features.  
