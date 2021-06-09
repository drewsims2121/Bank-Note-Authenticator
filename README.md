# Bank-Note-Authenticator

The purpose of this project is to create a Bank Note Authenticator, and then use a Flask API in order to create a more user friendly front end to authenticate new bank notes

**Jupyter Notebook**
There are 4 features being predicted off of in this project which are variance, skewness, curtosis, and entropy.
These features are fitted into a Random Forest Classifier to learn and predict results from the test test.
These classifier instance file is then pickled so that they can be exported from Jupyter Notebook, and imported into Spyder IDE.

**Spyder IDE**
The pickled classifier instance is imported into Spyder.
The flask API is created within Spyder.
The API creates two versions of using the classifer
  - The first is where you can manually enter values for the 4 features to predict off of
  - The second is an option where you can upload a file with multiple different bank notes for the classifier to predict off of so that each one does not have to be manually       entered
