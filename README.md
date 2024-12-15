## Lumpy Skin Disease Prediction Using Machine Learning
## 🔍 Project Overview
The goal of this project is to predict the occurrence of Lumpy Skin Disease (LSD) in cattle using machine learning techniques. The project leverages a dataset containing environmental, climatic, and geographical features to build predictive models for identifying affected regions.
Lumpy skin disease virus (LSDV) belongs to the family Poxviridae, subfamily Chordopoxviridae, and genus Capripoxvirus. LSD is a disease of cattle characterised by fever, nodules on the skin, mucous membranes and internal organs, emaciation, enlarged lymph nodes, oedema of the skin, and sometimes death.


<img width="357" alt="4443-Multimedia-30814-1-17-20240711" src="https://github.com/user-attachments/assets/73b5ff02-b5ab-4974-a18c-ad01542c9220" /> 
     
## 📊 Dataset Overview
Entries: 24,803 rows

Features: 17 columns

## The dataset comprises the following columns:
 ![image](https://github.com/user-attachments/assets/62cbc30d-97f8-48af-a20f-efb7c5755c55)

## 📂 Workflow Outline

**Read Data**
Importing the dataset and inspecting its structure.

**Preprocessing**
Handling missing values (if any).
Feature scaling/normalization for numeric columns.
Encoding categorical variables.

**Visualization**

Exploratory Data Analysis (EDA) to identify trends and relationships in the features.
Visualization of spatial distribution, temperature effects, and other climatic factors.
Modeling

**Baseline Model:** Logistic Regression 

**Additional Models:**  Random Forest, and Gradient Boosting techniques , SVM.

## Class Imbalance Handling

Apply SMOTE (Synthetic Minority Over-sampling Technique) to deal with any imbalance in the target variable (lumpy).
## Hyperparameter Tuning

Using GridSearchCV to optimize model performance.
Feature Reduction

Perform PCA (Principal Component Analysis) to reduce dimensionality and improve efficiency.
## ⚙️ Tools and Libraries

**Programming Language:**  Python

**Libraries:**

Data Handling: pandas, numpy

Visualization: matplotlib, seaborn

Machine Learning: scikit-learn, imbalanced-learn

## 🔑 Key Steps
Clean and preprocess the dataset (features and target).
Build baseline and advanced classification models.
Apply SMOTE to balance the lumpy column (0/1 distribution).
Use GridSearchCV for hyperparameter optimization.
Evaluate models using metrics like Accuracy, Precision, Recall, and F1-Score.
Visualize and interpret model results.
## 🎯 Outcome
This machine learning pipeline predicts regions where Lumpy Skin Disease may occur, leveraging environmental and climatic variables. The results can help in early intervention and disease management for cattle populations.

