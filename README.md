# Coffee Bean Recommender

## Executive Summary
This project is to provide an solution to coffee enthusiasts that buy specialty coffee bean fresh from local roasters. As this hobby is gaining popularity, there is also an increase in coffee roasters locally. This recommender system will aim to propose coffee bean based on certain features: Tasting notes, taste ranking scores and origin of coffee bean.

Using dataset from [Kaggle](https://www.kaggle.com/datasets/hanifalirsyad/coffee-scrap-coffeereview)

This dataset is use to help set the base feature for this recommender. Thereafter, any new locally scrap data can be build upon this. The systems uses conten-based filtering using similarity score for tasing notes, nearest neighbour for taste ranking score and matching string value to country origin.

## EDA
![alt text](//image.jpg)


## How it works
The recommender system uses content-based filtering to recommend coffee beans to users. Content-based filtering is a technique that recommends items similar to the ones that a user has liked in the past.

The system first asks the user a few questions about their taste preferences for coffee beans. It then recommends coffee beans based on their taste profile and other characteristics such as roast level, origin, and processing method.
