# EDA on Pima Indians Diabetes Dataset  

This project performs Exploratory Data Analysis (EDA) on the Pima Indians Diabetes dataset. The dataset contains several medical predictor variables and one target variable (diabetes outcome). The objective is to analyze distributions, patterns, and relationships in the data that could help in understanding the onset of diabetes in female Pima Indian patients.  

# Dataset Description  
**Source:** UCI Machine Learning Repository  

**Features:**  
- **Pregnancies**  
- **Glucose**  
- **BloodPressure**  
- **SkinThickness**  
- **Insulin**  
- **BMI**  
- **DiabetesPedigreeFunction**  
- **Age**  
- **Outcome:**  
  - 0 → No diabetes  
  - 1 → Diabetes  

# Technologies Used  
- Python  
- Jupyter Notebook  
- Pandas, NumPy – data manipulation  
- Seaborn, Matplotlib – visualization  
- Scikit-learn – preprocessing and checks  
- SciPy – statistical analysis  

# Project Workflow  
- **Data Loading** – Imported dataset using Pandas  
- **Initial Data Inspection** – Checked for null values, data types, and descriptive statistics  
- **Data Cleaning** – Replaced invalid zero values in columns like Glucose, BloodPressure, BMI etc.  
- **Univariate Analysis** – Distribution plots and boxplots, identification of outliers  
- **Bivariate Analysis** – Pairwise scatter plots, correlation heatmap  
- **Multivariate Analysis** – PairGrid plots, distribution comparison across outcome groups  
- **Skewness & Kurtosis** – Analyzed distribution shape of variables  
- **Outlier Detection & Handling** – Applied IQR method, compared boxplots before and after removal  
- **Gaussian Check** – Used histograms and statistical tests (Shapiro, Anderson-Darling)  

# Key Insights  
- Glucose, BMI, and Age show a strong relationship with diabetes outcome  
- Several features are right-skewed and may require transformation before modeling  
- Significant outliers observed in Insulin and SkinThickness  

