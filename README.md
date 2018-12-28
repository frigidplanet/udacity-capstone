# Starbucks Capstone Challenge

### Summary

This project analyzes data provided by the program to determine which rewards customers should not be sent offers.  If a customer was previously sent an offer and did not view it but still completed it then the offer was unecessary.  Using this data I built several models to try and predict when an offer would not be necessary using basic profile information.  This is in the hopes of solving the cold-start problem for new customers.

Overall, RandomForestClassifier obtained the best results of all the testing performed.

## Motivation

I was initially hestitant to choose this data set and problem.  But after looking at the data and pondering it for a few days the ideas started flooding in.  I settled on focusing on the cold-start problem and left ROI analysis for a later time.  It was fascinating that I could get so many data points from so little data.

## Files

- ./data/portfolio.json
- ./data/profile.json
- ./data/transcript.zip
  - zipped json file
- Starbucks_Capstone_notebook.ipynb
- udacity_capstone.pdf

### Libaries

- python 3.6.6
- pandas 0.23.4
- py-xgboost 0.8
- scikit-learn 0.20.0
- seaborn 0.9.0

### Acknowledgements

I heavily utilized stackoverflow, as always, and greatly appreciate all the community provides.  I've done my best to include links in the code if I found an answer particularly helpful.
