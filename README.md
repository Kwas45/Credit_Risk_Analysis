# Credit Risk Analysis Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. The purpose of the project is to use the credit card credit dataset from LendingClub, a peer-to-peer lending services company to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm.

__This project consists of three technical analysis:__
> Use Resampling Models to Predict Credit Risk.

> Use the SMOTEENN Algorithm to Predict Credit Risk.

> Use Ensemble Classifiers to Predict Credit Risk.

## Resource

[2019 Q1 Loan Stats](https://github.com/Kwas45/Credit_Risk_Analysis/blob/main/Resources/LoanStats_2019Q1.csv)


##  Credit Risk Analysis Results

#### 1. Naive Random Oversampling

![image](https://user-images.githubusercontent.com/102786356/183278902-db108d9d-3b2f-4a9b-b501-243da9ad3bf6.png)

* Per the image above the the balanced accuracy score is **65%**. The High Risk precision rate is **1%** with a recall of **68%** and F1 score of **2%**.
Low Risk has a precision rate of **100%** with a recall of **62%** and F1 score of **76%**

#### 2. SMOTE Oversampling

![image](https://user-images.githubusercontent.com/102786356/183279286-59761f10-f4fb-4f5c-ad88-1d00809ea855.png)

* Per the image above the the balanced accuracy score is **66%**. The High Risk precision rate is **1%** with a recall of **63%** and F1 score of **2%**.
Low Risk has a precision rate of **100%** with a recall of **68%** and F1 score of **81%**

#### 3. Undersampling

![image](https://user-images.githubusercontent.com/102786356/183279496-6e7d0139-43f1-42f3-80c9-f5663de59302.png)

* Per the image above the the balanced accuracy score is **54%**. The High Risk precision rate is **1%** with a recall of **69%** and F1 score of **1%**.
Low Risk has a precision rate of **100%** with a recall of **40%** and F1 score of **57%**

#### 4. Combination (Over and Under) Sampling

![image](https://user-images.githubusercontent.com/102786356/183279633-f713b93a-8912-4675-a06a-cb955880cb1d.png)

* Per the image above the the balanced accuracy score is **64%**. The High Risk precision rate is **1%** with a recall of **72%** and F1 score of **2%**.
Low Risk has a precision rate of **100%** with a recall of **57%** and F1 score of **72%**

#### 5. Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/102786356/183279884-1bdafe74-e363-4621-af46-750593df7f23.png)

* Per the image above the the balanced accuracy score is **91%**. The High Risk precision rate is **4%** with a recall of **67%** and F1 score of **7%**.
Low Risk has a precision rate of **100%** with a recall of **91%** and F1 score of **95%**


#### 6. Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/102786356/183279995-84b21baa-4473-403b-b564-c4d3090ad3bd.png)

* Per the image above the the balanced accuracy score is **93%**. The High Risk precision rate is **7%** with a recall of **91%** and F1 score of **14%**.
Low Risk has a precision rate of **100%** with a recall of **94%** and F1 score of **97%**

## Credit Risk Analysis Summary
Based on our results, the recommended model to use is the Easy Ensemble AdaBoost Classifier model. This is model is recommended due to its **93%** balanced accuracy score and **7%** predictability rate of High Risk loans. 
