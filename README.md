# Loan_prediction-analysis-and-ml-model-

This project involves building a model to predict loan approval based on various attributes of the applicants. Below you will find the details of the attributes used in the dataset and their significance.

## Attribute Significance

| Attribute          | Significance                          |
|--------------------|---------------------------------------|
| **Loan_id**        | Unique loan ID                        |
| **Gender**         | Male/Female                           |
| **Married**        | Applicant married (Y/N)               |
| **Dependents**     | Number of dependents                  |
| **Education**      | Applicant education (Graduate/Undergraduate) |
| **Self-employed**  | Self employed (Y/N)                   |
| **ApplicantIncome**| Applicant income                      |
| **CoapplicantIncome** | Coapplicant income                 |
| **LoanAmount**     | Loan amount in thousands              |
| **Loan_Amount_Term** | Term of loan in months             |
| **Credit_history** | Credit history meet guidelines        |
| **Property_area**  | Urban / Semi-urban / Rural            |
| **Loan_status**    | Loan approved (Y/N)                   |

## Jupyter Notebook

The Jupyter Notebook contains the data analysis code and the results. You can view it directly on GitHub:

[View Jupyter Notebook](./data_analysis_ml.ipynb)

## Tableau Dashboard

The Tableau Dashboard provides an interactive visualization of the data. You can view it on Tableau Public:


### Project Description

- **Data Source:**
  The data has been taken from kaggle it's attributes and significance of attributes are discussed above.
  
- **Analysis Goals:**
  Build a ML Model for predicting whether the loan of the candidate(based on input data) will be approved or declined.

  **Key Findings:**
1.We can see that approximately 81% are Male and 19% are female.
2.Percentage of applicants with no dependents is higher.
3.There are more number of graduates than non graduates.
4.Semi Urban people is slightly higher than Urban people among the applicants.
5.Larger Percentage of people have a good credit history.
6.The percentage of people that the loan has been approved has been higher rather than the percentage of applicant for which the loan has been declined.
7.We can infer that percentage of married people who have got their loan approved is higher when compared to non- married people.
8.The percentage of applicants with either 0 or 2 dependents have got their loan approved is higher.
9.The percentage of applicants who are graduates have got their loan approved rather than the one who are not graduates.
10.There is hardly any correlation between Loan_Status and Self_Employed applicants. So in short we can say that it doesn’t matter whether the applicant is self employed or not.
- **Technologies Used:** The tools and technologies used by me are:
  1.Jupyter Notebook, Python and its various in-built libraries: For cleaning and analysing data and building ML model.
  2.Tableau : for building dashboard(for represnting data in visual format).
