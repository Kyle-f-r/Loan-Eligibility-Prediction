#### Context
___

Credit risk is the risk of financial loss resulting from the failure by a borrower to repay the principal and interest owed to the lender. The lender uses the interest payments from the loan to compensate for the risk of potential losses. When the borrower defaults on his/her obligations, it causes an interruption in the cash flow of the lender.

In the banking sector, this is an important factor to be considered before approving the loan of an applicant in order to cushion the lender from loss of cash flow and reduce the severity of losses. 

#### Objective
___

Easy House is a finance company that deals in several varieties of home loans. They have a presence across urban, semi-urban, and rural areas. Currently the customer first applies for a home loan, after which the company validates the customer's eligibility for that loan. 

Now, the company wants to automate this loan eligibility process. They want to harness their past customers' data to build a model to predict whether the loan should be approved or not. This would help the company prevent potential losses, save time and focus more on eligible customers.

#### Results
___
In order to classify customers, a Random Forest classifier was used. When deciding between optimizing for precision or recall, it was decided to optimize for higher recall, since it would be more costly to Easy House if predicting a customer is eligible for a loan when the customer is actually not (positive = not eligible).

The final confusion matrix showed the that recall on the test set was 70%.

<p align="center">
<img src="https://github.com/Kyle-f-r/Loan-Eligibility-Prediction/blob/master/images/Testset_confusionmatrix.png?raw=true" width="450" height="400" />
</p>
<p align="center">
    <em></em>
</p>