# DOMAIN : BANKING 

- ### CONTEXT 
 CNB Bank deals in all kinds of car loans. Customer first apply for loan after that company validates the customer eligibility for loan. In case the 
 borrower doesn’t pay back the loan, the losses are to be incurred by the bank. LGD stands for Loss given default so it means when a customer at a 
 bank defaults on his loan how much money does the bank lose. The customer might have paid some amount back or no amount at all.The bank wants to
 know if the amount the bank loses can be predicted for new customers who apply for a loan from the past data of all defaulters and their pending 
 amounts.


- ### PROBLEM
 The bank wants to automate the loss estimation based on customer detail provided while applying for loan. These details are Age, Years of Experience,
 Number of cars, Gender,Marital Status. To automate this process, they have given a problem to identify the loss estimation given that the customers
 is a defaulter, those are eligible for loan amount so that they get to know what features are leading to defaults up to which amount. Here are the
 details about the data set: 


- ### DATASET
  LGD.csv

Variable - Description 

1. Ac_No - The account of customer used as identifier  

2. Age - Age of borrower (16-70) 

3. Years of Experience - Working experience (0-53) 

4. Number of Cars - Possessed cars (1, 2, 3, 4) 

5. Gender - Male/Female 

6. Married - Married/Single 

7. Loss in Thousands - Target variable

- ### Notebook 
  Linear_Regression_LGD_Dataset/ipynb