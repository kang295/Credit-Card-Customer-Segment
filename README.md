# Credit Card Customer Segmentation using K-Means Clustering (with PCA) 💳

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
     - Distribution Plot: Visualizing distributions of numerical variables.

4. **Pre-Modeling**
   - Converting numerical values in each column to categorized values for better scaling.
   - Scaling: Standardizing the range of our features for optimal clustering.
   - Determining the right K-value using the Inertia method and silhouette score.

6. **Model Building** 
   - **KMeans Clustering**: Segmenting our customers into meaningful groups based on their behavior and attributes.

7. **Cluster Labeling** 
   - Diving deep into each cluster to understand the defining characteristics and behaviors of segmented customer groups.
   - Understanding the characteristics of each cluster.

8. **Cluster Visualization**
   - PCA (Principal Component Analysis): Reducing dimensionality while retaining the essence of our data.

## Data Dictionary 📚:
- `CUST_ID`: Identification of credit card holder
- `BALANCE`: Amount of credit you've used on your card, which includes charges made
- `BALANCE_FREQUENCY`: How frequently the balance is updated, a score between 0 and 1
- `PURCHASES`: Amount of purchases made from the account
- `ONEOFF_PURCHASES`: Maximum purchase amount in a single transaction
- `INSTALLMENTS_PURCHASES`: Amount purchased in installment (할부구입)
- `CASH_ADVANCE`: The user's advance payment in cash (카드대출)
- `PURCHASES_FREQUENCY`: Frequency of purchases made on a regular basis, a score between 0 and 1
- `ONEOFFPURCHASESFREQUENCY`: Frequency of purchases made in a single transaction (일시불 거래)
- `PURCHASESINSTALLMENTSFREQUENCY`: Frequency of done purchases in installments (할부 거래)
- `CASHADVANCEFREQUENCY`: Frequency of cash in advance
- `CASHADVANCETRX`: "Cash in advance" total transactions
- `PURCHASES_TRX`: Purchase total transactions
- `CREDIT_LIMIT`: Credit card limit of a user
- `PAYMENTS`: Total amount paid by the user
- `MINIMUM_PAYMENTS`: Minimum payment amount made by user
- `PRCFULLPAYMENT`: Percent of total charge paid by the user
- `TENURE`: Credit card tenure of a user (가입 유지일)

## Clusters and Insights per Groups 🙌🏻
**Cluster 0: *Moderate Spenders with Credit Leverage***

**Cluster 1: *Conservative Credit Users with Limited Spending***

**Cluster 2: *Balanced Spenders with Varied Payment Behavior***

**Cluster 3: *Active and Balanced Spenders with Prudent Credit Management***

**Cluster 4: *Novice Credit Users with Limited Engagement***

**Cluster 5: *Long-Term Credit Veterans with Conservative Spending Habits***
