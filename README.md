# Credit Card - Fraud Detection <br><br/>

[![kaggle](https://img.shields.io/badge/_-Open_in_Kaggle-informational?style=plastic&logo=kaggle&logoColor=white&color=045bab&link=https://www.kaggle.com/code/martinab/credit-card-fraud-detection?scriptVersionId=113900916)](https://www.kaggle.com/code/martinab/credit-card-fraud-detection?scriptVersionId=113900916)

### Introduction
Credit card fraud is any kind of theft or fraud that involves a credit card. The aim of credit card fraud is to purchase goods without paying, or to steal money from someone else’s credit account.

We can break down the types of credit card fraud into four main areas:

 - Lost or stolen cards that are used without their owner’s permission
 - Skimmed cards - this is when the card is cloned or copied with a special swipe machine to make a duplicate of the card
 - Card-not-present - card details such as card number, holder/account name, date of birth and address are stolen, often from online databases or through phishing, then sold and used on the internet, or over the phone
 - Committing fraudulent applications in someone else’s name for a new credit card, without that person knowing

Credit card fraud is in general a rare event in comparison to the amount of genuine transactions. After we go through exploratory data analysis we find out that the dataset is very imbalanced. About 99.8% transactions are genuine and those identified as fraudulent represent approximately 0.2%. We can get over 99% model accuracy easily just by assuming that every transaction Class is equal to 0. This sounds great!

Actually, not really. Our model won't have enough data for fraudulent transactions to learn how to recognise them. This will cause that we won't be able to capture fraud.

In reality Fraud Analytics teams use the combination of different techniques to identify fraud, for example:

Rules based systems, with thresholds set manually and based on previous experience;
Matching data to external lists of fraudulet accounts and names;
Use machine learning algorithms to detect fraud or suspicious behaviour

<br><br/>


### Targets
 1. Use of Synthetic Minority Oversampling Technique (SMOTE) method that creates data artificially to balance dataset. It creates more sophisticated and realistic dataset. Downsite of this approach is that we are basically training on 'fake' data.


### Acknowledgements

The source of data for this project is from Kaggle's dataset called Credit Card Fraud Detection. <br><br/>

Useful links:
 - [SMOTE](https://www.youtube.com/watch?v=adHqzek--d0)
