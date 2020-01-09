# Bank_marketing
Assessing the success of a direct marketing campaign at a Portuguese Bank


## Retail Bank Marketing Campaign Analysis

When banks, or other companies with a retail presence, create new products, the success of the marketing campaign can make or break the launch.  Being able to use statistical methods to classify the productivity of the marketing campaign will help drive further innovation and be able to efficiently allocate resources for future marketing efforts.

I reviewed the data collected from direct marketing campaigns of a Portuguese banking institution. The method of marketing consisted of customer phone calls. Most potential subscribers required multiple touch points to determine if the customer had subscribed to the featured product.

The product for this focused analysis is a term deposit, a cash investment that is held at a financial instituion at an agreed interest rate for a fixed term (amount of time).

I built a classification model to correctly analyze the binary customer behavior (yes - subscribed or no - did not subscribe).

This project will satisfy the third project requirement for the Data Science Bootcamp at the Flatiron School.

![bank](images/bank.png)


### The Data
The original source data can be found at:  http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#

Converting the target variable form a 'yes/no' to a \[1,0] leads to the first useful insight: an 11.3% Sucess rate on a phone marketing campaign.  From my knowledge of retail phone sales, this is very reasonable.  A direct phone  marketing approach is worth repeating if we can identify these 'yes' customers in advance.  Then it's only a matter of making all the calls.


