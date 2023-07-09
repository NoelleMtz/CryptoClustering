# CryptoClustering
In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Find the Best Value for k Using the Original Scaled DataFrame
![elbowplot](https://github.com/NoelleMtz/CryptoClustering/assets/123044294/3a4ead37-c1db-49e5-b04b-14119644b3bd)

### Questions to answer:
**Question:** What is the best value for `k`?

**Answer:** 4 

## Cluster Cryptocurrencies with K-means Using the Original Scaled Data
![market_scaled_plot](https://github.com/NoelleMtz/CryptoClustering/assets/123044294/a7503cf6-61ce-4d63-a1cd-5f5c1902f21f)


## Optimize Clusters with Principal Component Analysis.
![PCARatio](https://github.com/NoelleMtz/CryptoClustering/assets/123044294/fc1fbe5b-c581-42f0-b36a-5d449f09ad68)
### Answer the following question: 
**Question:** What is the total explained variance of the three principal components?

**Answer:** 89%

## Find the Best Value for k Using the PCA Data

![elbow_pca_plot](https://github.com/NoelleMtz/CryptoClustering/assets/123044294/f1bc2cd7-bb72-4b09-927f-9562f2fd209c)

### Answer the following questions: 

* **Question:** What is the best value for `k` when using the PCA data?

  * **Answer:**  3


* **Question:** Does it differ from the best k value found using the original data?

  * **Answer:** Yes, 4 was the better for the original data.

## Visualize and Compare the Results

![Composite_Elbow](https://github.com/NoelleMtz/CryptoClustering/assets/123044294/36bd61cd-6411-4f19-8f89-4c3cd1235b95)
![Composite_Clusters](https://github.com/NoelleMtz/CryptoClustering/assets/123044294/e1ff509b-d0f5-40db-b85e-7a8b9f8cb8b9)

### Answer the following question: 

  * **Question:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** Reducing the features changed the inertia. So PCA had better results for clusters compared to the scaled data. By using the optimal value of 2 from the PCA, we saw more precise clustering. 

# References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

University of Arizona Data Analysis & Visualization Bootcamp (2023)

## Contributors
Noelle Martinez


