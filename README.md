# AI-BASED-RECOMMENDATION-SYSTEM

COMPANY NAME:CodeTech IT solutions 
NAME:V.Nivetha  INTERN ID:CT04DG2828
DOMAIN:Java Programming  DURATION:4 Weeks  MENTOR: Neela Santhosh 

Description:

This Java application demonstrates how to build a simple product recommendation system using Apache Mahout, a powerful machine learning library. It implements user-based collaborative filtering to suggest items (products or content) to users based on their past preferences and those of similar users.

The system reads a dataset of user ratings from a CSV file, computes user similarity using the Pearson correlation coefficient, and then recommends top items to a target user.

Key Features:
Collaborative Filtering based recommendation engine
Uses Apache Mahout 0.9 for recommendation logic
CSV-based input data format (userID,itemID,preference)
Supports customizable:
Number of recommendations
Neighborhood size (how many similar users to consider)

Technologies & Libraries:
Java
Apache Mahout (0.9) – for recommendation and similarity calculations

Files Included:
ProductRecommender.java:
Main class that reads data, calculates similarity, builds the recommender, and outputs recommendations.
data.csv:
Sample dataset containing user IDs, item IDs, and their preference scores.

Concepts Demonstrated:
User-based Collaborative Filtering
Pearson Correlation Similarity
Mahout’s Recommender API
File-based data modeling using FileDataModel

How It Works:
1. Reads the user-item-rating data from a CSV file.
2. Calculates similarity between users based on their ratings.
3. Identifies nearest neighbors (similar users).



