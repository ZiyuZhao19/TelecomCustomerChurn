# Telecom Customer Churn Analysis
Customer attrition analysis with data visualization and machine learning

## Background
  Customer loss can be a serious concern for most companies across various industries including telephone service, Internet service, pay TV, insurance, financial service industries, and so on. Since losing customers might harm a business’s ability to grow and take away its advantages in competitions, churn analysis that evaluates a company’s customer loss rate is of great significance for businesses to retain and recover long-term customers. In this project, we aim to do a customer attrition analysis for a telecommunication service company and build machine learning models to predict whether a customer might be inclining to quit services based on his/her demographic, service, and account information. Also by interpreting data and some of the models, we want to understand why customers might choose to leave. The risks of misclassification are to falsely predict clients who are highly possible to churn to be loyal and miss the opportunities of applying customer retention strategies to prevent losing them to competitors. In professional settings, inputs from the company’s customer service and marketing departments and, more ideally, feedback from customers themselves in forms of survey and questionnaire should also be considered during the process of modeling.
  
## Dataset
  The data we will be using is the Telco Customer Churn dataset on [Kaggle: Teleco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn). The dataset has 7043 rows and 21 columns with no null values. While each row represents a customer record, the columns show data on the customers’ demographic, services, and account information. The variables of gender, age-range, partner, and dependent status will be the protected attributes for the fairness evaluation task and will not be included in the primary modeling task.
  
## Structure
  This project is in the structure as the following:
  
    Section 0: Loading Data
  
    Section 1: EDA
  
      1.1 General Customer Statistics
      
      1.2 Churn Comparison
      
    Section 2: Primary Task
  
      2.1 Pre-processing
      
      2.2 Model Training
      
    Section 3: Fairness Audit
  
## Collaboration
  This project is group work. I was responsible for the EDA comparison analysis part and the primary model training and tuning task. EDA general analysis and Fairness audit tasks were undertaken by Xuechuan Song.
