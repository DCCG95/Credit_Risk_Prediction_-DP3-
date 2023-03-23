# Credit Risk Prediction

The problem presented below consists of evaluating credit risk models. Basically, when requesting a loan from a financial institution, we face two problems:

- Willingness to Pay.
- Economic capacity to meet the payment.

For this data project, there are 2 main objectives.

- Perform clustering to see what types of clients the bank has.
- Create a classifier that indicates whether the loan is good or not.

The dataproject includes 3 types of datasets:

- Demographic data (train_demographic_data.csv). Information about the client such as age, employment, education, etc.

- Performance Data (train_performance.csv). This dataset includes loans from clients that need to be predicted. Basically, we need to predict whether this loan would pass the model given the historical records of previous loans and demographic data of a client.

- Previous loan data (train_previous_loan.csv). This dataset includes all previous loans that the client had before the previous loan for which we want to predict the performance. Each loan will have a different systemloanid, but the same customerid for each client.
