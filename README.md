
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project can be run using Python version 3.*, and there are no additional libraries beyond the Anaconda distribution that are required. Ensure the following packages are installed before running the code:

1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scikit-learn
6. statsmodels

## Project Motivation<a name="motivation"></a>

Project Motivation
Hospital readmissions are a significant challenge, both financially and in terms of patient care. Nearly 20% of Medicare patients are readmitted within 30 days, costing the healthcare system $20 billion annually. High readmission rates often signal suboptimal care, poor discharge planning, or gaps in post-hospital support.

To address this, the Centers for Medicare and Medicaid Services (CMS) implemented the Hospital Readmission Reduction Program (HRRP), penalising hospitals with excessive readmissions. This has created an urgent need for data-driven strategies to predict and mitigate readmission risks.

The goal of this project is to assist CMS hospitals in reducing avoidable readmissions, which have both medical and financial consequences. By answering the key business questions, we aim to:

1. Identify the most influential factors contributing to readmissions, enabling hospitals to focus on these areas for improvement.
2. Develop predictive models to forecast the number of readmissions, allowing hospitals to allocate resources effectively.
3. Classify hospitals at risk of high readmission volumes, thus helping prevent penalties by warning those with the greatest need for intervention.

This project uses the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology, leveraging both regression and classification models to meet these goals. The dataset used for analysis is the CMS HRRP dataset, which contains hospital-level data related to readmissions from 2020-2023.

## File Descriptions <a name="files"></a>

This project consists of two main Jupyter Notebooks and a README file that showcase the analysis of the CMS HRRP (Hospital Readmissions Reduction Program) dataset. The notebooks focus on answering key business questions about predicting and classifying hospital readmissions. Here are the details of the files:

1. Regression_model.ipynb: This notebook covers the regression task, which predicts the Number of Readmissions at CMS hospitals. The notebook explores the correlation between features and the target variable, applies feature selection techniques, and builds regression models like Random Forest Regression, Linear Regression, and Decision Tree Regression. The goal is to identify the most important features and accurately predict the number of readmissions based on hospital characteristics.

2. Classification_model.ipynb: This notebook focuses on building a classification model to predict which hospitals are at risk of high readmission volumes, which could lead to penalties. It involves the creation of a target variable for high readmission volume and the implementation of classification models such as XGBoost and Random Forest. Key steps include feature selection, model training, and evaluation, with the aim to classify hospitals that are likely to face penalties due to excessive readmissions.

3. README.md: This file, which you are currently reading, provides an overview of the project, the business questions addressed, the data understanding and preparation steps, modeling techniques used, and the evaluation of both the regression and classification models.
## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@yudeshsubas/a-deep-dive-into-hospital-readmission-reduction-2252ba8838c1).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I must give credit to Centers for Medicare and Medicaid Services (CMS) for the data.  You can find the Licensing for the data and other descriptive information at the link available [here](https://data.cms.gov/provider-data/dataset/9n3s-kdb3#data-table).  Otherwise, feel free to use the code here as you would like! 

