# Finding donors for CharityML

In this project, I employ three supervised algorithms (Support Vector Machines, K-Nearest Neighbors and Random Forest) to accurately model individuals' income using data collected from the 1994 U.S. Census. From preliminary results, the best candidate algorithm is Random Forest. I further optimize this algorithm to best model the data. 

My goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations.  Properly evaluating an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with.  While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will see) infer this value from other publicly available features. 

The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The dataset was donated by Ron Kohavi and Barry Becker, after being published in the article _"Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid"_. You can find the article by Ron Kohavi [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf). The data I investigate here consists of small changes to the original dataset.

This project is part of the [Udacity Machine Learning Engineer Nanodegree](https://www.udacity.com).
