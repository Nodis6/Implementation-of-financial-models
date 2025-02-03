We are working on a binary classification problem to predict loan defaults. 
This involves building a model that can determine whether a loan applicant is likely to default (fail to repay) their loan based on various features like age, income, loan amount, property value, etc.

We are implementing two approaches:
  * Splitting the dataset based on loan applicant type (single or couple) and building separate models.
  * Feature engineering by combining age features and creating an indicator for loan applicant type, followed by model building on the modified dataset.

The primary objective is to build a model with high accuracy and recall, prioritizing the correct identification of loan defaulters.
