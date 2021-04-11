# Stock-Market-Sentiment-Analyser-for-Algorithmic-Trading

# DATA LABELLING : 
1. The dataset containing 2099 entries has been obtained from Kaggle, using statements hinting at a financial bias. 
2. The individual sentiment of each data entry has been assigned using Sentiment Intensity Analyser. 
3. The positive, negative, neutral, and compound intensities are calculated and a buffer of 0.33 was found, which ultimately helped in assigning the individual sentiments. 

# DATA MODELLING (SENTIMENT ANALYSER) : 
1. Logistic Regression has been performed on the dataset after cleaning, but the accuracy of only “Positive” sentiments (1) was calculated. 
2. To calculate accuracies of both 1 and 0, SMOTE is used which will simplify calculations on the imbalanced data by oversampling (to increase training data).
3. Logistic Regression is applied again, which now shows the accuracies of both 1 and 0 with a decreased accuracy of 1. 
4. For further verification, XGBoost is applied which shows an accuracy of around 0.72. 
5. Ensemble model has been applied to calculate and record which statistical models have good F1 scores. 
6. Using hyper-parameter tuning, we could concluded the results.
