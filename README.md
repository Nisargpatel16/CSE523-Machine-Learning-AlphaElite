# CSE523-Machine-Learning-AlphaElite

## Product Recommendation System


## Table content

- [Introduction](#heading)
 

   
- Content
- Introduction
- Dataset
- Functionality
- Technology Stack/Algorithms
- Libraries
- Contributors


## Algorithm
- Clustering
- Cosine Similarity
- Jaccard Similarity
- K-means
- Term Frequency and Inverse Document Frequency (tf-idf)
- Single Value Decompostion


## Introduction
Recommendation systems enable users to access products that they may not be aware of. The two traditional recommendation techniques are content-based and collaborative filtering. While both methods have their own advantages, they also have certain disadvantages, some of which can be solved by combining both techniques to improve the quality of the recommendation. Broadly speaking, a recommendation system provides specific suggestions about items (products or actions) within a given domain, which may  interest the given active user.

Product recommendation is generally a filtering system which seeks to predict, display and suggest the product to users that they would like to purchase. This type of system is utilized in a variety of fields such as news, research articles and many more.

Here we have designed a product recommendation system which can provide appropriate suggestions to the customers while buying another products. We are designing the system such that it suggests the item based on the ratings of all the other items and also according to their purchase history.It helps the users to make a right choice and also it makes the content more personalised.

## Dataset 
 http://snap.stanford.edu/data/web-Amazon-links.html

## Functionality

- We are recommending the products based on the ratings of the products given by the other customers or users in past using cosine similarity as well as jaccard similarity.
- When a new user comes to buy a product and enters a keyword to search, we are recommending the products using k-mean text clustering based on the keyword .
- We are performing clustering based on the product ID and ratings given to that particular product.
- We have performed k-means clustering from scratch without the use of inbuilt functions.


## Technology Stack/Algorithms

- Jaccards similarity
- kmeans
- Cosine similarity

## Libraries
- Pandas
- Kmeans
- MinMaxScaler
- pyplot
- numpy
- TfidfVectorizer and CountVectorizer
- Adjusted_rand_score
- NearestNeighbors 
- sparse

## Features / Screenshots

# Elbow Method for optimal value of K
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/TextBasedCLustering_OnProductDescription/2.PNG" width="500" height="500">

# K means from scratch
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/TextBasedCLustering_OnProductDescription/scratch.JPG" width="500" height="500">

# Clusters defined based on a rating given by users
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/CLustering_ProductID_Ratings/1.PNG" width="650" height="400">

# Jaccard similarity
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/Similarity/jaccard.png" width="500" height="300">

# Cosine similarity
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/Similarity/cosine.png" width="400" height="300">

# Clusters 
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/TextBasedCLustering_OnProductDescription/3.PNG" width="200" height="400">

# Cluster's output 
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/TextBasedCLustering_OnProductDescription/4.PNG" width="300" height="200">

# Combined system Cosine similarity + Jaccard similarity 
<img src="https://github.com/Nisargpatel16/CSE523-Machine-Learning-AlphaElite/blob/main/Results/Similarity/average.JPG" width="400" height="200">



## Contributors

| [Nisarg Patel](https://github.com/Nisargpatel16)                                                                                                            
| [Shivam Lakhtariya](https://github.com/shivamlakhtariya)     
| [Vismay Patel](https://github.com/Vismay1710)
