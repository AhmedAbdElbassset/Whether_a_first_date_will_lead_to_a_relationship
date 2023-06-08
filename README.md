# Whether_a_first_date_will_lead_to_a_relationship

# Problem description
- building a machine learning model to predict the probability (0-1, float) output that the dating will match.
- inputs : (191 features) for both training set (5909 observations) and (9842 observations) after the oversampling and test set (2469 observations)
- output : 1 feature 2469 observations as output (Using Test Data).
# Model
classification and prediction
# Challenges
- that our dataset has a lot of null values
- that the is an imbalanced dataset a lot 0's and less of 1's
# Model impact
It help people to meet their suitable partners
# The ideal solution
Using a XGBClassifierr with random search to search for the best hyperparameters combinations to get better ROC-AUC result on the test data is (88.835%)
