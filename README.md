# Loan-Repayment-Prediction

This project aims to predict whether clients will repay a loan or face difficulties using machine learning models. The dataset is provided by Home Credit, a service dedicated to providing lines of credit to the unbanked population. The goal is to develop models that can assist Home Credit in assessing loan repayment likelihood based on various client information.

Dataset Overview

The dataset consists of seven sources of data:

application_train/application_test: Contains information about each loan application at Home Credit. Each row represents a loan identified by the feature SK_ID_CURR. The training application data includes the TARGET column indicating loan repayment (0: repaid, 1: not repaid).

bureau: Provides data about a client's previous credits from other financial institutions. Each previous credit has its own row in bureau, potentially linked to one loan in the application data.

bureau_balance: Contains monthly data about previous credits in bureau. Each row represents one month of a previous credit, allowing for a detailed credit history.

previous_application: Includes information about previous loan applications for clients who have loans in the application data. Each current loan can have multiple previous loans.

POS_CASH_BALANCE: Offers monthly data about previous point-of-sale or cash loans clients have had with Home Credit.

credit_card_balance: Provides monthly data about previous credit cards clients have had with Home Credit.

installments_payment: Contains payment history for previous loans at Home Credit, recording both made and missed payments.

Scope of the Project

For this project, we will focus primarily on the main application training and testing data to establish a baseline model. While leveraging all available data might lead to more sophisticated models, this approach will allow us to build a foundational understanding of the problem before delving deeper into more complex analyses.

Working Steps

Exploratory Data Analysis (EDA): Understanding the distributions, correlations, and patterns within the main application data.

Baseline Model Creation: Developing initial models using the training data to establish a benchmark for performance.

Feature Engineering: Exploring additional features and potential data enhancements to improve model accuracy.

Model Evaluation and Improvement: Iteratively refining models, experimenting with different algorithms, and optimizing hyperparameters to enhance prediction capabilities.
