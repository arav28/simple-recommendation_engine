# simple-recommendation_engine
Comprehensive Guide to build a Recommendation Engine from scratch-Analytics vidhya

ITEM-ITEM collaborative filtering look for items that are similar to the articles that user has already rated and recommend most similar articles. 
But what does that mean when we say item-item similarity? 
In this case we don’t mean whether two items are the same by attribute like Fountain pen and pilot pen are similar because both are pen. 
Instead, what similarity means is how people treat two items the same in terms of like and dislike.

Advantages of Item-Item collabarative filtering
1. 1)Data Sparsity: In case of large number of items, number of items a user has rated reduces to a tiny percentage making the correlation coefficient less reliable
2. User profiles change quickly and the entire system model had to be recomputed which is both time and computationally expensive
