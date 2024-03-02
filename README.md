# Credit Card Customer Segmentation using Clustering 💳

## Project Description 📌: 
Synthesize a sample dataset comprising a recent 6-month usage behavior of approximately 9000 active credit card holders. The dataset is structured at the customer level and encompasses 18 behavioral variables.

## Objective: 
Utilize cluster analysis to segment credit card customers for effective marketing strategies.

## Project Overview: 
1. **Data Import** & **Overview** + **insights**
2. **Data Preprocessing** (Missing values, feature drop) and **EDA** (Histograms, Boxplot, Heatmap)
3. **Feature Engineering** on right-skewed data using 'Square root transformation'

## Data Dictionary:
- `CUST_ID`: Identification of credit card holder
- `BALANCE`: Balance amount left in the account to make purchases
- `BALANCE_FREQUENCY`: How frequently the balance is updated, score between 0 and 1
- `PURCHASES`: Amount of purchases made from the account
- `ONEOFF_PURCHASES`: Maximum purchase amount in single transaction
- `INSTALLMENTS_PURCHASES`: Amount purchase in installment (할부액)
- `CASH_ADVANCE`: The user's advance payment in cash (선납입)
- `PURCHASES_FREQUENCY`: Frequency of purchases made on a regular basis, score between 0 and 1
- `ONEOFFPURCHASESFREQUENCY`: Frequency of purchases made in single transaction (일시불 거래)
- `PURCHASESINSTALLMENTSFREQUENCY`: Frequency of done purchases in installments (할부 거래)
- `CASHADVANCEFREQUENCY`: Frequency of cash in advance
- `CASHADVANCETRX`: "Cash in advance" total transactions
- `PURCHASES_TRX`: Purchase total transactions
- `CREDIT_LIMIT`: Credit card limit of an user
- `PAYMENTS`: Total amount paid by the user
- `MINIMUM_PAYMENTS`: Minimum payment amount made by user
- `PRCFULLPAYMENT`: Percent of total charge paid by the user
- `TENURE`: Credit card tenure of an user (가입 유지일)
