# 20-supervised-learning

Overview  
This repository demonstrates the use of a simple supervised learning model to evaluate the creditworthiness of potential borrowers. The dataset is comprised of historical lending activity from a peer-to-peer lending services company. The scikit-learn library was used to train and run a logistic regression model (binary classifier) on this data.  Data was separated into labels (loan_status) and features and loan applications were either approved or denied.

Model Evaluation  
The binary classifier model performed near-perfectly with 99% accuracy, 100% precision, and 100% recall (sensitivity / true positive rate). These scores from the classification report reflect the very minimal number of type I and type II errors shown in the confusion matrix.

Accuracy is an overall metric for the performance of the model, being the proportion of correct predictions (positive and negative) out of the total predictions made.
Both precision and recall/sensitivity are measures of the model's accuracy in classifying positives. 
Precision is the proportion of true positive predictions out of all positive predictions made by the model (includes Type I errors / false positives).
Recall is the proportion of true positive predictions out of all actual positive instances in the dataset (includes Type II errors / false negatives).

Recommendation  
As the model is near-perfect across the board in all measures, it is validated and recommended for use. 
