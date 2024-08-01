---
layout: post
title: Week 8
---

This week, I experimented with a couple of different models in order to better classify the entries in the dataset I started working with last week, hopefully reducing overfit.
I started by simplifying the linear model I had been working with, in hopes that fewer parameters would result in less overfit. The updated model did have less overfit, but it was also somewhat inaccurate. 
I also tried a support vector machine (SVM) and a random forest model. The SVM classified everything outside of the training set as personal,
and the random forest misclassified the academic test data in all three trials. Neither of these models seemed more viable than the linear regression model due to this apparant bias towards personal anxiety.
In addition to these models that were implemented using SciKit Learn, I created my own rule-based system to attempt to classify the data based on domain knowledge, without being affected by the small sample size.
This rule-based model seems to be accurate, as it correctly classified all but one of the known data (which was a larger test set than the others, because none of the data had to be used for training), and most of its classifications for the unknown data are consistent with my initial predictions.
As such, I will be moving forward with the rule-based model, as it is more accurate and consistent than the other models.
