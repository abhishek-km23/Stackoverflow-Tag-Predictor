# Stackoverflow-Tag-Predictor
Suggest the tags based on the content that was there in the question posted in Stackoverflow.

It is a multilable classification problem. 
Multilable Classification: Multilabel classification assigns to each sample a set of target labels. This can be thought as predicting properties of a data-point that are not mutually exclusive, such as topics that are relevant for a document. A text might be about any of religion, politics, finance or education at the same time or none of these. 

Performance metric 
Micro-Averaged F1-Score (Mean F Score) : The F1 score can be interpreted as a weighted average of the precision and recall, where an F1 score reaches its best value at 1 and worst score at 0. The relative contribution of precision and recall to the F1 score are equal. The formula for the F1 score is:


F1 = 2 * (precision * recall) / (precision + recall)


In the multi-class and multi-label case, this is the weighted average of the F1 score of each class. 


'micro f1 score': 
Calculate metrics globally by counting the total true positives, false negatives and false positives. 


'macro f1 score':
Calculate metrics for each label, and find their unweighted mean. This does not take label imbalance into account. 


NB: This project was done as a part of assignment for machine Learning course taken at appliedaicourse.com/
