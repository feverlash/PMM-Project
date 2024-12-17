PMM Final Project

Case
Credit risk is the risk arising from the failure of a customer to pay its obligations on loans made to the Company.
The data provided is loan data from customers in one company.
The data consists of 26 columns containing the customer profile and loan transactions made by the customer.
For more details please see the ‘Data Description’ sheet.

Tasks
You and your team are a Credit Risk Management Team in one of the well-known companies.
You and your team are asked to analyse and create a classification model with the aim of knowing whether a loan made by a customer is good or bad.
The results of your analyses and models will be used by the Company to conduct screening in accepting or rejecting a customer when applying for a loan.

Description
Two data sets consisting of two csv files are provided:
[1] csv file with the name ‘Dataset’ is data that you can use as training data and testing models (there is already a classification that the loan is good (1) or bad (0).
[2] The csv file with the name ‘Data_Validation’ is data that you can use as validation of the model that has been formed (you must classify based on your model whether the loan is good (1) or bad (0).
For Model Validation format, please refer to the sheet ‘Model Validation Format’.
The project was completed within two weeks, from 14 November 2022 to 28 November 2022.
The model evaluation method used was Confusion Matrix.
There is no specific format for reporting the analysis process, model building and modelling results, so it depends on the creativity of each team.
The final assessment component will be determined by the lecturers in each class, namely Mr Nanang Susyanto and Mrs Dwi Ertiningsih.

Data Description
1. id Is the identity (unique number) of a loan transaction from a customer
2. member_id Is the identity (unique number) of a customer
3. loan_amnt Is the loan amount of the customer
4. funded_amnt Is the loan amount approved by the Company
5. term Represents the length of time (tenor) of the loan granted by the Company to the customer
6. int_rate Represents the interest given by the company to the customer
7. installment Represents the instalments paid by the customer
8. grade Represents the internal assessment classification (rating) of a customer's loan
9. sub_grade Represents the details of the internal assessment classification (rating) of a customer's loan
10. emp_title Represents the job level of a customer
11. emp_length Represents the length of work experience of a customer
12. home_ownership Represents the home ownership status of a customer
13. annual_inc Represents the annual income of a customer
14. verification_status Is the verification status of the customer's loan by the company
15. purpose Represents the purpose of the loan made by the customer
16. title Represents the details of the purpose of the loan made by the customer
17. zip_code Represents the postcode of the Customer's address
18. addr_state Represents the customer's address code
19. dti Represents the ratio between loan and income of the customer
20. total_acc Represents the number of loan transactions owned by a customer
21. total_pymnt Represents the total instalments that have been paid by the customer
22. total_rec_prncp Represents fees received by the Company related to the failure to pay the principal fee of the loan made by the Customer
23. recoveries Is a fee received back by the Company when a Customer has failed to pay the loan made
24. last_pymnt_amnt Represents the last instalment paid by the Customer to the Company.
25. application_type Represents the type of loan made by the customer
26. loan_status_class Is the loan classification status of a customer. If 0 is the customer's loan status is bad, or 1 is the customer's loan status is good.
