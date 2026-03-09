# german_credit_risk_prediction

# Project Title: Credit Risk Prediction Using Machine Learning
## Project Overview

This project aims to develop a machine learning solution to predict whether a loan applicant is likely to be a good or bad credit risk using the German Credit dataset. The purpose is to support financial institutions in making faster, more accurate, and more consistent lending decisions. By combining data analysis with predictive modeling, the project helps reduce loan default risk while improving the quality of customer approval decisions.

## Business Problem

Credit assessment is a critical part of lending, but traditional evaluation methods often rely on manual review, rigid approval rules, or subjective judgment. This can create several problems for banks and lenders. Approving high-risk applicants may lead to loan defaults, increased bad debt, and lower profitability. At the same time, rejecting potentially creditworthy applicants may result in missed revenue opportunities and weaker customer acquisition.

As lending volumes grow, financial institutions need a more scalable and data-driven approach to assess risk. This project addresses that challenge by building a predictive model that identifies patterns linked to bad credit behaviour and uses them to classify credit applicants more effectively.

## Key Risk Attributes Identified from EDA

Exploratory Data Analysis showed that several applicant and loan-related attributes are more strongly associated with bad credit risk. The most important attributes include:

#### 1.Lower Account Balance
Applicants in lower account balance categories show a much higher proportion of bad credit risk.

#### 2.Poor Payment Status of Previous Credit
Customers with weaker repayment history or prior credit issues are more likely to fall into the bad credit group.

#### 3.Longer Duration of Credit
Bad credit applicants tend to have longer repayment periods, suggesting that longer-term loans may carry greater risk.

#### 4.Higher Credit Amount
Applicants requesting larger loan amounts are more likely to be associated with bad credit outcomes.

#### 5.Lower Savings and Stocks Value
Lower levels of savings are linked to weaker financial resilience and higher credit risk.

#### 6.Shorter Length of Current Employment
Applicants with less stable employment history tend to show a higher likelihood of bad credit classification.

These findings suggest that both financial strength and repayment behaviour are major drivers of creditworthiness.

## Project Approach

The dataset was first cleaned and prepared by converting categorical variables into numerical form through one-hot encoding. Exploratory analysis was then conducted to understand the distribution of credit risk and identify important attributes related to bad credit. After preprocessing, multiple machine learning classification models were trained and tested, including:

- Logistic Regression

- Decision Tree

- Random Forest

- Gradient Boosting

- Neural Network (MLP)

The target variable was Creditability, where the model predicts whether an applicant is a good or bad credit risk.

## Key Results

The project produced promising results, showing that machine learning can classify credit risk with relatively strong accuracy. The model performance results were as follows:

| Model | Accuracy |
|------|----------|
| Logistic Regression | 77.6% |
| Decision Tree | 71.2% |
| Random Forest | 77.6% |
| Gradient Boosting | 74.8% |
| Neural Network (MLP) | 77.2% |

The strongest-performing models were Logistic Regression and Random Forest, both achieving 77.6% accuracy. These results show that predictive analytics can provide meaningful support in distinguishing between higher-risk and lower-risk applicants.

## Business Value

This project creates value for banks, fintech firms, and lending institutions in several ways.

#### 1.Improved risk management
By identifying high-risk applicants earlier, the model helps reduce default rates and potential loan losses.

#### 2.Faster credit decisions
Automated prediction can shorten loan processing time and improve operational efficiency.

#### 3.More consistent evaluations
The use of data-driven models reduces subjectivity and supports more standardized decision-making across applications.

#### 4.Stronger portfolio quality
Better screening helps lenders approve more suitable borrowers and manage the overall quality of the credit portfolio.

#### 5.Scalability for digital lending
The solution can be integrated into credit scoring systems, loan approval workflows, or digital lending platforms to support large application volumes.

## Conclusion

This project demonstrates how machine learning can improve credit risk assessment by combining predictive accuracy with practical business insights. In addition to delivering model accuracy of up to 77.6%, the analysis also highlights the key attributes that contribute to bad credit risk, such as low account balance, poor repayment history, high credit amount, longer credit duration, low savings, and shorter employment history. This makes the solution valuable not only for prediction, but also for helping lenders better understand the drivers of risk and make smarter lending decisions.
