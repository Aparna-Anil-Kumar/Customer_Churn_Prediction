# Customer_Churn_Prediction

## Project Description
This project focuses on predicting customer churn in a telecom company using Machine Learning techniques. Customer churn refers to customers who are likely to stop using a company’s service. The goal of this project is to analyze customer data and build predictive models that can identify customers at risk of churning.

## Dataset
Dataset Used: Telco Customer Churn Dataset

The dataset contains customer information such as:
- Gender
- Tenure
- Contract Type
- Internet Service
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

## Technologies and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM

## Project Workflow

### 1. Data Loading and Understanding
- Loaded the dataset using Pandas
- Explored dataset structure using:
  - head()
  - tail()
  - shape
  - info()
  - describe()

### 2. Data Cleaning
- Checked for missing values
- Checked for duplicate records
- Removed unnecessary columns such as `customer ID`

### 3. Exploratory Data Analysis (EDA)
Performed visual analysis using:
- Count plots
- Histograms
- Box plots
- Correlation analysis

EDA helped identify patterns related to customer churn.

### 4. Data Preprocessing
- Split features and target variable
- Performed train-test split
- Applied Label Encoding for binary categorical columns
- Applied One-Hot Encoding using `pd.get_dummies()` for multi-category columns
- Aligned train and test datasets after encoding
- Applied Standard Scaling where required
