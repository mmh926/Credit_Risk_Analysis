# CREDIT RISK ANALYSIS
## Written by: Monica Holmes
### June 13, 2021


# This analysis applies machine learning (Supervised Learning) to solve a real world challenge: credit card risk built and evaluated using Scikit-Learn.

## PURPOSE: 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly, I evaluated the performance of these models and made a written recommendation (below) on whether they should be used to predict credit risk.

## 1. Naïve Random Oversampling:

  ![image](https://user-images.githubusercontent.com/78371845/129498213-1d18081f-c885-4fcc-bdf5-e4b17146e604.png)
  ![image](https://user-images.githubusercontent.com/78371845/129498218-4809fbd0-c6da-4601-b18f-cf39eb502048.png)


 
•	Balanced Accuracy Score: 65.14%

•	Precision Score - High Risk: 0.01

•	Precision Score - Low Risk: 1.00

•	High Risk Sensitivity: 0.67

•	F1 score is 0.02

 
## 2. SMOTE Oversampling:

  ![image](https://user-images.githubusercontent.com/78371845/129498227-e1b817bb-d180-4364-8c2b-8f6762089d98.png)

 
•	Balanced Accuracy Score: 62.67%

•	Precision Score - High Risk: 0.01

•	Precision Score - Low Risk: 1.00

•	High Risk Sensitivity: 0.61

•	F1 score is 0.02


## 3. Undersampling:

  ![image](https://user-images.githubusercontent.com/78371845/129498237-035435b2-2b2b-4a99-a48f-2df417e6fb70.png)

 
•	Balanced Accuracy Score: 52.93%

•	Precision Score - High Risk: 0.01

•	Precision Score - Low Risk: 1.00

•	High Risk Sensitivity: 0.61

•	F1 score is 0.01


## 4. Combination of Over and Undersampling:

  ![image](https://user-images.githubusercontent.com/78371845/129498273-dc3152ed-8d3f-425e-a3bb-e82591101df5.png)

 
•	Balanced Accuracy Score: 63.75%

•	Precision Score - High Risk: 0.01

•	Precision Score - Low Risk: 1.00

•	High Risk Sensitivity: 0.70

•	F1 score is 0.02


## 5. Balanced Random Forest Classifier:

  ![image](https://user-images.githubusercontent.com/78371845/129498279-0276e786-bef6-4176-a64e-89d48c38a7ba.png)

 
•	Balanced Accuracy Score: 78.85%

•	Precision Score - High Risk: 0.03

•	Precision Score - Low Risk: 1.00

•	High Risk Sensitivity: 0.70

•	F1 score is 0.06


## 6. Easy Ensemble AdaBoot Classifier:

  ![image](https://user-images.githubusercontent.com/78371845/129498291-b7ab24c4-e812-456a-821c-c05fe4ae99cd.png)

 
•	Balanced Accuracy Score: 93.17%

•	Precision Score - High Risk: 0.09

•	Precision Score - Low Risk: 1.00

•	High Risk Sensitivity: 0.92

•	F1 score is 0.16



# RESULT:

After comparing results of 6 classification technique, mentioned above, the Easy Ensemble ADA Classification technique is the most effective algorithm for classifying this data. The technique had the highest Accuracy score (93.17%), High Risk Precision score (0.09) and Sensitivity score (0.92).  It is important to note that the results of this models overall ability to predict risk is not optimum.




[Credit Risk Analysis README.docx](https://github.com/mmh926/Credit_Risk_Analysis/files/6644352/Credit.Risk.Analysis.README.docx)
