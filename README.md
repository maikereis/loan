# Predict Loan Eligibility for Dream Housing Finance company

![](img/header.jpg)

<br>

# 1. Overview

_"Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan."_

See on [analyticsvidhya](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/#ProblemStatement)


<br>


# 2. The problem

 **1. Context:**

   A startup **SweetHome**, begins his operation of real state in Ames, Iowa. The main business is to buy and sell houses, like the [Zillow](https://www.zillow.com/).

 **2.The Bussiness Problem:**
   
   Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 

 **3. Stakeholders:**

   The company needs an accurate model, due to the risk involved in this type of operation.

   The CTO wants a model that can do the forecasts at the least cost possible.

   The development team needs a deployable model, lightweight, and scalable model.

       
<br>


# 3. Data

The dataset has 12 explanatory variables of customers and a target variable called _`Loan Status`_

* Loan Status - Loan approved (Y/N)
* Loan_ID - Unique Loan ID
* Gender - Male/ Female
* Married - Applicant married (Y/N)
* Dependents - Number of dependents
* Education	Applicant - Education (Graduate/ Under Graduate)
* Self_Employed	Self - employed (Y/N)
* ApplicantIncome - Applicant income
* CoapplicantIncome - Coapplicant income
* LoanAmount - Loan amount in thousands
* Loan_Amount_Term - Term of loan in months
* Credit_History - credit history meets guidelines
* Property_Area - Urban/ Semi Urban/ Rural


<br>
