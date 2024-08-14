---
layout: post
title: Week 9
---

This week, I analyzed the results of the rule-based model, refined it a bit based on the results and our domain knowledge, and analyzed the new results. This analysis had a particular focus on those results that didn't match our initial evaluation or predictions. 
All but four of the 39 data points were classified as expected, with one misclassification of an academic data point as personal and three instances of unsure data points being classified against our predictions.
The misclassification was apparantly caused by additional value being placed on certain factors because the respondant placed additional emphasis on them, which the cleaned data used for the rule-based model did not capture.
The other unpredicted results can be accounted for by the large number of personal factors listed, and most of them were close to the classification threshold, having similar scores for personal and academic anxiety.
All four of these unpredicted results were personal, predicted academic.
The updated rule-based model reduced the impact of each personal factor to account for this apparent bias, while increasing the impact of particular personal factors that may be underlying factors behind self-reported academic pressure based on our domain knowledge.
This updated model had very similar results to the original, with only one data point (predicted personal, originally classified as such, re-classified as academic) changing classification.
For this data point, the personal prediction likely came from more in-depth descriptions of personal factors that were cleaned out of the data before feeding it to the rule-based model.
As such, this model seems to be effective at data classification, albeit limited by the lack of intricacy in the data and inability to handle such complexities.
