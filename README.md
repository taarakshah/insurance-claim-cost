# insurance-claim-cost
Individual effort from class project relating to insurance claim costs for 2020 Travelers Modeling Competition.

https://www.kaggle.com/c/2020-travelers-modeling-competition

In this report, we will address the methods used in predicting claim cost for the InsNova Auto Insurance Company. We are given various predictors to predict this and other supplemental information. Of the provided variables, claim_cost, claim_ind, and claim_count are only provided in the training dataset, so we can only use them in constructing the response variable, not for prediction of the claim cost. In this report, we address which of the variables above proved to be useful across different methods in predicting the claim cost. We will address the best methods for predicting claim cost and the benefits and drawbacks of each method considered.

Methods: gradient boosted regression, linear regression, two-step modeling, Tweedie GLM, bootstrapping
