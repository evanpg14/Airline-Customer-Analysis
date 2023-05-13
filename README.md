# Airline-Customer-Analysis
This project is about clustering using K-Means and supervised machine learning (classification) model.

## Objectives
Given the context, the main aim of this experiment is to perform customer value analysis by clustering customers using the LRFMC indicators, which is an extended version of the commonly used RFM indicators. After clustering, this experiment also do multi-class classification model. The experiment utilizes customer information and airline flight records collected in 2014 and has the following objectives:

1. Perform customer segmentation (clustering) using K-Means algorithm with LRFMC indicators derived from the dataset.
2. Perform classification model using Decision Tree, Random Forest, and SVM.
3. Analyze the characteristics of each cluster obtained from segmentation.
4. Offer business insights related to the analysis results.

## Steps

1. Data Collection
2. Data Cleaning
3. Data Pre-processing
4. Clustering
5. Classification

## Clustering Result

1. **Cluster 0**  (champion) = This cluster use our service recently (averaging 1.5 months ago), the most frequent to fly, with the discount usage is average compare to others and has been a member for about 60 months or 5 years ago

2. **Cluster 1** (promising) = This cluster's recently use our service (around 4 months ago), pretty frequent to fly, and doesn't use lots of discount, the newest member (since 2.3 years ago) 

3. **Cluster 2** (loyal customer) = This cluster is average on recency of 4.5 months, pretty frequent using our service, and also average usage of dicsount, and the longest member (almost 7 years as a member)

4. **Cluster 3** (price sensitive) = This is also average on recency averaging 4.5 months, frequently use our service, use lots of discount, and has joined as a member for about 4.5 years ago (pretty long)

5. **Cluster 4** (hibernating) = This cluster last seen used our service 16 months ago (the worst among others), the lowest frequency, average usage of discount, and has been a member since 3 years ago (long enough)

![image](https://github.com/evanpg14/Airline-Customer-Analysis/assets/111892017/7217887f-08ba-4d16-8c9a-ab62f013f971)

And this is the distribution of the clusters

![image](https://github.com/evanpg14/Airline-Customer-Analysis/assets/111892017/6d8e1ee3-9e77-480c-858b-391d16774ac1)

## Classification Result 

Random Forest is the best model to predict airline-customer-analysis case with Precission, Recall, F1, and Accuracy above 90%

![image](https://github.com/evanpg14/Airline-Customer-Analysis/assets/111892017/8d9ae439-0a31-4a83-91c4-ee7340c211c4)
