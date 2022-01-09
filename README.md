# Credit_Risk_Analysis  
## Analysis Overview  
The purpose of the analysis is to use different machine learning methods to find the best algorythm to use for predicting credit risk  
* Results  
1. The first method is the naive oversampling method Balanced accuracy score for this method is 65.15% with a precision of .99 and a recall of .68  
![Naive BAS](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Naive%20Oversampling%20BAS.png?raw=true)  ![Naive Confusion Matrix](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Naive%20Oversampling.png?raw=true)  
2. the 2nd method is the SMOTE Oversampling method with a balanced accuracy score of .624 and a precision of .99 and a recall of .66  
![Smote BAS](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Smote%20Oversampling%20BAS.png?raw=true)  ![Smote Confusion Matrix](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Smote%20Oversampling.png?raw=true)  
3. the 3rd method is the undersampling method with a balanced accuracy score of .624 and a precision of .99 and a recall of .44  
![Undersampling BAS](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Undersampling%20BAS.png?raw=true) ![Undersampling Confusion Matrix](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Undersampling.png?raw=true)  
4. The 4th method is the combination over and under sampling method with a balanced accuracy score of .64 and precision of .99 and a recall of .58  
![Combination BAS](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Combination%20Over%20and%20Under%20Sampling%20BAS.png?raw=true) ![Combination Confusion Matrix](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Combination%20Over%20and%20Under%20Sampling.png?raw=true)  
5. the 5th method is the Random Forest Classifier with a balanced accuracy score of .7877 and a precision .99 and a recall of .91  
![BRF BAS](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Random%20Forest%20Classifier%20BAS.png?raw=true)    ![BRF Confusion Matrix](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Random%20Forest%20Classifier.png?raw=true)  
6. the 6th method is the EasyEnsemble Ada Boost Classifier with a balanced accuracy score of .925 and a precisison of .99 and a recall of .94  
![Easy Ensemble BAS](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Easy%20Ensemble%20BAS.png?raw=true)   ![Easy Ensemble Confusion Matrix](https://github.com/dubes1/Credit_Risk_Analysis/blob/main/Easy%20Ensemble.png?raw=true)  
## Summary  
In summary after sampling all the methods I would recommend the Easy Ensemble method because its accuracy and recall scores are so much higher than all the other methods
