# Starbucks Project

<p align="center" width="100%">
    <img width="60%" src="https://vamers-com.exactdn.com/wp-content/uploads/2016/04/VAMERS-FYI-LIFESTYLE-Ordering-at-Starbucks-A-Guide-to-Starbucks-Lingo-Main-Banner.png"> 
</p>

As a final task in Udacity Data Science Nanodegree, I chose to perform analysis and modelling using simulated Starbucks data. 

## Introduction
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

In this project, my goal was to predict whether an offer sent to a customer will be successful or not (i.e. will it be used/actioned upon or not).


## Technologies
* Python 3.7.2

Libraries used: 
* pandas
* numpy
* math
* json
* matplotlib
* datetime
* seaborn
* sklearn
* itertools
* time

## Files
The data is contained in three files:

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)

profile.json - demographic data for each customer

transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Summary of the results
In this project, I tried to predict whether an offer sent to a user would be successful or not (i.e. will it be used/actioned upon or not). Models that I used were Logistic Regression, Decision Tree, Random Forest, k-Nearest Neighbors. 
As it turns out, all models were quite close in observed metrics. Decision Tree and k-Nearest Neighbors are best performers. Logistic regression has even slightly higher precision than the winner, so in this case not one single model is (far) superior to all others.

Article with a more detailed discussion can be found [here](https://medium.com/@josip.vuger/starbucks-capstone-challenge-508e9a90caad).

<p align="center" width="100%">
    <img width="33%" src="https://i.pinimg.com/originals/88/0b/b6/880bb6b520c42b194d47cd175ed48fab.jpg"> 
</p>

## Acknowledgements
Data provided by [Udacity](https://udacity.com).

https://towardsdatascience.com/dealing-with-list-values-in-pandas-dataframes-a177e534f173

https://matplotlib.org/stable/tutorials/introductory/lifecycle.html#sphx-glr-tutorials-introductory-lifecycle-py

https://medium.com/swlh/how-to-code-and-evaluate-of-decision-trees-2d94093b3c1a

https://machinelearningmastery.com/hyperparameters-for-classification-machine-learning-algorithms/

https://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/
