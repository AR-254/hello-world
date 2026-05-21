1. Why is this unsupervised learning?
Because the dataset has no labels

2. Why remove CUST_ID?
Because it is only an identifier and does not represent customer behavior.

3. Which columns had missing values?
CREDIT_LIMIT 1 value and MINIMUM_PAYMENTS (313 values).

4. How were missing values handled?
Using mean imputation.

5. Why is scaling important?
Because K-Means is distance-based and features have different ranges, so scaling ensures fair contribution.

6. Which K value did you choose?
K = 3 Based on the silhouette score results,

7. Cluster description (general):
Clusters represent different customer types such as low spenders, regular users, high-value customers, and cash advance users.

8. High-value customers cluster:
The cluster with high PURCHASES, CREDIT_LIMIT, and PAYMENTS.

9. Cash advance cluster:
The cluster with high CASH_ADVANCE and CASH_ADVANCE_TRX.

10. Marketing use:
Companies can target each cluster with personalized offers to improve retention and increase revenue.
