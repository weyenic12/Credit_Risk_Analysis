## Overview of the Analysis
- We used a credit card dataset from LendingClub to run six different machine learning models and algorithms to predict credit risk and figure out whether the performance of the machine learning models is good or bad.
--------------------------
## Results
BalancedRandomForest:

![balancedrandomforest](https://user-images.githubusercontent.com/80421977/125850694-a3598c7d-a4c0-4542-a3b2-2c7465287d31.PNG)

Combination:

![combination](https://user-images.githubusercontent.com/80421977/125850712-70012c9e-b9cb-4704-a40a-6fd311806023.PNG)

Easy Ensemble:

![easyensemble](https://user-images.githubusercontent.com/80421977/126087920-49589826-c4f6-4593-8eca-ad6ba1ff71e3.PNG)

Oversample:

![oversample](https://user-images.githubusercontent.com/80421977/125850731-8a5236b8-34fe-4dbe-93ad-b7e44c89a36b.PNG)

SMOTE:

![smote](https://user-images.githubusercontent.com/80421977/125850733-67d2e4c3-9cce-4379-ab17-16b89a23e030.PNG)

Undersample:

![undersample](https://user-images.githubusercontent.com/80421977/125850742-79478179-30eb-4395-91bc-56b009899e19.PNG)


--------------------------
## Summary
- The 'geo' column represents the balanced accuaracy score for that specific model. The 'pre' column represents precision and the 'rec' represents the recall of the model. After looking at the results of the six above, the best machine learning algorithm to go with would be the Easy Ensemble algorithm because it has the highest accuracy score of 0.92 and has the highest recall of 0.94. Since, we are trying to find and flag fraudulent applications, the higher recall means it will flag more of the fraudulent applications. However, many of them will be false positives which is a negative, but it is the best of the six models.

