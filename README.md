
# Detecting Fake News From Twitter

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

This problem is a Kaggle Comptetion in which the goal is to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.
Dataset includes 10,000 tweets that were hand classified. Dataset is originally from https://appen.com/open-source-datasets/

We first start with a very simple model (Rigid classifier on sparse data) as a hand-on explained in the Kaggle.
Then more data exploraation, and visualizations are added. Two other models including random forest classifier and xgboost classfieir are added and evaluated using different metrics.
