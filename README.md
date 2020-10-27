# Data-Science
Data source: https://www.kaggle.com/kingburrito666/cannabis-strains

Goal of the model:
Take input info from users, including strain type, rating, effects, and flavors, the model will give the recommended strain name. 

How does the model work? 
Step1: Convert the users' input into numbers by using Spacy (Natural Language Processing Package), which is a open-source library for advanced Natural Language Processing (NLP) in Python. Spacy is a package developed by neural network. 
Step2: NearestNeighbors model is used, which is used to calculate the distance of different vectors. 
Step3: NearestNeighbors model provides the index of closest strain name, and then the strain name will be extracted from the original dataframe. 

The model is saved as a .pkl file, so people who need the model can just load the model by using the pickle.load. 
