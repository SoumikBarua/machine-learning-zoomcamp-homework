I just completed Module 4: Evaluation Metrics for Classification from ML Zoomcamp 2025 :tada:
Using converted prediction project, this module covered:
:small_orange_diamond: Data Preparation & data validation framework
:small_orange_diamond: Accuracy tells us about the fraction of the correct predictions
:small_orange_diamond: Different threshold quanity can affect the accuracy
:small_orange_diamond: Usually, logistic regression tries to optimize for 0.50 to be the best threshold
:small_orange_diamond: Accuracy doesn't tell us how good the model is
:small_orange_diamond: Confusion table is a way of looking at how our models make different errors and correct decisions. The decisions can be categorized into four groups: 1) true negative, 2) false negative, 3) false positive, and lastly 4) true positive.
:small_orange_diamond: For true negative, g(xi) < t and y = 0. For false negative, g(xi) < t but y = 1. For false positive, g(xi) >= t and y = 0. And finally, true positive is g(xi) >= t and y = 1.
:small_orange_diamond: The numbers from these four categories gives us a better picture of the accuracy. Accuracy is equal to the (true positives + true negatives) / (true positives + true negatives + false positives + false negatives)
:small_orange_diamond: Precision tells us what percentage of positive predictions are correct. Mathematically, precision = true positives / (true positives + false positives)
:small_orange_diamond: Recall tells us out of all positives, what percentage was correctly predicted. Mathematically recall = true positives / (true positives + false negatives)
:small_orange_diamond: Together, precision & recall paints a good picture of how reliable our accuracy is.
:small_orange_diamond: ROC Curve stands for receiver operating characteristics curve. This describes the performance of a binary classification model.
:small_orange_diamond: FPR is false positive rate. FPR = FP / (TN + FP)
:small_orange_diamond: TPR is true positive rate. TPR = TP / (FN + TP)
:small_orange_diamond: TPR is the same as recall!
:small_orange_diamond: We want False Positive Rate or FPR to be as low as possible while wanting the True Positive Rate or TPR as high as possible.