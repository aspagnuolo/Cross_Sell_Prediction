# Health Insurance Cross Sell Prediction
mOur client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company. 

The dataset consists of the following properties:

- **id**: unique identifier of the policyholder.
- **Gender**: gender of the policyholder.
- **Age**: age of the policyholder. 
- **Driving_License**: 1 if the policyholder has a driving license, 0 otherwise.
- **Region_Code**: unique code for the policyholder's region.
- **Previously_Insured**: 1 if the policyholder already has a vehicle insured, 0 otherwise.
- **Vehicle_Age**: age of the vehicle.
- **Vehicle_Damage**: 1 if the policyholder has damaged the vehicle in the past, 0 otherwise.
- **Annual_Premium**: the amount that the policyholder must pay as a premium during the year.
- **Policy_Sales_Channel**: anonymized code of the channel used for the proposal (e.g. by email, by phone, in person, etc...)
- **Vintage**: number of days the policyholder has been a customer of the company.
- **Response**: 1 if the policyholder responded positively to the sales proposal, 0 otherwise. 

The purpose of the model is to predict the value of Response.

The project is divided into three parts: 
- exploratory data analysis (EDA);
- construction of different models to address the problem of class imbalance;
- choice of the best model.
