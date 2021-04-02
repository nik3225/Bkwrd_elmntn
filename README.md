# Bkwrd_elmntn
Backward Elimination for Feature selection
1. We have done backward elimination to select which subset of the features would be the best to derive a model.
2. Significance level plays a major role as we compare it with the p-values of individual feature.
3. If the p-value of multiple features is greater than the significance level then we drop the one with the highest value and redo the process.
4. In the end we create the model with the features that have p-value less than the Significant level.
