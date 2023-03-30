# credit-risk-classification

Analysis:

The purpose of this model was to find out the credit worthiness of borrowing customers.
Dependant variable (y value) in this analysis was the "loan status" indicating if a loan is healthy or at risk.
Independent Variables (x values) were loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.
In this analysis, we first split our data to traning and test sets. Then, define our dependent and independent variables. Next, we create logistic regression model and fit our original data to this model. Trained model is used to make predictions. Lastly, we evaluate the model`s performance.
Two diffeent Logistic Regression models were created by using the original data set and randomy over resampled data set (to get rid of the imbalances). In the end, their results -which was gathered with scikit-learn library- were compared.

#Results Of Model:

The data collected was used to first and then train the model.
When we tested the data we obtained the following results.
![Screenshot 2023-03-30 161950 png1](https://user-images.githubusercontent.com/116110534/228955114-316839d4-3403-449a-8ec4-0182dc40fe36.png)

![Screenshot 2023-03-30 161453 png 1](https://user-images.githubusercontent.com/116110534/228954002-7d5abc4b-baaf-4655-bdbe-95865e65fe66.png)


 When we trained the data the following results were obtaibned.
 
 ![Screenshot 2023-03-30 165422 png3](https://user-images.githubusercontent.com/116110534/228962274-e062108d-12b1-4075-9efb-9c928c6151d8.png)
 
 ![Screenshot 2023-03-30 161525 png2](https://user-images.githubusercontent.com/116110534/228954124-736c62f0-c6e5-48cc-938c-4c155ed19533.png)

Randomly oversampling the data helps us to get higher balanced accuracy and recall scores. With higher recall value, model can predict risky loans more accurately,If they are predicted more accurately we can save the instituion from alot of defaults.
