# Marketing-Analysis
This repository contains some practice cases about Marketing Analysis using: 
1. Market Basket Analysis-Algorithma Apriori
2. Collaborative Filtering
3. Content_Based Filtering
4. Hybrid Filtering
5. A/B Testing

In this repository contains code and dataset.

Code Market Basket Analysis-Algorithma Apriori can only be dirun in the command prompt while the other can be run on a jupyter notebook.

The dataset used here is a private dataset which is a dataset of class activities in Boothcamp except for A/B testing used data from Kaggle which is already described in the code.

------------------------------------------------------------------------------------------------------------------------------------------
# 1. Market Basket Analysis-Algorithma Apriori
In this case I use the source code from: https://github.com/coorty/apriori-agorithm-python. 

Where will later be run at the command prompt. Input to run the code and minimum support value, minimum confidence value, and the item you want to research.
The dataset used is the survey dataset of the goods to be purchased by Boothcamp friends with a maximum number of 3 items.

# Usage Example
To run the program with dataset provided (in ./data/) and mininum support = 0.12, mininum confidence = 0.5 and return rules for Bread:
python test_apriori_command_line.py -f ./data/transaction.csv -s 0.20 -c 0.50 -r Camera.

-----------------------------------------------------------------------------------------------------------------------------------------
# 2. Collaborative Filtering
Collaborative filtering is one of the market analysis techniques where we recommend the product to users. The main objective is to give a recommendation to the user who will choose or buy a specific product based on the rating given by another user. The simple concept is the assumption that someone who likes a certain product, the product will also be liked by others. 

In this case, I use the dataset that I and my friends have collected by giving a rating (1-5) on the movie that we've watched. 

Output of Collaborative Filtering is Recomendations Film to user.

-------------------------------------------------------------------------------------------------------------------------------------------
# 3. Content_Based Filtering
Content-based filtering, also referred to as cognitive filtering, recommends items based on a comparison between similarity content of the items.

In this case I used a dataset of movies that I have used in collaborative filtering. In this Case these films are viewed by their characteristics based on type (Indonesia or Hollywood), Genre, IMDB Rate, and duration. The Output of content based filtering is films that have similarities to the film.

Output of Content_Based Filtering is Film that has Similarity.

-------------------------------------------------------------------------------------------------------------------------------------------
# 4. Hybrid Filtering

Hybrid filtering technique is a combination of multiple recommendation techniques like, merging collaborative filtering (CF) with content-based filtering (CB) or vice-versa. Hybrid Filtering get two technique:
Content-based → collaborative We can use content-based prediction at users with many training examples and collaboration at others. The prediction of content-based models can be used in recursive collaborative filtering.

Output of Hybrid Filtering is Recomendations Film for User

--------------------------------------------------------------------------------------------------------------------------------------------
# 5. A/B Testing
A/B testing (also known as split testing or bucket testing) is a method of comparing two versions of a webpage or app against each other to determine which one performs better. AB testing is essentially an experiment where two or more variants of a page are shown to users at random, and statistical analysis is used to determine which variation performs better for a given conversion goal.

In this practice case I used the dataset that I found in kaggle below : https://www.kaggle.com/yufengsui/mobile-games-ab-testing. And using Z test to measure hypothesis of it.

----------------------------------------------------------------------------------------------------------------------------------------------
Hopefully helpful


