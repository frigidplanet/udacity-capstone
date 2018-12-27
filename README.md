# Starbucks Capstone Challenge

### Summary

This project analyzes data provided by the program to determine which rewards customers should not be sent offers.  If a customer was previously sent an offer and did not view it but still completed it then the offer was unecessary.  Using this data I built several models to try and predict when an offer would not be necessary using basic profile information.  This is in the hopes of solving the cold-start problem for new customers.

Overall, RandomForestClassifier obtained the best results of all the testing performed.

### Libaries

- python 3.6.6
- pandas 0.23.4
- py-xgboost 0.8
- scikit-learn 0.20.0
