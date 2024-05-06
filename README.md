# assignment08
Assignment 8 for Intro to Data Science Course at McCourt, GU
Asad & Priscilla

In Question 1, we analyze the votes from Session 103 of US Senate (1993) through principal component analysis. We then make two graphs
based on the two principal components and color coding them by parties and regions respectively.

In Question 2, we make a custom function that takes a data of votes and the number of clusters we wants to make and outputs a graph of
principal components colored by the clusters. 

In Exercise 3, we delve into text analysis of executive orders. Beginning with data preparation, we 
generate bigrams from the text and exclude common stop words, which lack substantial meaning in our 
analysis. Then, we count and filter the bigrams based on their frequency, visualizing their relationships. 
Next, we calculate TF-IDF to measure word importance in relation to each president. Finally, we select 
and visualize the top 15 bigrams with the highest TF-IDF values for each president, revealing 
distinctive word pairs in their executive orders.

In exercise 4, we start by preprocessing the Senate bills data, dividing it into training and 
testing sets. We then create a text processing recipe that involves tokenization, stop word removal,
stemming, and TF-IDF transformation. This recipe is customized with a specific list of stopwords
tailored to the domain. We proceed to build a logistic regression model for classifying bill
passage based on their descriptions, incorporating the processed data. After fitting the model
to the training data, we evaluate its performance using the testing set, calculating metrics
such as accuracy, precision, recall, and generating a ROC curve for visualization.