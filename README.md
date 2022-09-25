# Market-Basket-Analysis
In conclusion for categorical output data:
• When we deal with datasets which have around 30,000 transactions, Apriori is a tried and tested method whose implementation is straight forward. 
• When we deal with slightly bigger datasets fast apriori algorithm is preferred. This algorithm simply pivots the table decreasing the number of scans required for the algorithm to calculate 
support for each item. 
• When we deal with large datasets where the number of transactions is in the terms of millions Super fast apriori algorithm is the best algorithm. This is not an algorithm which is inbuilt into python. 
All these observations have been made in the assumption that the data is a transactional dataset with categorical output. If the application has huge amounts of data which is 
categorical in nature, then Super fast apriori is the best but we must write the code on our own which will raise different problems such as optimization and debugging. 
The apriori algorithm which we have used is already optimized by machine learning engineers and peer reviewed by coders all over the world.

DATASET LINK:-
https://www.kaggle.com/competitions/instacart-market-basket-analysis/data
