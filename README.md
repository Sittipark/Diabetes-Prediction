# Diabetes Prediction

## About the Project
**Goal:** To predict whether a person has diabetes based on various health indicators.

**Methodology:** This project employs a machine learning approach to analyze a dataset containing information about individuals' pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age. By leveraging techniques such as data exploration, preparation, modeling, and evaluation, we aim to develop a predictive model that can accurately classify individuals as having or not having diabetes.   

## Data Understanding

| Feature       | Description | 
| ------------- | ------------- |
| Pregnancies | Number of pregnancies | 
| Glucose |	Glucose level in blood |
| BloodPressure |	Blood pressure measurement |
| SkinThickness |	Thickness of the skin |
| Insulin	| Insulin level in blood |
| BMI |	Body mass index |
| DiabetesPedigreeFunction | Diabetes percentage |
| Age |	Age |
| Outcome	| Final result (1: Yes, 0: No) |

## Data Exploration
**Initial Analysis:**
- View data information and samples.
- Calculate descriptive statistics.

**Visualization:**
- Create **bar plots**, **histograms**, and **boxenplots** to understand data distribution and relationships.
- Analyze **correlations** between features.

## Data Preparation
- **Handling Missing Values:**
Identify and address missing data (e.g., imputation, removal).
- **Data Consistency:**
Ensure data consistency and uniformity.
- **Duplicate Detection:**
Check for and remove duplicate records.
- **Outlier Identification and Handling:**
Detect and handle outliers using appropriate methods (e.g., removal, capping).
- **Feature Engineering:**
Create new features or transform existing ones if necessary.
- **Encoding Categorical Variables:**
Convert categorical variables into numerical representations (e.g., one-hot encoding).
- **Scaling Numerical Features:**
Standardize or normalize numerical features to a common scale.
- **Train-Test Split:**
Divide the dataset into training and testing sets for model development and evaluation.

## Modeling
- **Algorithm Selection:**
Choose appropriate machine learning algorithms for classification **(Logistic Regression, Random Forest, Decision Tree)**.
- **Model Training:**
Train each model on the training set.
- **Model Evaluation:**
Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
- **Model Comparison:**
Compare the performance of different models to select the best candidate.




