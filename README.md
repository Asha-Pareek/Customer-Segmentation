# Customer-Segmentation
Analytics Vidhya

Private leaderboard score: 0.93215 using XGBoost and 0.93088 using KNN

# Problem Statement
An automobile company has plans to enter new markets with their existing products (P1, P2, P3, P4 and P5). After intensive market research, they’ve deduced that the behavior of new market is similar to their existing market.
In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for different segment of customers. This strategy has work exceptionally well for them. They plan to use the same strategy on new markets and have identified 2627 new potential customers.
You are required to help the manager to predict the right group of the new customers.

The evaluation metric for this hackathon is Accuracy Score.

# Approach
1.	There are 2627 rows in test, out of which 2332 are already available in train data.
2.	Need to predict only for 295 rows (11%)
3.	Used XGBoost or KNN for predicting lables for these 295 observations.
