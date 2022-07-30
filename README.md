# Loan Application Status Prediction![image](https://user-images.githubusercontent.com/96686981/181925733-881add29-5ef1-4ae3-8202-7274595d4488.png)
# Problem Definition:-
This dataset includes details of applicants who have applied for loan. The dataset includes details like credit history, loan amount, their income, dependents etc. 
# The Objectives
The loan of the applicant will be approved or not on the basis of the details provided in the dataset.it is classification problem
# Data Directory
Gender-A person is either male or female	
Married-A person is single or married
Dependents-1, 2, 2+
Education-Graduate or not Graduate	
Self_Employed-A person is employed or not
ApplicantIncome-Applicant income
CoapplicantIncome-Coapplicant income
LoanAmount-Loan amount in thousands
Loan_Amount_Term-Term of loan in months
Credit_Histor-credit history meets guidelines
Property_Area-Urban/ Semi Urban/ Rural
Loan_Status-Loan approved (Y/N)
# Steps Included in the Project
# importing Libraries
![image](https://user-images.githubusercontent.com/96686981/181933541-555b31e9-8484-4e07-8b03-a4897923b7d4.png)
# loading Data
![image](https://user-images.githubusercontent.com/96686981/181933665-bd225dcb-cf06-47a9-a5ae-45b1ef9cb57d.png)
# Understanding Data
![image](https://user-images.githubusercontent.com/96686981/181933703-dfc854e6-c140-4e70-991f-6184479ed54a.png)
# Exploratory data analysis
![image](https://user-images.githubusercontent.com/96686981/181933877-16a4ab4e-4290-48d5-878a-59f01e9e0fae.png)
check null values
![image](https://user-images.githubusercontent.com/96686981/181933913-554d23ac-475b-4056-ba66-c5a53ebe7189.png)
![image](https://user-images.githubusercontent.com/96686981/181933943-3c3382c8-b121-481d-b79b-f5d619f5ef00.png)
![image](https://user-images.githubusercontent.com/96686981/181933995-b6f60069-cf2a-49dd-93be-d3ef61943612.png)
![image](https://user-images.githubusercontent.com/96686981/181934130-87d4527b-2f72-43ee-8aa7-060bb0fe1c04.png)
![image](https://user-images.githubusercontent.com/96686981/181934142-2ff42077-55e4-40bf-a991-1ab0c121f58b.png)
![image](https://user-images.githubusercontent.com/96686981/181934154-1354bb9f-b65b-4cac-8022-7954bd5d5229.png)
![image](https://user-images.githubusercontent.com/96686981/181934170-6b053495-ff33-4a32-b2ed-b0c48f5c11c7.png)
![image](https://user-images.githubusercontent.com/96686981/181934186-cac8263d-4552-49ed-b599-fe4bd9d6d473.png)
![image](https://user-images.githubusercontent.com/96686981/181934196-a0a37800-761b-443d-85aa-4c8ae2288ea5.png)
![image](https://user-images.githubusercontent.com/96686981/181934205-ad61659a-813e-45cc-ac8f-e5da2a5d0f0b.png)
![image](https://user-images.githubusercontent.com/96686981/181934226-fadb1f9d-73a6-46b0-8da3-3cba7f66c9f3.png)
![image](https://user-images.githubusercontent.com/96686981/181934259-870bb999-83e2-4ba4-8971-a9fbab82d975.png)
![image](https://user-images.githubusercontent.com/96686981/181934273-603f49a5-eece-4c52-a33f-ff7781650f60.png)
![image](https://user-images.githubusercontent.com/96686981/181934313-353f8430-c5cd-4067-aa1b-546f924f1d7b.png)
Checking Skewness and outliers
![image](https://user-images.githubusercontent.com/96686981/181934347-005b191b-9d8d-41bf-9e6d-b69251b5b000.png)
![image](https://user-images.githubusercontent.com/96686981/181934372-cb358fce-9d42-4e3c-a07f-9bfba9d08a9b.png)
![image](https://user-images.githubusercontent.com/96686981/181934387-7815a8b6-18dd-4e31-864b-973c4c06038b.png)
![image](https://user-images.githubusercontent.com/96686981/181934395-a72455a2-f7f8-4d19-b375-5e5940a317d3.png)
Checking Multicollinearity
![image](https://user-images.githubusercontent.com/96686981/181934442-6988711e-5cce-4070-9192-cec8c71a3694.png)
![image](https://user-images.githubusercontent.com/96686981/181934458-8f6d5425-20d4-4ab7-9e45-574dee9ed0ba.png)
Applying different models for  Classification Target Variable. 
# model building
Model Building

. First we will split our dataset into train and test dataset

. After that we will build multiple models for training and testing and will find out the best random_state for the best model.

. Thereafter, we will look for Cross Validation score to check the overfitting of data Finally, we will perform Hyper Parameter Tuning on our Best Model to improve the accuracy

Lastly we will save the tuned model for future use.
![image](https://user-images.githubusercontent.com/96686981/181934576-08338dea-ed7f-44a1-9f5c-03d9cf84f6a6.png)
![image](https://user-images.githubusercontent.com/96686981/181934586-32de3b08-1236-441d-9607-5314e9d35aad.png)
![image](https://user-images.githubusercontent.com/96686981/181934607-23d388c3-da22-4218-93a9-e9a8e8a08bcc.png)
![image](https://user-images.githubusercontent.com/96686981/181934617-c7b75b20-89b7-45c2-9b5c-859f5599c863.png)
![image](https://user-images.githubusercontent.com/96686981/181934650-9af9857e-5732-4e69-a5a6-21874c2994aa.png)
![image](https://user-images.githubusercontent.com/96686981/181934717-c7f11742-e973-4105-9d97-bfd4b21f57c9.png)
![image](https://user-images.githubusercontent.com/96686981/181934739-b23c9927-16e1-450b-a6a0-3bdcde9792aa.png)
![image](https://user-images.githubusercontent.com/96686981/181934754-12ab4ec1-5893-47f4-937f-8455f353df2a.png)
![image](https://user-images.githubusercontent.com/96686981/181934775-5e8d941e-0ff0-4ff2-b327-99754bf8cd11.png)
![image](https://user-images.githubusercontent.com/96686981/181934791-353d6080-31d7-41fa-9390-e0c675d0275e.png)
![image](https://user-images.githubusercontent.com/96686981/181934805-318c7d24-33b7-44ba-bf81-d8aea3f995da.png)
# Conclusion:
### SVS Classifier model has the best Accuracy i.e. 77%
### Performed Hyper Parameter Tuning using GridSearchCV, and Accuracy score was 75%, which is less so there is no need do hyper tuning.
### Drawn Distribution Plot between Acutal and Predicted Test Data, Which has Normally Distribution and shows that our Model is working very well.

