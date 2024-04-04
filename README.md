# Customer Segmentation
### Overview
- Built a model using the K-means clustering algorithm to cluster customers with similar interest 
- The Model is trained on data collected from a well-known e-commerce website based on the customer’s search profile.
### Data Cleaning 
- Columns with Null Values are treated.
- Checking the count of gender, and treating the missing values.
### Model Building
![image](https://github.com/itskokila/Customer_segmentation/assets/129524618/86fa5dd8-4a21-4b9a-8b21-61c736f32487)
- The elbow method is a graphical method for finding the optimal K value in a k-means clustering algorithm.
![image](https://github.com/itskokila/Customer_segmentation/assets/129524618/6e4d7fa6-614d-49b4-bb0f-e0fafd20f95d)
- The Silhouette Score was evaluated for the quality of clustering results to get the optimum value.
- After getting the optimum K value use it as the number of clusters and perform the model fit.
![image](https://github.com/itskokila/Customer_segmentation/assets/129524618/c727d022-ff5a-40d9-bbaa-eb64fa8bd7eb)
- The model will provide the output of different clusters.
- Analyzing each cluster to get insights.

### Insights 
- In this 30,000 customer dataset,
   - Cluster 0 has 12432 customers 
   - Cluster 1 has 9128 customers 
   - Cluster 2 has 8440 customers.
  ![image](https://github.com/itskokila/Customer_segmentation/assets/129524618/ff892c46-9b50-4508-b0c9-4214f29ec668)
- Cluster 0 has the Lowest past orders but has the most searches, whereas
- Cluster 1 has the Highest past orders and average searches and at last
- Cluster 2 relatively has the Average past orders and average searches.

- Cluster 0 has done the most number of searches with 81477 searches.
- cluster 1 has done 64573 searches.
- Cluster 2 has done the least number of searches with 60093.

  





  
 
