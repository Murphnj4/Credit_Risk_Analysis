# Credit_Risk_Analysis
## Overview. The purpose of this analysis is to gauge the effectiveness of multiple data sampling methods and the accuracy scores they produce in predicting credit risk.
Below is a chart of all results and scores.
Method	/Accuracy Score/	Precision Score/	Recall Score
			
Random Oversampling	64.56%	68.20%	99.71%
			
Smote Oversampling	62.34%	63.77%	99.69%
			
Undersampling	52.94%	44.96%	99.56%
			
Combo Over&under Sampling	62.34%	63.77%	99.69%
			
Balanced Random Forest	76.64%	87.94%	99.77%
			
Easy Ensemble AdaBoost	93.17%	94.25%	99.95%

The Easy Ensemble method had the best balanced accuracy score at over 93%. The other methods were less accurate but the two ensemble methods had better overall results.
The results of the precision score were best for the ensemble methods with a score of 94.25%. This means that of all the positive results predicted 94.25% were actually positive.
The results for the recall score were all over 99% under all methods. This means that of all the total positives over 99% were predicted. 
### Summary. Based on these results we can see that the ensemble method produced the best results acrosss the board and could be used in production.

