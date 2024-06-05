# Telco Customer Churn Prediction

This repository contains the project on Telco Customer Churn Prediction. The project utilizes a dataset from Kaggle to analyze and predict customer churn.

## Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It contains information about telco customers, including their demographic, account, and usage data, as well as whether they have churned or not.

## Project Files

### Jupyter Notebook

The Jupyter notebook `Customer_Churn_Prediction.ipynb` contains the following sections:

1. **Importing Libraries**: 
   - Essential libraries like pandas, numpy, seaborn, matplotlib, and sklearn are imported for data manipulation, visualization, and modeling.

2. **Importing the Data**:
   - The dataset is loaded into a pandas DataFrame.
   - `df=pd.read_csv("/Users/trivikramgss/Documents/Telco_Project/WA_Fn-UseC_-Telco-Customer-Churn.csv")`
   
3. **Exploratory Data Analysis (EDA)**:
   - Basic statistics and insights about the dataset are gathered.
   - `df.shape`
   - `df.describe()`
   - `df.isnull()`
   - Unique values for each column are displayed.
   - `for column in df.columns:\n print('Column :{} - Unique Values: {}'.format(column,df[column].unique()))`
   
4. **Data Preprocessing**:
   - Handling missing values, data transformation, and feature engineering steps.

5. **Model Building**:
   - Various machine learning models are built and evaluated to predict customer churn.

6. **Evaluation**:
   - The performance of the models is assessed using appropriate metrics.

### Power BI File

The Power BI file `Customer_Churn.pbix` contains interactive visualizations that provide insights into customer churn. It includes:

- Demographic analysis of churned and retained customers.
- Account information analysis.
- Usage patterns analysis.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gss-18/Telco-Customer-Churn-Prediction.git

2. **Jupyter Notebook**:
    - Ensure you have Jupyter Notebook installed.
    - Open the notebook using Jupyter Notebook.
    - Run the cells to reproduce the analysis and models.

3. **Power BI File**:
    - Open the .pbix file using Power BI Desktop.
    - Explore the visualizations and gain insights from the data.

## Results
The models developed in this project aim to predict customer churn with high accuracy. The visualizations in the Power BI file provide a comprehensive understanding of the factors affecting customer churn.