# Credit_Risk_Analysis
A machine learning analysis of credit risk using multiple different models (oversampling, under sampling, combination, and reduction of bias)

# Overview
The purpose of the project is to create models using machine learning that could possibly be used to predict credit risk. The following procedures will be tested
* SMOTE and RandomOverSampler, which would both oversample the data.
* ClusterCentroids, which would undersample the data.
* A combination approach of over and under sampling using an alogrithm known as the SMOTEENN.
* Finally, machine learning models that reduces bias known as BalancedRandomForestClasssifier and EasyEnsembleClassifier. 

# Results
# RandomOverSampler
<img width="1104" alt="Screen Shot 2022-07-16 at 4 00 50 AM" src="https://user-images.githubusercontent.com/102098068/179348272-1dd817ae-c651-4f91-8525-f0d78951b4b3.png">

The balanced accuracy score appears to be 64.56%. High risk precision is about 1% with 61% sensitivity, making a F1 score of 2%.
Since there is a large number in the low risk population, precision is approximately 100% with a sensitivity of 68%.

# SMOTE Model
<img width="1079" alt="Screen Shot 2022-07-16 at 4 14 06 AM" src="https://user-images.githubusercontent.com/102098068/179348686-f784bcf1-ec1b-4046-b818-b00b39329276.png">
Results appear somewhat different from previous model. Balanced accuracy rate is 62.34%. High risk precision is 1% with 61% sensitivity, making a F1 of 2%. High number of the low risk population once again shows a precision level of 100% and a sensitivity of 64%.

# ClusterCentroids Model
<img width="1091" alt="Screen Shot 2022-07-16 at 4 18 07 AM" src="https://user-images.githubusercontent.com/102098068/179348849-5b7c72df-fffb-46e7-9250-1c3ff8f851a7.png">
Balanced accuracy score is roughly 51%. High risk precision is approx 1% with 57% precision, creating an F1 of 1%. Low risk sensitivity is at 45%. 

# SMOTEENN Model
<img width="1095" alt="Screen Shot 2022-07-16 at 4 24 31 AM" src="https://user-images.githubusercontent.com/102098068/179349063-22148d84-b671-403a-b89e-f1fa3ad4e5a3.png">
Balanced accuracy score is approximately 61.57% High risk prevcision is at 1% with 69% sensitivity, creating a F1 of 2%. Low risk sesntivity is 54%.

# BalancedRandomForestClassifier Model
<img width="1080" alt="Screen Shot 2022-07-16 at 4 28 10 AM" src="https://user-images.githubusercontent.com/102098068/179349142-72640775-d318-495b-a426-199002e7ec4a.png">
With the next deliverable, the BalancedRandomForestClassifier has an increased accuracy score of approximately 79%. High risk precision remains low at 4% and a 67% sensitivity, creating a F1 value of 7%. Low risk sensitivity is now at 91% with approximately 100% precision.

# EasyEnsemble Classifier Model
<img width="1089" alt="Screen Shot 2022-07-16 at 4 34 12 AM" src="https://user-images.githubusercontent.com/102098068/179349337-f6e1d771-fd8a-40e9-a9b0-b9a697ee31b7.png">
This model shows a high balanced accuracy score of 92.5%. High risk precision is still low at 7% with 91% sensitivity, creating a F1 of 14%. A lower number of false positivies shows the low risk sensitivity is 95$ with 100% precision.

# Summary
All of the models that were showcased in this exercise shows that machine learning was unable to determine with a high precision the risk of an individual on the basis of credit. The ensemble models did perform considerably better than the resampling models, especially with the high risk results. Easy Ensemble showed the best amount of high risk credit, but with a low precision, so there is still individuals who would be penalized and negatively affect the bank's strategy on revenue with missing opportunities. With the results of this exercise, no machine learning model would prove wise to be used for credit risk. 



