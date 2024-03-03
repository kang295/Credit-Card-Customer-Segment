# Credit Card Customer Segmentation using Clustering 💳

## Project Description 📌: 
Synthesize a sample dataset comprising a **recent 6-month** usage behavior of approximately 9000 active credit card holders. The dataset is structured at the customer level and encompasses 18 behavioral variables.

## Objective: 
Utilize cluster analysis to segment credit card customers for effective marketing strategies.

## Project Overview 📖: 
1. **Data Import** & **Understanding**
   - Insights: Initial glimpse into the dataset, understanding the structure and the type of data we're dealing with.

2. **Data Preprocessing** & **Exploratory Data Analysis (EDA)** 
   - **Missing Values & Feature Drop**: Tackling the challenges of incomplete data and irrelevant features to streamline our analysis.
   - **EDA Techniques**:
     - Histograms: Visualizing distributions of numerical variables.
     - Boxplot: Identifying outliers and the spread of the data.
     - Heatmap: Unveiling correlations between variables.

3. **Feature Engineering** 
   - Addressing right-skewed data with 'Square root transformation' to normalize distributions and improve model performance.

4. **Pre-Modeling** 
   - Scaling: Standardizing the range of our features for optimal clustering.
   - PCA (Principal Component Analysis): Reducing dimensionality while retaining the essence of our data.
   - Explained variance ratio

5. **Model Building** 
   - **KMeans Clustering**: Segmenting our customers into meaningful groups based on their behavior and attributes.

6. **Cluster Interpretation** 
   - Diving deep into each cluster to understand the defining characteristics and behaviors of segmented customer groups.

## Data Dictionary 📚:
- `CUST_ID`: Identification of credit card holder
- `BALANCE`: Amount of credit you've used on your card, which includes charges made
- `BALANCE_FREQUENCY`: How frequently the balance is updated, score between 0 and 1
- `PURCHASES`: Amount of purchases made from the account
- `ONEOFF_PURCHASES`: Maximum purchase amount in single transaction
- `INSTALLMENTS_PURCHASES`: Amount purchase in installment (할부구입)
- `CASH_ADVANCE`: The user's advance payment in cash (카드대출)
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

## Clusters and Insights per Groups 🙌🏻
**Cluster 0**:
For this group, offering products that incentivize full payments, such as cashback rewards, could be effective. Additionally, promoting low-interest rates on cash advances or providing offers that encourage more frequent use of the card for purchases could increase engagement.

**Cluster 1**:
For this group, offering products that incentivize full payments, such as cashback rewards, could be effective. Additionally, promoting low-interest rates on cash advances or providing offers that encourage more frequent use of the card for purchases could increase engagement.

**Cluster 2**:
Customers in this cluster might respond well to rewards that benefit frequent and high spenders, such as tiered rewards programs. Offers that encourage larger purchases or bonus points for installment purchases could also be appealing. Additionally, providing incentives for paying off balances could encourage more full payments.
