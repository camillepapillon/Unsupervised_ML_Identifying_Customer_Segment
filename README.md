# Unsupervised Machine Learning Project to Identify Customers Segments

Goal : Apply unsupervised Learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. 

Why ?  These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of return  


This project was done as part of the Udacity Nanodegree : Introduction to Machine Learning with Tensorflow Nanodegree during the final model on Unsupervised Learning. 

Those are the steps that were done to realise this project: 
### 1. Load the Dataset (general population)
### 2. Preprocessing 




      2.1 Assess Missing Data
      2.2 Select and Re-encode Features
      2.3 Create a Cleaning Function

### 3. Feature Transformation 




     3.1 Apply Feature Scaling
     3.2 Perform Dimensionality Reduction
     3.3 Interpret Principal Components

### 4. Clustering



    4.1 Apply clustering to General Population
    4.2 Apply All Steps to the Customer Data 
    4.3 Compare Customer Data to Demographics Data  


### 5. Apply clustering to the customer dataset 


## Key Findings and Insights 

      -> Dropped 6 columns with more than 20% missing data
      -> Re-encoded binary features and dropped the 14 multilevel features
      -> Transformed missing values in rows with Imputer function => average missing values on all rows = 1,37 %
      -> Applied feature scaling with StandardScaler() on general population dataset
      -> Performed dimensionality reduction (PCA) and kept 30 principal components
      -> Applied Kmeans clustering to general population dataset and kept 14 clusters 




