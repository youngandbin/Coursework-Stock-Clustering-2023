# Data
- The data was collected from Wikipedia, Yahoo Finance, and Fama-French 3 Factor Model.
- contains information for publicly traded companies in the United States.
  - 1) Market capitalization
  - 2) Daily prices
  - 3) Fama-French 3 Factors

# Task
- Clustering 
  - 1) Describe clusters with company names and market capitalization, then compare clusters with F-F 3 factors.
  - 2) Try different clustering methods and explain how they differ from original results (k-means).
- Regression
  - Select one stock of your choice and perform regression fitting with the factor. Then, compare and interpret the results with the example of APPL stock shown in the PPT.
  - Refer to the values of beta, alpha, and R-squared.

# Conclusion
- To compare it with the Fama-French 3 Factor model, stocks were grouped into 3 clusters.
- Comparing with the three cluster centers:
  - Cluster 0 resembles the SMB factor, which oscillates around zero during the given period.
  - Cluster 1 exhibits a movement similar to the Mkt-RF factor.
  - Cluster 2 resembles the HML factor, which shows a consistent upward trend during the given period.
- Fitting the cluster factors:
  - The Apple stock, with the largest market capitalization, has a strong correlation with the Cluster 1 which is similar to the market factor.
  - The Apple stock, with the largest market capitalization, has a significant negative correlation with the size factor.
