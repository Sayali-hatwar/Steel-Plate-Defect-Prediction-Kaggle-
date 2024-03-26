# Steel-Plate-Defect-Prediction-Kaggle-
Predict the probability of various defects on steel plates
train.csv - the training dataset; there are 7 binary targets: Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, Other_Faults
test.csv - the test dataset; your objective is to predict the probability of each of the 7 binary targets
sample_submission.csv - a sample submission file in the correct format.

Submissions are evaluated using area under the ROC curve using the predicted probabilities and the ground truth targets.
To calculate the final score, AUC is calculated for each of the 7 defect categories and then averaged. In other words, the score is the average of the individual AUC of each predicted column.
For each id in the test set, predicted the probability for each of 7 defect categories: Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, Other_Faults.
