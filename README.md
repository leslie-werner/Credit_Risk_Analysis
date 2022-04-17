# Credit_Risk_Analysis

## Overview
<!-- Overview of the loan prediction risk analysis: The purpose of this analysis is well defined (4 pt) -->
The purpose of this analysis was to use imbalanced-learn and scikit-learn libraries to determine which model will be best to predict credit card risk. Oversampling was done using RandomOverSampler and SMOTE algorithms. BalancedRandomForestClassifier and EasyEnsembleClassifier was used to reduce bias and predict credit risk. Once the analysis is complete, we will recommened which model should be used.

## Results: Machine Learning Models
<!-- There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt) -->

* Oversampling Results:
   - The balance accuracy score was 0.6456130066757718, or 65%.
   - The average precision was 99%, recall of 68%

<img width="856" alt="oversam" src="https://user-images.githubusercontent.com/65638310/163723030-9a55429d-729c-4644-ad58-f17908c82d81.png">


* SMOTE Results
    - The balance accuracy score was 0.6234433606890912, or 62%
    - The average precision was 99%, and recall of 64%

<img width="748" alt="SMOTE" src="https://user-images.githubusercontent.com/65638310/163724076-b17d268c-38f0-4f14-8d73-f9273bc10acc.png">

* Undersampling Results
    - The balance accuracy score was 0.5225775650555374, or 52%
    - The average precision was 99%, and recall of 43%
     
<img width="829" alt="undersa" src="https://user-images.githubusercontent.com/65638310/163724089-9bc42806-c8b5-4baf-98e2-1502b63341b2.png">


* Combination of Over and Undersampling Results
     - The balance accuracy score was 0.6531287896185101, or 65%
     - The average precision was 99%, and recall of 62%

<img width="727" alt="combo" src="https://user-images.githubusercontent.com/65638310/163724096-d22d130b-0fd1-4ced-8c31-1205843c402b.png">

* BalancedRandomForestClassifier Results
     - The balance accuracy score was 0.7877672625306695, or 79%
     - The average precision was 99%, and recall of 91%
 
    
<img width="828" alt="BalaF" src="https://user-images.githubusercontent.com/65638310/163724112-4128c9c3-8f02-410c-bdc6-eb0123c681be.png">


* EasyEnsembleClassifier Results
    - The balance accuracy score was 0.925427358175101, or 93%
    - The average precision was 99%, and recall of 94%

<img width="854" alt="easyec" src="https://user-images.githubusercontent.com/65638310/163723171-cf5d0b92-c7e3-4d6a-9df0-8000af887a70.png">



## Summary
<!--There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt) -->

After looking at all of the data above, we can conclude that the best prediction model for credit card risk is EasyEnsembleClassifier. The EasyEnsebleClassifier has the highest rate of precision and accuracy.  
