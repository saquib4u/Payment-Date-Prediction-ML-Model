# Payment-Date-Prediction-ML-Model
## Machine Learning Model to predict payment date for the invoices using XGBoost Regressor.

It is a Machine Learning Model in which users in the **Account Receivable department** do the following tasks on a daily basis:

● View data from various purchasers' invoices.

● View the invoice(s) from a certain buyer's various fields/attributes.

● Pre-process the invoice data via data pre-processing.

● With EDA and Feature Engineering, we may get account-level analytics to quickly
display and comprehend data.

● Get an estimate for when the invoice will be paid

### B2B Transactions ###
<p>
When a buyer company orders products from a seller company, the seller company sends an invoice to the buyer company. This products invoice includes information such as the specifics of the goods purchased and when they should be paid. In accounting, this is referred to as "Accounts Receivable."
Money due to the company by entities for the sale of items or services on credit is represented by Accounts Receivable.
<br><br>
</p>

**On the basis of the algorithm, MSE score, and R2 score, the models I have compared ML Models to determine which best suits the needs:**

1. Linear Regression

2. Decision Tree Regression

3. Random Forest Regression

4. Support Vector Regression

5. Extreme Gradient Boost Regression
<br><br>
### Conclusion:
I choose Random Forest Regression as it best suits the need.
The reason behind it is:
* XGboost is an efficient algorithm in terms of execution speed and it provides high delivery performance and accuracy as compared to any other Algorithms. On classification and Regression predictive modeling problems, XGboost dominates structured or tabular dataset.
* Also, We know from the comparisons data frame of various regression models  that the XGB Regressor model has the highest  R_Squaared (R2_Score) value of all the models, and as we know , we select model which have higher R-squared because in general, higher the R-squared the better the model fits in the data.
* And also, its MSE_Score has the lowest value than other algorithms.

**I got a prediction of when the invoice is going to get paid. In the new dataset we get the "clear_date" column which shows the date when payment is going to be cleared.**

## Resources:
* [Initial dataset](https://github.com/saquib4u/Payment-Date-Prediction-ML-Model/blob/main/dataset.csv)
* [Jupyter Notebook](https://github.com/saquib4u/Payment-Date-Prediction-ML-Model/blob/main/Payment_date_prediction.ipynb)
* [Final dataset](https://github.com/saquib4u/Payment-Date-Prediction-ML-Model/blob/main/final_dataset.csv)
