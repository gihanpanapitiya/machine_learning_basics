
When you try to understand the meanings of True Positive, True Negative, False Positive and False Negative, start thinking in terms of the predicted class.

For example, in the term 'False Positive', Positive is with respect to the predicted class.  False Positives are those predicted as Postives, but their ground truth is Negative. Similarly, False Negatives are those that were predicted as Negatives, but they actulally belong to the Positive Class.




True Positives = Predicted as Positves, Actually Possitive
False Positives = Predicted as Positives, Actuallt Negatives

True Negatives = Predicted as Negatives, Actually Negatives
False Negatives = Predicted as Negatives, Actually Positives


Precision = True Positives/(True Positives + False Positives)
This metric is important when the we are concerned about False Positives. Which are predicted positives, but they are actually negatives.

Recall = True Positves/(True Positives + False Negatives)
This metric is important when the we are concerned about False Negatives.
