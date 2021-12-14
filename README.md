# AI/ML Project - Heart Disease Diagnosis 🫀

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/146058811-db5d9600-dca9-4bf5-a355-7ebcce3f6592.jpg" style="width: 1000px;"/></p>

### Description:

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.

### Acknowledgements:
This dataset has been referred from Kaggle: \
https://www.kaggle.com/ronitf/heart-disease-uci

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to predict weather the a person will have heart diease or not.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Feature Selection/Extraction
6. Predictive Modelling
7. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. Target Variable Distribution**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/146058950-b79112da-31a2-4928-91db-576d79713adb.png" /></p>

**2. Categorical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/146059005-05fdcc35-bc8b-4ac5-b77c-08eca6e3aa0d.png)


**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/146059068-d45abe7e-6ad8-4f73-95ab-10182cde7860.png)
![image](https://user-images.githubusercontent.com/54996245/146059084-81b7a054-38c0-4830-9a99-6d56a0c62a33.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/146059104-9f92a475-2f2f-4239-8c6c-8fe705d5caa0.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/146059128-01670076-b8ad-426d-853c-34b737aff856.png)

**6. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/146059162-df818d16-72c4-47d8-ac29-367723eb58cf.png)

**7. VIF & RFE Scores & PCA Decomposition**
  
![image](https://user-images.githubusercontent.com/54996245/146059190-45214e2d-4938-4900-a535-ace56d2c2272.png)
![image](https://user-images.githubusercontent.com/54996245/146059216-7dd50dcb-6c3d-4100-8695-1318924e74d6.png)
![image](https://user-images.githubusercontent.com/54996245/146059229-9f9297d7-03b0-4b38-babc-db4b188508f4.png)
![image](https://user-images.githubusercontent.com/54996245/146059240-9cfa87d5-17a7-4034-b07b-725e36f6b79d.png)

**8. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/146059280-02337c33-da92-4b61-8181-d917e6bd383e.png)

**9. Tree Plot & Feature Importance in Random Forest
  
![image](https://user-images.githubusercontent.com/54996245/146059302-8433ecd5-a020-4d13-abd6-a104b758ecb0.png)
![image](https://user-images.githubusercontent.com/54996245/146059327-a83f4084-32a2-46b3-a03f-77a07a0b5112.png)


**10. ML Algorithm's Scores for the Dataset**
  
![image](https://user-images.githubusercontent.com/54996245/146059354-69b80785-aa32-484b-9ce3-f07f9c2ee974.png)
![image](https://user-images.githubusercontent.com/54996245/146059361-b43dc641-7197-43c3-a593-464d633b866a.png)

  
### Here are some of the key outcomes of the project:
- The Dataset was quiet totalling around 300 samples & after preprocessing 5.1% of the datasamples were dropped. 
- The samples were slightly imbalanced after processing, hence SMOTE Technique was applied on the data to  balance the classes, adding 9.2% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the feature-set.
- Feature Selection/Eliminination was carried out and appropriate features were shortlisted.
- Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The SVM, Boosting & Random Forest Classifier performed exceptionally well on the current dataset, considering Recall Score as the key-metric.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive, but comes at the cost of slight misclassifications.

