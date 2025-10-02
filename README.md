# Interconnect
Create a machine learning model that predicts the churn of clients. 

**Objective:** The telecom operator Interconnect would like to be able to forecast their churn of clients. If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. Interconnect's marketing team has collected some of their clientele's personal data, including information about their plans and contracts. We were tasked with creating a machine learning model with this purpose.

**Method:** For this project, we will first start with exploring the data, making sure we don't have missing information, keeping only the columns relevant for the model, and creating some extra columns that might help with  getting a deeper understanding of the info.

Then we will proceed with training several models while evaluating their accuracy and ROC-AUC scores in order to select the best model for this task. These all will be evaluated against a random model. Once the best model has been selected, we will proceed with the final test on some part of the data that will be used only for this goal. 

**Conclusions:** The best performing model was the one created using the Logistic Regression in coordination with the following parameters: solver='liblinear', class_weight='balanced'. It was also highlighted that EDA can provide relevant information to guide marketing efforts like the present one.
