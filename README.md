# Voice-based Age Detection NUAIH Competition

This repository contains the notebooks used for Kaggle's competition: [Age capturing from speech signals](https://www.kaggle.com/competitions/nuaih-age-capturing-from-speech-signals)
The [dataset](https://www.kaggle.com/competitions/nuaih-age-capturing-from-speech-signals/data) can be found on the competition's page

Three notebooks can be found:

-	NUAIH_Explore: execute exploratory data analysis on the dataset to decide on needed preprocessing steps.

-	NUAIH_ML: feature extraction (pitch, tempo, MFCCs) and use machine learning models as XGBoost, Gradient Boosting Regressor to predict the age.

-	NUAIH_DL: use YAMNET deep neural network to extract embeddings for the audios and then feed them to CNN network to predict age.


