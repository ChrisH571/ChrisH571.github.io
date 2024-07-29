---
layout: post
title: Week 7
---

This week, I applied the machine learning concepts I had practiced with in previous weeks to attempt to classify the cause of anxiety in international graduate and PhD students as either personal or academic based on a small dataset of survey results.
Due to the small size of the dataset, some overfit was expected when applying the same techniques used in previous weeks.
After cleaning the data and classifying each student as having (definitively) more personal or academic anxiety, or as ambiguous, I ran two linear regression models over the dataset, using different training sets for both. 
Both models were ably to perfectly fit the training data, but gave vastly different results for many of the unknown data points we were trying to classify. 
As such, we concluded that the models suffered from overfit and that other methods would have to be explored to apply domain knowledge to a model.
